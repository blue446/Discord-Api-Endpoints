POST: https://discord.com/api/v6/auth/login
This is the format that you must follow in order to successfully login
I have put this into a .env i suggest you'd do the same.
``Login = "{\"email\":\"@gmail.com\",\"password\":\"password\",\"undelete\":false,\"captcha_key\":null,\"login_source\":null,\"gift_code_sku_id\":null}"``

``
```py
class Login():
    #headers = ({'content-type': "application/json"}) 
    load_dotenv() # So it won't return None
    Creds = os.getenv("Login")

LoginNToken = r.post("https://discord.com/api/v6/auth/login", data=Login.Creds, headers=Login.headers) #Login Var is the token FYI
Token = LoginNToken.json()["token"]
print(Token)
LoginNTokenHeaders = LoginNToken.headers
print(LoginNTokenHeaders)
```
If you've done this correcly it'll return for e.g
```
{'token': 'Your account token', 'user_settings': {'locale': 'en-US', 'theme': '
dark'}}
