nginx.conf
========
Recognizing [Kerchhoffs's principle][k], I hereby publish my own nginx
configuration files.

```bash
sudo ln -sf "$PWD/hyeonme.conf" /etc/nginx/nginx.conf
sudo ln -sf "$PWD/hyeonme" /etc/nginx/sites

# Test if everything's alright
sudo nginx -t -c /etc/nginx/nginx.conf
```

[k]: https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle
