# This file represents what is needed to send a message.
so far I've only found that you can send a message once every {} minutes with the default Nonce
so far
```py
import requests
import random
import json
url = "https://discord.com/api/v6/channels/{channelID}/messages"
def random_with_n_digits(n):
    range = 10**(n-1)
    end = (10**n)-1
    return random.randint(range, end)
e = (random_with_n_digits(18))
print(e)
payload = ({"content":"Test#2", "nonce":e, "tts":"false"})
print(payload)
headers = {
    'x-super-properties': "",
    'authorization': "UserToken",
    'user-agent': "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/81.0.4044.138 Safari/537.36",
    'content-type': "application/json"
    }

response = requests.request("POST", url, data=payload, headers=headers)
print(response.json(), response)
```

Note: Not sure if the ``def random_with_n_digits(n)`` is needed nor ``headers = {'x-super-properties': ""}``

**UPDATE**: I've timed about 11min from each message i'll try for 10 next.
