## OpenVPN check

Retrieve OpenVPN server metrics via admin port command 'load-stats'.

```
app_checks:
  - name: openvpn
    check_module: openvpn
    pattern:
      comm: openvpn
    conf:
      domain: vpn.example.tld
      port: 7505
      password: your_password
```
