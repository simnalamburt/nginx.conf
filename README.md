> **WARNING**: This project is no longer actively maintained. I have changed
> my personal homepage's web server into [Caddy](https://caddyserver.com).
> Since TLS 1.3 related settings are not applied to this config, so this
> project is highly likely to be outdated soon.

nginx.conf
========
Recognizing [Kerchhoffs's principle], I hereby publish my own nginx
configuration files.

```bash
sudo ln -sf "$PWD/nginx.conf" /etc/nginx/
sudo ln -sf "$PWD/options-ssl-nginx.conf" /etc/letsencrypt/

# Test if everything is alright
sudo nginx -t -c /etc/nginx/nginx.conf
```

##### References
- http://nginx.org/en/docs/
- https://github.com/h5bp/server-configs-nginx
- https://github.com/yandex/gixy

[Kerchhoffs's principle]: https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle
