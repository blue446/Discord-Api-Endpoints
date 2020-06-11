POST: https://discord.com/api/v6/auth/login
This is the format that you must follow in order for a successfully login
``"{\"email\":\"@gmail.com\",\"password\":\"password\",\"undelete\":false,\"captcha_key\":null,\"login_source\":null,\"gift_code_sku_id\":null}"
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
