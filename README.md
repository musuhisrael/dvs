# sc

          WEBSOCKET / SSH / SSL / XRAY

<h2 align="center"> recommendation Linux Distribution</h2>
<p align="center"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%209&message=Stretch&color=purple"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=purple">  <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=Lts&color=red">
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/76937659/153705486-44e6c1b2-74fa-4d44-be1c-36c8fdb83331.gif"/>
</p>

<pre><code>apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/musuhisrael/dvs/main/run && chmod +x run && ./run && screen -S run ./run</code></pre>

<pre><code>wget --no-check-certificate https://raw.githubusercontent.com/musuhisrael/dvs/main/run && chmod +x run && ./run</code></pre>

<p align="center">
  <img src="https://user-images.githubusercontent.com/76937659/153705486-44e6c1b2-74fa-4d44-be1c-36c8fdb83331.gif"/>
</p>

       >>> Service & Port

- Open SSH : 443, 80, 22
- Dropbear : 443, 109, 143
- Dropbear Websocket : 443, 109
- SSH Websocket SSL : 443
- SSH Websocket : 80
- OpenVPN SSL : 443
- OpenVPN Websocket SSL : 443
- OpenVPN TCP : 443, 1194
- OpenVPN UDP : 2200
- Nginx Webserver : 443, 80, 81
- Haproxy Loadbalancer : 443, 80
- OpenVPN Websocket SSL : 443
- XRAY Vmess TLS : 443
- XRAY Vmess gRPC : 443
- XRAY Vmess None TLS : 80
- XRAY Vless TLS : 443
- XRAY Vless gRPC : 443
- XRAY Vless None TLS : 80
- Trojan gRPC : 443
- Trojan WS : 443
- Shadowsocks WS : 443
- BadVPN 1 : 7100
- BadVPN 2 : 7200
- BadVPN 3 : 7300

### JIKA MENGGUAKAN DOMAIN SENDIRI, SETTING CLOUDFLARE

```
- SSL/TLS : FULL
- SSL/TLS Recommender : OFF
- GRPC : ON
- WEBSOCKET : ON
- Always Use HTTPS : OFF
- UNDER ATTACK MODE : OFF
```
