## Trojan-Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/EdyDevz/Trojan-Heroku)

### CONFIG OPENCLASH

```
  - name: TROJAN HEROKU
    server: #HOSTNAME
    port: 443
    type: trojan
    password: xynte
    skip-cert-verify: true
    sni: #BUG.COM
    network: ws
    ws-opts:
      path: /xynte
      headers:
        Host: #HOSTNAME
    udp: true
```

### CONFIG V2RAY

```
trojan://xynte@GANTI HOSTNAME HEROKU:443?path=%2Fxynte&security=tls&host=GANTI+HOSTNAME+HEROKU&type=ws&sni=BUG.COM#TOJAN+HEROKU
```