## Bypass OTP

Wrong Response | Manipulate Response
----------------|--------------------
**{"status":"0","message":"Incorrect OTP. Please Try Again"}** | **{"status":"1","message":"Correct OTP"}**
**{"error"}** | **{"Success"}**
**{"verificationStatus":false,"mobile":"+62xxxxxxxx","profileId":"450xxxxx"}** | **{"verificationStatus":true,"mobile":"+62xxxxxxxx","profileId":"450xxxxx"}**
**Input String On OTP if Blank Response Value 200 OK** | **Add number 1 on Value**
**Input Wrong Captcha if Response Value 7** | **Change 7 to 1**

##### Bypass OTP #2
> Input 000000 Code To Bypass OTP

---

#### Authentication Bypass Due OTP Exposure

##### Tips #1
1. Register/Login into the system
2. After that Intercept That Request and Intercept Response.
3. **{"status_code":200, "OTP":4800,"user_id":"ef0245zxxxxxxxxx"}**
4. Boom OTP expose on Response Register/Logged in.
5. Use OTP, Done

##### Tips #2
1. Input phone number, and hen send .
2. Intercept Request and intercept response.
3. **{"msg":"success","OTP":601823}**
4. Boom OTP Exposed.
5. You can use OTP, Done






