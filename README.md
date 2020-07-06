<p align="center"><a href="https://github.com/Luca-Castelnuovo/Deploy"><img src="https://rawcdn.githack.com/Luca-Castelnuovo/Deploy/09849e0612d3b4ea98589b0b49605483b4164170/public/assets/images/banner.png"></a></p>

<p align="center">
<a href="https://github.com/Luca-Castelnuovo/Deploy/commits/master"><img src="https://img.shields.io/github/last-commit/Luca-Castelnuovo/Deploy" alt="Latest Commit"></a>
<a href="https://github.com/Luca-Castelnuovo/Deploy/issues"><img src="https://img.shields.io/github/issues/Luca-Castelnuovo/Deploy" alt="Issues"></a>
<a href="LICENSE.md"><img src="https://img.shields.io/github/license/Luca-Castelnuovo/Deploy" alt="License"></a>
</p>

# Deploy

Auto deploy and build with Github webhooks.

## Installation

For development

1. `git clone git@github.com:Luca-Castelnuovo/Deploy.git`
2. Edit `.env`
3. `php cubequence app:key`
4. `php cubequence db:migrate`
5. `php cubequence db:seed`
6. Start development server `php -S localhost:8080 -t public`

For deployment

1. `git clone git@github.com:Luca-Castelnuovo/Deploy.git`
2. `composer install --optimize-autoloader --no-dev`
3. Edit `.env`
4. `php cubequence app:key`
5. `php cubequence db:migrate`

## Security Vulnerabilities

Please review [our security policy](https://github.com/Luca-Castelnuovo/Deploy/security/policy) on how to report security vulnerabilities.

## License

Copyright © 2020 [Luca Castelnuovo](https://github.com/Luca-Castelnuovo). <br />
This project is [MIT](LICENSE.md) licensed.
