```py
e = https://discord.com/api/v6/auth/login
LoginNToken = r.post(e, data=Login.Creds, headers=Login.headers) #Login Var is the token FYI
Token = LoginNToken.json()["token"]
print(Token)
LoginNTokenHeaders = LoginNToken.headers
print(LoginNTokenHeaders)
```
