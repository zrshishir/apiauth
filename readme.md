Step1: Download the project

Step2: Setting Database credentials in .env file

Step3: run the command 'composer install'

Step4: run your project using 'php artisan serve'

Step5: run the command 'php artisan migrate'

Step6: run your postman app

Step7: add this url on your postman for posting http://127.0.0.1:8000/api/register and add your email, password on body section on postman for registration 
      
        key:name, value:your name
        key:email , value:your email,
        key:password, value:your password
        key:c_password, value: your password
click on send button and you will get a token with user name save it

Step8: add this url on your postman for posting http://127.0.0.1:8000/api/login and add your email, password on body section on postman for registration 

        key:email , value:your email,
        key:password, value:your password
        
        click on send button
        
        
Step9: add this url on your postman for posting http://127.0.0.1:8000/api/details and add below credentials on headers section on postman for getting detail about user information 

        key:Authorization, value:Bearer <your response token>
        key:Content-Type , value:application/x-www-form-urlencoded,
        key:Accept, value:application/json
        
        click on send button
