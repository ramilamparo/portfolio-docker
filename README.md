# Build parameters

`--db-pass` Postgres password.

`--db-user root` Postgres username.

`--db-name portfolio` Postgres database name.

`--gatsby-port 48620` Port to serve gatsby frontend.

`--cms-port 48621` Port to serve strapi cms.

`--captcha-site-key captcha_frontend_key` Frontend captcha key to prevent spam.

`--captcha-secret-key` Backend captcha key to prevent spam.

`--jwt-secret secret_key` JWT secret key for generating login token.

`--email-user contact@ramilamparo.com` Your smtp user for sending inquiries to contact-email

`--email-pass email_pass` Your smtp password.

`--email-host mail.privateemail.com` Your smtp server address.

`--contact-email contact@ramilamparo.com` Email where site visitors will send inquiries.

`--gatsby-browser-api-url https://cms.ramilamparo.com` Where gatsby will send inquiries from browser.

`--static-folder /var/www/static/cms` Where strapi will store uploaded media files.

## Example

```
build \
--db-pass db_pass \
--db-user root \
--db-name portfolio \
--gatsby-port 48620 \
--cms-port 48621 \
--captcha-site-key captcha_site_key \
--captcha-secret-key captcha_secret_key \
--jwt-secret jwt_secret \
--email-user contact@ramilamparo.com \
--email-pass email_password \
--email-host mail.privateemail.com \
--contact-email contact@ramilamparo.com \
--gatsby-browser-api-url https://cms.ramilamparo.com \
--static-folder /var/www/static/cms
```
