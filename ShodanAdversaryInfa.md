## Adversary Infrastructure on Shodan

#### `Metasploit C2`
- http.favicon.hash:-127886975
- ssl:MetasploitSelfSignedCA
- http.html:"msf4"

#### `Cobalt Strike C2`
- ssl.jarm:07d14d16d21d21d07c42d41d00041d24a458a375eef0c576d23a7bab9a9fb1+port:443
- ssl.cert.serial:146473198
- product:"Cobalt Strike Beacon"
- http.html:"cs4.4"

#### `Covenant C2`
- http.favicon.hash:-737603591
- ssl:Covenant http.component:Blazor

#### `Sliver C2`
- http.html:"sliver-client"
- ssl.cert.issuer.cn:"operators" ssl.cert.subject.cn:"multiplayer"
- product:"Sliver C2"
- "HTTP/1.1 404 Not Found" "Cache-Control: no-store, no-cache, must-revalidate" "Content-Length: 0" -"Server:" -"Pragma:"

#### `Mythic C2`
- ssl:Mythic port:7443
- http.favicon.hash:-859291042

#### `PoshC2`
- ssl:P18055077

#### `Brute Ratel C4`
- http.html_hash:-1957161625
- product:"Brute Ratel C4"

#### `Deimos C2`
- http.html_hash:-14029177

#### `PANDA C2`
- http.html:"PANDA" http.html:"layui"

#### `AcridRain Stealer`
- http.html:"AcridRain Stealer"

#### `Grand Misha (aka Misha Stealer)`
- http.title:"misha" http.component:"UIKit"

#### `Patriot Stealer`
- http.favicon.hash:274603478
- http.html:"patriotstealer"

#### `RAXNET Bitcoin Stealer`
- http.favicon.hash:-1236243965

#### `Titan Stealer`
- http.html:"Titan Stealer"

#### `Hashcat cracking tool`
- http.html:"hashcat"

#### `Collector Stealer`
- http.html:"Collector Stealer"
- http.html:"getmineteam"

#### `BurpSuite pentesting tool`
- http.html:"BurpSuite"

#### `Mystic Stealer`
- http.html:"Mystic Stealer"

#### `PowerSploit Windows PowerShell Exploitation`
- http.html:"PowerSploit"

#### `XMRig Monero Cryptominer`
- http.html:"XMRig"
- http.favicon.hash:-782317534
- http.favicon.hash:1088998712

#### `Uname Web Panel`
- http.title:"Unam Web Panel"

#### `ShadowSyndicate`
- `1c:a4:cb:ac:89:5f:c3:bd:12:41:7b:77:fc:6e:d3:1d`
- `55:c6:58:70:3c:07:d6:34:4e:32:5e:a2:6c:f9:6c:3b`
- `dd:d9:ca:54:c1:30:9c:de:57:80:62:cb:a9:65:57:1e`
- Source: [here](https://www.group-ib.com/blog/new-shadowsyndicate-infrastructure/)
