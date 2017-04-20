# Nginx Configurations for a Secure Reverse Proxy
[![Runtime][runtime-badge]][nginx-runtime-url]
[![License][license-badge]][nginx-license-url]

**Nginx Configurations for a Secure Reverse Proxy** is a collection of Nginx configurations that include some best practices to secure your application.

It's based and inspired by [**Nginx Server Configs**][h5bp-server-configs-nginx] and other materials that I found over the internet.

## Usage

Clone this repository to `/etc/nginx` and adapt the examples available in `/etc/nginx/site-available` to your application configuration.

After that, just create a referral symbolic link in `/etc/nginx/site-enabled`.

## License and Author

See `LICENSE` for more details.

   [h5bp-server-configs-nginx]: https://github.com/h5bp/server-configs-nginx
   [nginx-runtime-url]: https://github.com/amalucelli/nginx-config-reverse-proxy
   [nginx-license-url]: https://github.com/amalucelli/nginx-config-reverse-proxy/blob/master/LICENSE
   [license-badge]: https://img.shields.io/badge/license-mit-757575.svg?style=flat-square
   [runtime-badge]: https://img.shields.io/badge/runtime-nginx-orange.svg?style=flat-square
