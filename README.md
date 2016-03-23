nginx.conf
========
Recognizing [Kerchhoffs's principle][k], I hereby publish my own nginx
configuration files.

```bash
# hyeon.me
sudo ln -sf "$PWD/hyeonme.conf" /etc/nginx/nginx.conf
sudo ln -sf "$PWD/hyeonme" /etc/nginx/sites
sudo ln -sf "$PWD/options-ssl-nginx.conf" /etc/letsencrypt/
# kuma.hyeon.me
sudo ln -sf "$PWD/kuma.conf" /etc/nginx/nginx.conf
sudo ln -sf "$PWD/options-ssl-nginx.conf" /etc/letsencrypt/

# Test if everything's alright
sudo nginx -t -c /etc/nginx/nginx.conf
```

##### References
- http://nginx.org/en/docs/
- https://github.com/h5bp/server-configs-nginx

[k]: https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle
