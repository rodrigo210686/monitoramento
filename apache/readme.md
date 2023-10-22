## Habilite os modulos do apache

```sh
sudo a2enmod ssl
sudo a2enmod proxy
sudo a2enmod proxy_balancer
sudo a2enmod proxy_http
```

/etc/grafana/grafana.ini
```sh

[server]
http_addr =
http_port = 3000
domain = esim.com.br
root_url = http://grafos.esim.com.br/
#cert_key = /etc/grafana/grafana.key
#enforce_domain = False
protocol = http
socket =
enable_gzip = False
#cert_file = /etc/grafana/grafana.crt
static_root_path = public
router_logging = False
```` 

