# otp-phone-auth-using-firebase-php

1. Firebase only works in JavaScript so I am sending this request to php using jQuery Ajax
2. After receiving success code 1, we are performing sending OTP
3. Hide the register form and show otp form
4. after entering OTP and clicking the button first verify the OTP by firebase' confirm method
5. if it works fine then send to ajax and save sassion in PHP.

#All the Best

# ##If you still find any trouble in you coding you can contact me by visiting my profile or mail me on
rizwanpatel.rnk@gmail.com


# firebase response to get more info

it gives response in object form you can convert to json by
JSON.stringify(result);

Sent code response 
{"verificationId":"AIndW9BdMyz8qf0QZxjBhIF-C6UfqCmzZY1HaTNGpEUXImbGJqGqEN5_ZJE5cWuzllgpCM60XJ7Uk82RafFdEvVcJ326h6dGQikbDUawhteDGXsznHM8c9oHy8Y2RWyP8CENq7LqJqbWIVQgJZDvWeanAnhwJOXcYdt1LLJ96s5ccSPTSxbDhq8_UGeK9UM3xw7DovYu-cTBkwTURc85COU9GU4rE72PI4pUBi1eBUCcEoWPqD_7RUE"}

Verify OTP response 
{"uid":"9F86JAxu8eMHLHmrv28nQyk1bey2",
"emailVerified":false,"isAnonymous":false,"phoneNumber":"+918962423386","providerData":[{"providerId":"phone","uid":"+918962423386","displayName":null,"email":null,"phoneNumber":"+918962423386","photoURL":null}],"stsTokenManager":{"refreshToken":"AOkPPWR76yFLcIVMT0PIqOsjPGNMj9TUUJjnDqCwqakb1Gx85KHG1ADQleIPQqUNXnLLONaKTWOwO4_hpGjY48u1bDxL62h2qehiI8ZMwKzKclhIjyrQ8ul-n04SLt8tqQNTPmEhCmTUULLv3WOwYAvbEOnmxbTVuirrhvYeh_3QqNB1NBFz-gxZCJSueidLAubQlG_c3C5z","accessToken":"eyJhbGciOiJSUzI1NiIsImtpZCI6ImY1NWU0ZDkxOGE0ODY0YWQxMzUxMDViYmRjMDEwYWY5Njc5YzM0MTMiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL3NlY3VyZXRva2VuLmdvb2dsZS5jb20vd2lucml0LW90cCIsImF1ZCI6IndpbnJpdC1vdHAiLCJhdXRoX3RpbWUiOjE2NzM5MjU4NzcsInVzZXJfaWQiOiI5Rjg2SkF4dThlTUhMSG1ydjI4blF5azFiZXkyIiwic3ViIjoiOUY4NkpBeHU4ZU1ITEhtcnYyOG5ReWsxYmV5MiIsImlhdCI6MTY3MzkyNTg3NywiZXhwIjoxNjczOTI5NDc3LCJwaG9uZV9udW1iZXIiOiIrOTE4OTYyNDIzMzg2IiwiZmlyZWJhc2UiOnsiaWRlbnRpdGllcyI6eyJwaG9uZSI6WyIrOTE4OTYyNDIzMzg2Il19LCJzaWduX2luX3Byb3ZpZGVyIjoicGhvbmUifX0.jYVcK_ggoreoQIWJLAGLJRggvqzLv5Hys72xbCLJOnk3ekna1cOchyxDXSLI0WR9PxFI2ljO2fyqNRqyZLyRIZrOxonhhIjsVqUPz_4o8rnNuoU9gFiS4ooFwdDI6qs5v5uZOpFAhUa2IctsGFWEvSoot_BubsQ4KBRQzOENk3gZbXZpdScB9YLZol8ZIcMlTQNPHzfDhg9uUugLDEJb8yCjotRcx5rWsXcLjICMKT8BJLHTh9GBHlboFGP8FUhQHYlDgPvzN812YGO1ACmb4wAtNmQWUo-HeybLlrk3rh2TKPk3a0g8b8qbOBdK7R_b3_qyMEBCtSsviKLr6KfdkA","expirationTime":1673929479455},"createdAt":"1673921892363","lastLoginAt":"1673925877325","apiKey":"AIzaSyDIDt2u5SFy7jdvXJ4Dzg6QaEfrueGV938","appName":"[DEFAULT]"}
