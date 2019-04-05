# CI-LiteAdmin

CodeIgniter 3.1.10 with LiteAdmin 2.0
Code Sample

## Installation

1. Unzip the package.
2. Upload the `CI-LiteAdmin` folders and files to your server.
3. Update `application/config/common/dp_config.php` file:

```
$host_dev = 'LiteAdmin';
// where your project is hosted
$host_prod = 'http://localhost/LiteAdmin';
```

4. Create a table named `ci_LiteAdmin` and inject the data from the `install/sql/ci_LiteAdmin.sql` file.
5. Change if necessary the connection information to your database in the `application/config/database.php` file.

### Login

- Email : `admin@admin.com` / Password : `password`

## Browser Compatibility

Support for most major browsers including Chrome, Firefox, IE9+, Opera and Safari.

## Server Requirements

PHP version 5.6 or newer is recommended.

It should work on 5.4.8 as well, but we strongly advise you NOT to run such old versions of PHP, because of potential security and performance issues, as well as missing features.

## Dependencies

| NAME          | VERSION |                     WEB                      |                             REPO                             |
| :------------ | :-----: | :------------------------------------------: | :----------------------------------------------------------: |
| CodeIgniter   | 3.1.10  |      [Website](https://codeigniter.com)      |     [Github](https://github.com/bcit-ci/CodeIgniter/) )      |
| Bootstrap     |  3.3.7  | [Website](https://getbootstrap.com/docs/3.3) |         [Github](https://github.com/twbs/bootstrap)          |
| Ion Auth      |  2.6.0  |  [Website](http://benedmunds.com/ion_auth)   | [Github](https://github.com/benedmunds/CodeIgniter-Ion-Auth) |
| jQuery        |  2.2.4  |         [Website](http://jquery.com)         |          [Github](https://github.com/jquery/jquery)          |
| Font Awesome  |  4.7.0  |  [Website](https://fontawesome.com/v4.7.0)   |    [Github](https://github.com/FortAwesome/Font-Awesome)     |
| Mobile Detect | 2.8.30  |      [Website](http://mobiledetect.net)      |    [Github](https://github.com/serbanghita/Mobile-Detect)    |

## CodeIgniter 3 Documentation

- [User guide](https://codeigniter.com/user_guide)

## Reference

- [CodeIgniter](https://github.com/bcit-ci/CodeIgniter)
- [Translations for CodeIgniter System](https://github.com/bcit-ci/codeigniter3-translations)
