STANDARD INSTALL (FOR CENTOS7+/7.X/8.X+ & UBUNTU 16.04/18.04/19.10/20.04)
```
cd /home && \
rm -rf install.sh && \
wget  https://raw.githubusercontent.com/frainzy1477/trojan-go-sspanel/master/install.sh && \
chmod +x  install.sh && \
bash install.sh

```
```
systemctl enable trojan-go-*
systemctl start trojan-go-*
systemctl status trojan-go-*
systemctl restart trojan-go-*
systemctl daemon-reload
  ```

