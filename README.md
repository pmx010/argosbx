## Argosbx One-Click Non-Interactive Lightweight Script 💣: Minimalist + Lightweight + Fast

---------------------------------------

<img width="757" height="255" alt="d89e2542c513e705106371acc7fa1d33" src="https://github.com/user-attachments/assets/7d7a4678-4223-478c-afe2-d303ba0f85a4" />


### 【Argosbx Current Version: V25.11.20】

---------------------------------------

#### 1. Based on Sing-box + Xray + Cloudflared-Argo Three-Core Automatic Allocation

#### 2. Supports Linux mainstream VPS systems (latest version recommended), SSH script supports non-root environment running, almost no dependencies, done with one enter key.

#### 3. Supports various container systems, Docker image deployment, public image repository: ```ygkkk/argosbx```

#### 4. According to different Sing-box and Xray kernels, optional 15 WARP outbound combinations, change landing IP to WARP IP, unlock streaming media.

#### 5. All proxy protocols do not require a domain name (except Argo fixed tunnel, IP port CDN), support single or multiple proxy protocol combinations and quick reset/replacement.
【 Supported: AnyTLS, Any-reality, Vless-xhttp-reality-vison-enc, Vless-tcp-reality-vision, Vless-xhttp-vison-enc, Vless-ws-vision-enc, Shadowsocks-2022, Vmess-ws, Socks5, Hysteria2, Tuic, Argo temporary/fixed tunnel supports Vless-ws-vision-enc or Vmess-ws 】

#### 6. Recommended to use with SSH One-Click Script Command Generator webpage: https://yonggekkk.github.io/argosbx/

#### 7. If you need diverse functions, it is recommended to use the VPS dedicated four-in-one script [Sing-box-yg](https://github.com/yonggekkk/sing-box-yg)

#### 8. Argosbx Client Recommendation:

Android Client: [Nekobox-starifly version (All protocols supported)](https://github.com/starifly/NekoBoxForAndroid/releases), [V2rayNG official version](https://github.com/2dust/v2rayNG/releases)

Windows Client: [V2rayN official version (All protocols supported)](https://github.com/2dust/v2rayN/releases)

iOS Client: OneXray, Streisand

----------------------------------------------------------

## I. Custom Variable Parameters Description:

| Variable Meaning | Variable Name| Fill inside ""| Delete Variable | Leave empty inside "" | Requirements & Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1. Enable vless-tcp-reality-v | vlpt | Specify Port | Disable vless-tcp-reality-v | Random Port | One is required 【xray core: TCP】 |
| 2. Enable vless-xhttp-reality-enc | xhpt | Specify Port | Disable vless-xhttp-reality-enc | Random Port | One is required 【xray core: TCP】 |
| 3. Enable vless-xhttp-enc | vxpt | Specify Port | Disable vless-xhttp-enc | Random Port | One is required 【xray core: TCP】 |
| 4. Enable vless-ws-enc | vwpt | Specify Port | Disable vless-ws-enc | Random Port | One is required 【xray core: TCP】 |
| 5. Enable shadowsocks-2022 | sspt | Specify Port | Disable shadowsocks-2022 | Random Port | One is required 【singbox core: TCP】 |
| 6. Enable anytls | anpt | Specify Port | Disable anytls | Random Port | One is required 【singbox core: TCP】 |
| 7. Enable any-reality | arpt | Specify Port | Disable any-reality | Random Port | One is required 【singbox core: TCP】 |
| 8. Enable vmess-ws | vmpt | Specify Port | Disable vmess-ws | Random Port | One is required 【xray/singbox core: TCP】 |
| 9. Enable socks5 | sopt | Specify Port | Disable socks5 | Random Port | One is required 【xray/singbox core: TCP】 |
| 10. Enable hysteria2 | hypt | Specify Port | Disable hy2 | Random Port | One is required 【singbox core: UDP】 |
| 11. Enable tuic | tupt | Specify Port | Disable tuic | Random Port | One is required 【singbox core: UDP】 |
| 12. Warp Switch | warp | See 15 warp outbound modes below | Disable warp | Warp global V4+V6 enabled for singbox & xray | Optional, see 15 warp outbound modes below |
| 13. Argo Switch | argo | Fill vwpt or vmpt | Disable argo tunnel | Disable argo tunnel | Optional, when filling vmpt or vwpt, vmess-ws or vless-ws variable vmpt or vwpt must be enabled, and fixed tunnel must fill vmpt or vwpt port |
| 14. Argo Fixed Tunnel Domain | agn | Domain hosted on CF | Use temporary tunnel | Use temporary tunnel | Optional, fixed tunnel activatable only when argo fills vmpt or vwpt |
| 15. Argo Fixed Tunnel Token | agk | Token starting with ey from CF | Use temporary tunnel | Use temporary tunnel | Optional, fixed tunnel activatable only when argo fills vmpt or vwpt |
| 16. UUID Password | uuid | Conform to uuid format | Randomly generated | Randomly generated | Optional |
| 17. Reality Domain (Only for reality protocols) | reym | Conform to reality domain rules | apple website | apple website | Optional, when using CF domains: combination of server ip:node port, can serve as ProxyIP/Client address reverse proxy IP (Recommended for high ports or pure IPv6 to avoid scanning leaks) |
| 18. Host address for vmess-ws, vless-xhttp/ws-enc in client | cdnym | CF resolved IP domain | vmess-ws, vless-xhttp/ws-enc is direct | vmess-ws, vless-xhttp/ws-enc is direct | Optional, set when using port 80 CDN or origin CDN, otherwise client host address needs manual change to CF resolved IP domain |
| 19. Switch IPv4 or IPv6 config | ippz | Fill 4 or 6 | Auto identify IP config | Auto identify IP config | Optional, 4 means IPv4 config output, 6 means IPv6 config output |
| 20. Add prefix to all node names | name | Any string | Default protocol name prefix | Default protocol name prefix | Optional |
| 21. Open all ports for current system | oap | Fill y | Prohibit opening all ports | Prohibit opening all ports | Optional, run once, delete variable later, no need to run every time |
| 22. 【Container/Docker Only】Listening port, web query | PORT | Specify Port | 3000 | 3000 | Optional |
| 23. 【Container/Docker Only】Enable vless-ws-tls | DOMAIN | Server Domain | Disable vless-ws-tls | Disable vless-ws-tls | Optional, vless-ws-tls can exist independently, uuid variable must be enabled |

------------------------------------------------------------------

* #### As shown below: One-Click SSH Command Generator: [Click for Video Tutorial](https://youtu.be/4u6W4c-t3oU)

<img width="1201" height="800" alt="729cda77f5d7f29dcbab7915ec50b087" src="https://github.com/user-attachments/assets/c2c8d8ea-6526-4628-9a8a-8a5153f04987" />

------------------------------------------------------------------

* #### As shown below: Clawcloud 4 price sets + 7 protocol groups combination for you to choose: [Click for Video Tutorial](https://youtu.be/xOQV_E1-C84)

<img width="869" height="602" alt="25d8af7b9b43d49d84ed84826600bebb" src="https://github.com/user-attachments/assets/739e4e86-8326-4c80-861d-5726c7f96481" />

------------------------------------------------------------------

* #### As shown below: Abandon third-party independent WARP scripts, xray+singbox dual-core integrated 15 kinds of WARP outbound combinations: [Click for Video Tutorial](https://youtu.be/iywjT8fIka4)

<img width="1015" height="681" alt="e0b66a115b1cd6a5060c38cae6e45c55" src="https://github.com/user-attachments/assets/06e69e8e-f714-4ba5-a519-f09fdecb0bbf" />

----------------------------------------------------------

## II. SSH One-Click Variable Script Template Description:

### Script runs in the form of ```Variable Name="Variable Value" Single or Multiple Combination + Main Script```

* Default Main Script curl: ```bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)```

* If curl not found error occurs, use Main Script wget: ```bash <(wget -qO- https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)```

* Mandatory Protocol Port Variables: ```vwpt=""```, ```vmpt=""```, ```vmpt="" argo="vmpt"```, ```vwpt="" argo="vwpt"```, ```vlpt=""```, ```xhpt=""```, ```anpt=""```, ```arpt=""```, ```hypt=""```, ```tupt=""```, ```sspt=""```, ```vxpt=""```, ```sopt=""```

* Optional Function Variables: ```warp=""```, ```uuid=""```, ```reym=""```, ```cdnym=""```, ```argo=""```, ```agn=""```, ```agk=""```, ```ippz=""```, ```name=""```, ```oap=""```

Please refer to ```I. Custom Variable Parameters Description``` for variable usage. Fill variable values inside ```" "```, separate variables with a space, delete unused variables.

-------------------------------------------------------------

* ### Template 1: Multiple Arbitrary Protocol Combination Run
```
sspt="" vlpt="" vmpt="" vwpt="" hypt="" tupt="" xhpt="" vxpt="" anpt="" arpt="" sopt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

* ### Template 2: Mainstream TCP or UDP Single Protocol Run

Vless-Tcp-Reality-vision Protocol Node
```
vlpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-Xhttp-Reality-vision-enc Protocol Node (Default Enable ENC Encryption)
```
xhpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-Xhttp-vision-enc Protocol Node (Default Enable ENC Encryption, IDX-Google-VPS container supported)
```
vxpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-ws-vision-enc Protocol Node (Default Enable ENC Encryption)
```
vwpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Shadowsocks-2022 Protocol Node
```
sspt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

AnyTLS Protocol Node
```
anpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Any-Reality Protocol Node
```
arpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vmess-ws Protocol Node
```
vmpt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Socks5 Protocol Node (Use with other app built-in proxies, do not use as direct node)
```
sopt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Hysteria2 Protocol Node
```
hypt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Tuic Protocol Node
```
tupt="" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

* ### Template 3: Run Nodes with CDN Optimization Enabled

Argo Temporary/Fixed Tunnel Running Optimized Node, recommended for IDX-Google-VPS containers without public network, quick one-click intranet penetration to get node

Vmess-ws-argo Temporary Tunnel CDN Optimized Node
```
vmpt="" argo="vmpt" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-ws-vision-enc-argo Temporary Tunnel CDN Optimized Node
```
vwpt="" argo="vwpt" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vmess-ws-argo Fixed Tunnel CDN Optimized Node, must fill port (vmpt), domain (agn), token (agk)
```
vmpt="CF set URL port" argo="vmpt" agn="Resolved CF domain" agk="Token from CF" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-ws-vision-enc-argo Fixed Tunnel CDN Optimized Node, must fill port (vwpt), domain (agn), token (agk)
```
vwpt="CF set URL port" argo="vwpt" agn="Resolved CF domain" agk="Token from CF" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vmess-ws 80 series port, origin port CDN Optimized Node
```
vmpt="80 series port, specified origin port" cdnym="CF resolved IP domain" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-Xhttp-vision-enc 80 series port, origin port CDN Optimized Node
```
vxpt="80 series port, specified origin port" cdnym="CF resolved IP domain" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

Vless-ws-vision-enc 80 series port, origin port CDN Optimized Node
```
vwpt="80 series port, specified origin port" cdnym="CF resolved IP domain" bash <(curl -Ls https://raw.githubusercontent.com/yonggekkk/argosbx/main/argosbx.sh)
```

* #### As shown below: Node IP, Port banned but still usable! CDN Optimization 5 Major Solutions 3-Step Video Tutorial:
  
[Video 1: 80 series + origin cdn](https://youtu.be/RnUT1CNbCr8)

[Video 2: Argo Temporary/Fixed Tunnel Difference & Settings](https://youtu.be/K35NhrNiLK8)

[Video 3: Black Tech 80 Port CDN](https://youtu.be/X8BFVyeiY9g)

<img width="1776" height="960" alt="f51af75fcc76bae7e76fe0ef5b9ecc86" src="https://github.com/user-attachments/assets/028b780d-bd48-4c79-8c60-940b3c3d1937" />

---------------------------------------------------------

## III. Multi-functional SSH Shortcut Command Groups

#### Note: After the first successful installation, you need to reconnect SSH for ```agsbx command``` shortcuts to take effect; if not effective, please use ```Main Script command``` shortcuts

1. Command to view Argo fixed domain, fixed tunnel token, temporary domain, currently installed node info: ```agsbx list``` or ```Main Script list```

2. Command to change, add, delete variable groups: ```Define various protocol variables agsbx rep``` or ```Define various protocol variables Main Script rep```

3. Command to update script: ```Previously installed various protocol variables Main Script rep``` 

4. Command to update Xray or Singbox core: agsbx upx or ups 【OR】 Main Script upx or ups

5. Command to restart script: ```agsbx res``` or ```Main Script res```

6. Command to uninstall script: ```agsbx del``` or ```Main Script del```

7. Temporary Switch IPV4/IPV6 Node Config (Dual-stack VPS Exclusive):

Show IPV4 node config: ```ippz=4 agsbx list``` or ```ippz=4 Main Script list```

Show IPV6 node config: ```ippz=6 agsbx list``` or ```ippz=6 Main Script list```

----------------------------------------------------------

#### Related tutorials can be found at [Yongge Blog](https://ygkkk.blogspot.com/2025/08/argosb.html), Video tutorials as follows:

Updating...

[ArgoSBX Lightweight Script Update Note: Added VLESS ENC Anti-Quantum Encryption; 80 Port Can Also Enable TLS Encryption? CDN Optimization Without Domain?](https://youtu.be/X8BFVyeiY9g)

[Argo Tunnel Proxy Node Ultimate Tutorial: VPS + Container Build Strongest CDN Node | Ignore Port IP Ban | Argo Temporary/Fixed Tunnel Difference | CDN Optimized IP Acceleration](https://youtu.be/K35NhrNiLK8)

[ArgoSBX One-Click Non-Interactive Lightweight Script 💣 (IV): One-Click SSH Command Generator Released, Just a Few Clicks, Major Proxy Protocols for You to Choose](https://youtu.be/4u6W4c-t3oU)

[ArgoSB One-Click Non-Interactive Lightweight Script 💣 (III): Built-in 15 Kinds of WARP Outbound Combinations, Easily Replace Independent WARP Scripts](https://youtu.be/iywjT8fIka4)

[ArgoSB One-Click Non-Interactive Lightweight Script 💣 (II): Proxy Node IP, Port Banned Still Usable! ArgoSB Script CDN Optimization 4 Major Solutions Tutorial](https://youtu.be/RnUT1CNbCr8)

[ArgoSB One-Click Non-Interactive Lightweight Script 💣 (I): VPS/nat VPS Application under Main Protocol; Just Press Enter Once, Multi-Protocol Free Combination](https://youtu.be/CiXmttY7mhw)

[Clawcloud, IDX Google VPS Gospel: Solve Server IP Access Troubles! Argosb Script Adds WARP Outbound Function, Easily Change Landing IP to Cloudflare WARP IP](https://youtu.be/HO_XLBmIYJw)

[Claw.cloud Free VPS Build Proxy Final Tutorial (V): ArgoSB Script Docker Image Update Supports AnyTLS, Xhttp-Reality](https://youtu.be/-mhZIhHRyno)

[Claw.cloud Free VPS Build Proxy Final Tutorial (IV): Lowest as 1 cent, 4 Price Sets + 7 Protocol Groups Combination for You to Choose; Operation Instructions for Viewing Nodes, Restarting Upgrade, Changing IP, Changing Config](https://youtu.be/xOQV_E1-C84)

[SAP Build Free Node One-Stop Tutorial: Multi-Platform Multi-Account Build + Keep Alive Done at Once, Supports Argo/workers/pags Multiple CDN Ways](https://youtu.be/NRYZNKWoLj8)

----------------------------------------------------------

### Communication Platform: [Yongge Blog Address](https://ygkkk.blogspot.com), [Yongge YouTube Channel](https://www.youtube.com/@ygkkk), [Yongge TG Telegram Group](https://t.me/+jZHc6-A-1QQ5ZGVl), [Yongge TG Telegram Channel](https://t.me/+DkC9ZZUgEFQzMTZl)

----------------------------------------------------------
### Thanks for support! WeChat Tip Yongge Kankankan ygkkk
![41440820a366deeb8109db5610313a1](https://github.com/user-attachments/assets/e5b1f2c0-bd2c-4b8f-8cda-034d3c8ef73f)

----------------------------------------------------------
### Thanks for your star 🌟 at the top right
[![Stargazers over time](https://starchart.cc/yonggekkk/ArgoSB.svg)](https://starchart.cc/yonggekkk/ArgoSB)

----------------------------------------------------------
### Declaration: All code comes from the integration of Github community and ChatGPT

### Thanks to [zmto/vtexs](https://console.zmto.com/?affid=1558) for the sponsorship support
