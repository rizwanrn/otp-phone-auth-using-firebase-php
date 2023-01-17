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
{"verificationId":"AIndW9BdMyzsdsdf8qf0QZxjBhIF-C6UfqCmzZY1HaTNHM8c9oHy8Y2RWyP8CENq7LqJqbWIVQgJZDvWeanAnhwJOXcYdt1LLJ96s5ccSPTSxbDhq8_UGeK9UM3xw7DovYu-cTBkwTURc85COU9GU4rE72PI4pUBi1eBUCcEoWPqD_7RUE"}

Verify OTP response 
{"uid":"sdfsdfsdfsdfdsf####",
"emailVerified":false,"isAnonymous":false,"phoneNumber":"+918######","providerData":[{"providerId":"phone","uid":"+918######","displayName":null,"email":null,"phoneNumber":"+918######","photoURL":null}],"stsTokenManager":{"refreshToken":"AOkPPWR76yFLcIVMT0PIqOsjPGNMj9TasdasdUNXnLLONaKTWOwO4_hpGjY48u1bDxL62h2qehiI8ZMwKzKclhIjyrQ8ul-n04SLt8tqQNTPmEhCmTUULLv3WOwYAvbEOnmxbTVuirrhvYeh_3QqNB1NBFz-gxZCJSueidLAubQlG_c3C5z","accessToken":"asd..asd-asd","expirationTime":1673929479455},"createdAt":"1673921892363","lastLoginAt":"1673925877325","apiKey":"asdasd","appName":"[DEFAULT]"}
