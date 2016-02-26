nginx.conf
========
Recognizing [Kerchhoffs's principle][k], I hereby publish my own nginx
configuration files.

```bash
# Install
sudo ln -sf "$PWD/nginx.conf" /etc/nginx/
sudo ln -sf "$PWD/options-ssl-nginx.conf" /etc/letsencrypt/

# Test if everything's alright
sudo nginx -t -c /etc/nginx/nginx.conf
```

[k]: https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle
