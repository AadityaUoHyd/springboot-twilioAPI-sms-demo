# springboot-twilio-sms-demo

- First of all create Twilio account. login there. Get your own account_sid, auth_token, trial_number, and put that in springboot "application.yml" file.

- Run the code as Spring boot program.

- Go to postman tool and with url: http://localhost:8080/api/v1/sms

{
  "phoneNumber" : "+xxxxxxxxxxx",    //your mobile no
  "message":"Hello world! This is Aaditya With his first Spring boot Twilio integration success msg"
}

- Output : You’ll receive above message.

PS : In case you want to change the 'trial_number' to real time 'from name' then go through this twilio document : https://support.twilio.com/hc/en-us/articles/223133967-Change-the-From-number-or-Sender-ID-for-Sending-SMS-Messages 
