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
3. **{"success":true,"msg":"otp is Verified successfully.","user_id":"6342","redirect_uri":"create_package"}**
4. Change **"user_id":"6342"** To Another ID exp.6343

---

##### Tips 3 > Account Take Over Due to 2FA Logic Flow
1. Register/Login into Account.
2. enabled 2FA authentication Intercept Request and send to Repeater and then logout.
3. before doing perform logged in **Enabled 2FA : 1** Change to **0** of value.
4. Login again , and boom

---

#### Tips 4 > Account Take Over Of Support And Ceo Email Due to Logic Flow
1. Register on xyz.com with email **admin@gmail.com**
2. Verif Email.
3. Login again to xyz.com
4. You redirected to dashboard and then **Adding Other email address as Temporary email ex.attacker@gmail.com** And Activation Login has been send to attacker@gmail.com
5. Logout and Visit to your gmail account **admin@gmail.com** and then reuse verfification link, with way clicking link below.
6. Login with email **attacker@gmail.com** Boommm.

---
