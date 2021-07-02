#Laravel/PHP Project to send mail using AWS SES service

####Steps to cconfig the project:

1. Clone your project
2. Go to the folder application using cd command on your cmd or terminal
3. Run composer install on your cmd or terminal
4. Copy .env.example file to .env on the root folder. You can type copy .env.example .env if using command prompt Windows
5. Open your .env file and change the following things:
	MAIL_MAILER=smtp
	MAIL_HOST=email-smtp.us-east-2.amazonaws.com
	MAIL_PORT=587
	MAIL_USERNAME="User name that one get from aws smtp configuration"
	MAIL_PASSWORD="User password that one get from aws smtp configuration"
	MAIL_ENCRYPTION=tls
	MAIL_FROM_ADDRESS="yourmail@gmail.com"
	MAIL_FROM_NAME="${APP_NAME}" 
6. Run php artisan serve in cmd
7. Goto localhost:8000/contact
