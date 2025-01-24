proxies:
- name: SG
  server: sg3.6n6.net
  port: 443
  type: trojan
  password: 0e7eaf90-d536-11ef-9aa3-1239d0255272
  sni: static-quiz.prod.vidiocdn.com
  skip-cert-verify: true
  udp: true
  network: ws
  ws-opts:
    path: /howdy
    headers:
      Host: sg3.6n6.net
