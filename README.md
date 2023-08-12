<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Project with the objective of learning and improving skills with Laravel

- MySQL database
- Export to PDF/Excel
- Route settings
- Integration with Bootstrap
- Composer
- Authentication System
- MVC and more...

To test it, it is necessary to configure the .env file with an email and generate an access password.

-<h3> Gmail</h3>

    MAIL_MAILER=smtp
    MAIL_HOST=smtp.gmail.com
    MAIL_PORT=587
    MAIL_USERNAME= {"your email here"}
    MAIL_PASSWORD= {"password"}
    MAIL_ENCRYPTION=TLS
    MAIL_FROM_ADDRESS="${MAIL_USERNAME}"
    MAIL_FROM_NAME="${APP_NAME}"

1 - Click on the option "Manage your Google Account" <br/>
2 - Click on the "Security" option <br/>
3 - Turn on the "Two-Step Verification" option <br/>
4 - Click on the "App passwords" option (If it doesn't appear, search for it ) <br/>
5 - Click on the option "Select the app and device for which you want to generate the app password" and choose the option "Other" <br/>
6 - Define a name (can be any name) and then click "generate" <br/>
7 - The password will be generated, just copy it <br/>
8 - Use the password copied in the project configuration file (.env, 'MAIL_PASSWORD') <br/>


The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
