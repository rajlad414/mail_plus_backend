# Laravel/PHP Project to send mail using AWS SES service

#### Steps to cconfig the project:
1. Clone your project
2. Go to the folder application using cd command on your cmd or terminal
3. Run composer install on your cmd or terminal
4. Copy .env.example file to .env on the root folder. You can type copy .env.example .env if using command prompt Windows
5. Open your .env file and change the following things:<br>
	MAIL_MAILER=smtp<br>
	MAIL_HOST=email-smtp.us-east-2.amazonaws.com<br>
	MAIL_PORT=587<br>
	MAIL_USERNAME="User name that one get from aws smtp configuration"<br>
	MAIL_PASSWORD="User password that one get from aws smtp configuration"<br>
	MAIL_ENCRYPTION=tls<br>
	MAIL_FROM_ADDRESS="yourmail@gmail.com"<br>
	MAIL_FROM_NAME="${APP_NAME}" <br>
6. Run php artisan serve in cmd
7. Goto localhost:8000/contact
