# Docked Nginx & PHP-FPM

> A dockerized Nginx & PHP-FPM

## generate certificate

run this to generate ssl certificate for local development

```bash
$ mkcert -cert-file ./cert/docked.mvp.crt -key-file ./cert/docked.mvp.key "docked.mvp" "*.docked.mvp"
```

edit the file names in `./conf/nginx.shared.conf` if you change the output files