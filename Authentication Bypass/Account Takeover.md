### Account Takover


##### Tips 1
1. Login with original user 
2. Intercept Response 
3. **{"success":false,","data":{"address":[],"customer":{"id":318620,"full_name":null,"email":original@gmail.com","phone":"+62xxxxxxxxxxx","is_login":1,"last_login":"2021-04xxxxxxx","created_at":2021-04xxxxxx,"updated_at":2021-04xxxxx}},"message":"Csutomer login successfully"}**
4. Change **"id":"318620"** To Another ID exp.318621

---
##### Tips 2
1. Login with original user 
2. Intercept Response 
3. {"success":true,"msg":"otp is Verified successfully.","user_id":"6342","redirect_uri":"create_package"}
4. Change **"user_id":"6342"** To Another ID exp.6343
