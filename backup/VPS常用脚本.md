## 检查IP解锁

```
bash <(curl -Ls IP.Check.Place)
```

## X-UI

```
bash <(curl -Ls https://raw.githubusercontent.com/FranzKafkaYu/x-ui/master/install.sh)
```

## 一键四协议(vless-reality|vmess-ws-tls(argo)|hysteria2|tuic5)
**支持的系统：Ubuntu/Debian/CentOS/Alpine/Fedora/Rocky/Almalinux/kail**

```
bash <(curl -Ls https://raw.githubusercontent.com/eooce/sing-box/main/sing-box.sh)
```

## ssh综合工具箱一键脚本
**支持的系统：Ubuntu/Debian/CentOS/Alpine/Fedora/Rocky/Almalinux/kail**

```
curl -fsSL https://raw.githubusercontent.com/eooce/ssh_tool/main/ssh_tool.sh -o ssh_tool.sh && chmod +x ssh_tool.sh && ./ssh_tool.sh
```

## ArgoX（包含Vless、Vmess、Trojan）
#### 可使用Cloudflare固定隧道，无需root

```
bash <(curl -Ls https://main.ssss.nyc.mn/argox.sh)
```
### 卸载ArgoX👇
```
ps aux | grep -E '[w]eb|[n]pm|[b]ot' | awk '{print }' | xargs -r -n 1 kill -9
```

致谢：[FranzKafkaYu](https://github.com/FranzKafkaYu)   [eooce](https://github.com/eooce)  
