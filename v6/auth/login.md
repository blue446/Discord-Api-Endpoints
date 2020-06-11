```py

LoginNToken = r.post("https://discord.com/api/v6/auth/login", data=Login.Creds, headers=Login.headers) #Login Var is the token FYI
Token = LoginNToken.json()["token"]
print(Token)
LoginNTokenHeaders = LoginNToken.headers
print(LoginNTokenHeaders)
```
