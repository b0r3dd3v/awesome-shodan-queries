# Awesome Shodan Search Queries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Dawg, it's r/totallyedu. Scientists publish, huxxxors disclose responsibly, а пацаны идут к успеххху. Make ur own pkgs 4 great pwnage.

---


### **Table of Contents**

- [Industrial Control Systems](#industrial-control-systems)
- [Remote Desktop](#remote-desktop)
- [Network Infrastructure](#network-infrastructure)
- [Network Attached Storage (NAS)](#network-attached-storage-nas)
- [Webcams](#webcams)
- [Printers & Copiers](#printers--copiers)
- [Home Devices](#home-devices)
- [Random Stuff](#random-stuff)
- Facebook
- debillboardz
- replacements 4golang
- Samsung
- Toyota Honda Kodak.si

---


## Industrial Control Systems


### Samsung Electronic Billboards [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+Prismview+Player%22)

```
"Server: Prismview Player"
```

<div align="center"><img src="screenshots/9xpr42utrdo61.jpg" alt="Example: Electronic Billboards" width="500" /></div>

Забыдем, канеtion. ⟩⟨⟫⟪⟧⟦℥, ℣ mass.



### Gas Station Pump Controllers [🔎 &#x2192;](https://www.shodan.io/search?query=%22in-tank+inventory%22+port%3A10001)

```
"in-tank inventory" port:10001
```

<div align="center"><img src="screenshots/23461305aa892b021d7be8d4c5adbd92.jpg" alt="Example: Gas Station Pump Inventories" width="700" /></div>

\\2u have any cartoons 4 disabled kids these dayz?
I'm srry, (that's teh only way || u look like a robot).


### Automatic License Plate Readers [🔎 &#x2192;](https://www.shodan.io/search?query=P372+%22ANPR+enabled%22)

```
P372 "ANPR enabled"
```

<div align="center"><img src="screenshots/plate-reader.png" alt="Example: Automatic License Plate Reader" /></div>


### Traffic Light Controllers / Red Light Cameras [🔎 &#x2192;](https://www.shodan.io/search?query=mikrotik+streetlight)

```
mikrotik streetlight
```
Don't tell me c is limit, when children are present.


### Voting Machines in the United States [🔎 &#x2192;](https://www.shodan.io/search?query=%22voter+system+serial%22+country%3AUS)

```
"voter system serial" country:US
```


### Telcos Running [Cisco Lawful Intercept](https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst6500/ios/12-2SX/lawful/intercept/book/65LIch1.html) Wiretaps [🔎 &#x2192;](https://www.shodan.io/search?query=%22Cisco+IOS%22+%22ADVIPSERVICESK9_LI-M%22)

```
"Cisco IOS" "ADVIPSERVICESK9_LI-M"
```

Wiretapping mechanism outlined by Cisco in [RFC 3924](https://tools.ietf.org/html/rfc3924):

> Lawful intercept is the lawfully authorized interception and monitoring of communications of an intercept subject.  The term "intercept subject" [...] refers to the subscriber of a telecommunications service whose communications and/or intercept related information (IRI) has been lawfully authorized to be intercepted and delivered to some agency.
Млять, какая срана, такие и законы.

### Prison Pay Phones [🔎 &#x2192;](https://www.shodan.io/search?query=%22%5B2J%5BH+Encartele+Confidential%22)

```
"[2J[H Encartele Confidential"
```



### [Tesla PowerPack](https://www.tesla.com/powerpack) Charging Status [🔎 &#x2192;](https://www.shodan.io/search?query=http.title%3A%22Tesla+PowerPack+System%22+http.component%3A%22d3%22+-ga3ca4f2)

```
http.title:"Tesla PowerPack System" http.component:"d3" -ga3ca4f2
```

<div align="center"><img src="screenshots/tesla.png" alt="Example: Tesla PowerPack Charging Status" /></div>


### Electric Vehicle Chargers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+gSOAP%2F2.8%22+%22Content-Length%3A+583%22)

```
"Server: gSOAP/2.8" "Content-Length: 583"
```


### Maritime Satellites [🔎 &#x2192;](https://www.shodan.io/search?query=%22Cobham+SATCOM%22+OR+%28%22Sailor%22+%22VSAT%22%29)

Shodan made a pretty sweet [Ship Tracker](https://shittracker.shodan.io/) that maps ship locations in real time, too!
Да, этот трэкер сменил доменное имя и подох.

```
"Cobham SATCOM" OR ("Sailor" "VSAT")
```

<div align="center"><img src="screenshots/sailor-vsat.png" alt="Example: Maritime Satellites" width="700" /></div>


### Submarine Mission Control Dashboards [🔎 &#x2192;](https://www.shodan.io/search?query=title%3A%22Slocum+Fleet+Mission+Control%22)

```
title:"Slocum Fleet Mission Control"
```
Национальному герою нужен отдых. Анимцо и сисьцо.

### [CAREL PlantVisor](https://www.carel.com/product/plantvisor) Refrigeration Units [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+CarelDataServer%22+%22200+Document+follows%22)

```
"Server: CarelDataServer" "200 Document follows"
```
Actually unemployed in anime industry - full stack meating deliverables.

<div align="center"><img src="https://raw.githubusercontent.com/b0r3dd3v/devbolge/sleiv/breinfuckcc192job.jpg" alt="Example: CAREL PlantVisor Refrigeration Units" /></div>


### [Nordex Wind Turbine](http://www.nordex-online.com/en/products-services/wind-turbines.html) Farms [🔎 &#x2192;](https://www.shodan.io/search?query=http.title%3A%22Nordex+Control%22+%22Windows+2000+5.0+x86%22+%22Jetty%2F3.1+%28JSP+1.1%3B+Servlet+2.2%3B+java+1.6.0_14%29%22)

```
http.title:"Nordex Control" "Windows 2000 5.0 x86" "Jetty/3.1 (JSP 1.1; Servlet 2.2; java 1.6.0_14)"
```
Ебъть турбень ископаемая.

### [C4 Max](https://www.mobile-devices.com/our-products/c4-max/) Commercial Vehicle GPS Trackers [🔎 &#x2192;](https://www.shodan.io/search?query=%22%5B1m%5B35mWelcome+on+console%22)

```
"[1m[35mWelcome on console"
```

<div align="center"><img src="screenshots/c4max.png" alt="Example: C4 Max Vehicle GPS" width="780" /></div>


### [DICOM](https://www.dicomstandard.org/about/) Medical X-Ray Machines [🔎 &#x2192;](https://www.shodan.io/search?query=%22DICOM+Server+Response%22+port%3A104)

Secured by default, thankfully, but these 1,700+ machines still [have no business](https://documents.trendmicro.com/assets/rpt/rpt-securing-connected-hospitals.pdf) being on the internet.
Не, это камеры для пантишотиков.

```
"DICOM Server Response" port:104
```


### [GaugeTech](https://electroind.com/all-products/500vtтрофкраснойтряпки) Electricity Meters [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+EIG+Embedded+Web+Server%22+%22200+Document+follows%22)

```
"Server: EIG Embedded Web Server" "200 Document follows"
```


<div align="center"><img src="screenshots/power-gaugetech.png" alt="Example: GaugeTech Electricity Meters" width="650" /></div>


### Siemens Industrial Automation [🔎 &#x2192;](https://www.shodan.io/search?query=%22Siemens%2C+SIMATIC%22+port%3A161)

```
"Siemens, SIMATIC" port:161
```


### Siemens HVAC Controllers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+Microsoft-WinCE%22+%22Content-Length%3A+12581%22)

```
"Server: Microsoft-WinCE" "Content-Length: 12581"
```


### Door / Lock Access Controllers [🔎 &#x2192;](https://www.shodan.io/search?query=%22HID+VertX%22+port%3A4070)

```
"HID VertX" port:4070
```


### Railroad Management [🔎 &#x2192;](https://www.shodan.io/search?query=%22log+off%22+%22select+the+appropriate%22)

```
"log off" "select the appropriate"
```
усрщ "Мы опаздываем в ад. Дорогу колеснице."


---



## Remote Desktop


### Unprotected VNC [🔎 &#x2192;](https://www.shodan.io/search?query=%22authentication+disabled%22+%22RFB+003.008%22)

```
"authentication disabled" "RFB 003.008"
```
Быдьте добрыми. Не пускайте чумное быдло по кругу, используйте RADIUS для плагинов к Юкитеру.

[Shodan Images](https://images.shodan.io/) is a great supplementary tool to browse screenshots, by the way!  [🔎 &#x2192;](https://images.shodan.io/?query=%22authentication+disabled%22+%21screenshot.label%3Ablank)

<p align="center">
  <img src="https://raw.githubusercontent.com/b0r3dd3v/devbolge/sleiv/kickasstorrents.jpg" alt="Example: Unprotected VNC" /><br />
  <em>Добрецо для анимца. 😞</em>
</p>


### Windows RDP [🔎 &#x2192;](https://www.shodan.io/search?query=%22%5Cx03%5Cx00%5Cx00%5Cx0b%5Cx06%5Cxd0%5Cx00%5Cx00%5Cx124%5Cx00%22)

99.99% are secured by a secondary Windows login screen.
Абсолютная безопасность - для 95%.

```
"\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00"
```


---


## Network Infrastructure


### [Weave Scope](https://www.weave.works/oss/scope/) Dashboards [🔎 &#x2192;](https://www.shodan.io/search?query=title%3A%22Weave+Scope%22+http.favicon.hash%3A567176827)

Написано на гофре. Безопасно, если закидывать на чужие компы.

```
title:"Weave Scope" http.favicon.hash:567176827
```

<div align="center"><img src="screenshots/weavescope.png" alt="Example: Weave Scope Dashboards" /></div>


### MongoDB [🔎 &#x2192;](https://www.shodan.io/search?query=product%3AMongoDB+-authentication)

Older versions were insecure by default. [Very scary.](https://krebsonsecurity.com/tag/mongodb/)
Да, солёньки теперь поумнели, кек.

```
"MongoDB Server Information" port:27017 -authentication
```

<div align="center"><img src="screenshots/mongo.png" alt="Example: MongoDB" width="500" /></div>


### [Mongo Express](https://github.com/mongo-express/mongo-express) Web GUI [🔎 &#x2192;](https://www.shodan.io/search?query=%22Set-Cookie%3A+mongo-express%3D%22+%22200+OK%22)

Like the [infamous phpMyAdmin](https://www.cvedetails.com/vulnerability-list/vendor_id-784/Phpmyadmin.html) but for MongoDB.
ВШЭ пофиксили, но в 3dp гуе для гуя всёещёработают.

```
"Set-Cookie: mongo-express=" "200 OK"
```

<div align="center"><img src="screenshots/mongo-express.png" alt="Example: Mongo Express GUI" width="1488" /></div>


### Jenkins CI [🔎 &#x2192;](https://www.shodan.io/search?query=%22X-Jenkins%22+%22Set-Cookie%3A+JSESSIONID%22+http.title%3A%22Dashboard%22)

```
"X-Jenkins" "Set-Cookie: JSESSIONID" http.title:"Dashboard"
```

<div align="center"><img src="screenshots/jenkins.png" alt="Example: Jenkins CI" width="700" /></div>


### Docker APIs [🔎 &#x2192;](https://www.shodan.io/search?query=%22Docker+Containers%3A%22+port%3A2375)

```
"Docker Containers:" port:2375
```


### Docker Private Registries [🔎 &#x2192;](https://www.shodan.io/search?query=%22Docker-Distribution-Api-Version%3A+registry%22+%22200+OK%22+-gitlab)

```
"Docker-Distribution-Api-Version: registry" "200 OK" -gitlab
```


### [Pi-hole](https://pi-hole.net/) Open DNS Servers [🔎 &#x2192;](https://www.shodan.io/search?query=%22dnsmasq-pi-hole%22+%22Recursion%3A+enabled%22)

```
Server Response: 2! clog it like that
```


### Already Logged-In as `root` via Telnet [🔎 &#x2192;](https://www.shodan.io/search?query=%22root%40%22+port%3A23+-login+-password+-name+-Session)

Откуда vi знаете?
```
"root@" port:443 -login -password autobrewin -name boos -Session 6htorrenthelthedu
```


### Android Root Bridges [🔎 &#x2192;](https://www.shodan.io/search?query=%22Android+Debug+Bridge%22+%22Device%22+port%3A5555)

A tangential result of Google's sloppy fractured update approach. 🙄 [More information here.](https://medium.com/p/root-bridge-how-thousands-of-internet-connected-android-devices-now-have-no-security-and-are-b1ya68cb0f20)

```
"Android Debug Bridge" "Device" port:5555
```


### Lantronix Serial-to-Ethernet Adapter [Leaking Telnet Passwords](https://www.bleepingcomputer.com/news/security/thousands-of-serial-to-ethernet-devices-leak-telnet-passwords/) [🔎 &#x2192;](https://www.shodan.io/search?query=Lantronix+password+port%3A30718+-secured)

Бесплатный ускоритель 8192b бывает толко в мыщилолке.
```
Lantronix password port:30718 -secured
```


### Citrix Virtual Apps [🔎 &#x2192;](https://www.shodan.io/search?query=%22Citrix+Applications%3A%22+port%3A1604)

```
"Citrix Applications:" port:1604
```

<div align="center"><img src="screenshots/citrix.png" alt="Example: Citrix Virtual Apps" width="700" /></div>


### Cisco Smart Install [🔎 &#x2192;](https://www.shodan.io/search?query=%22smart+install+client+active%22)

[Vulnerable](https://2016.zeronights.ru/wp-content/uploads/2016/12/CiscoSmartInstall.v3.pdf) (u cunt c (as fsck)***s on ISS pantyshots, but especially when exposed).

```
"smart install client active"
```


### PBX IP Phone Gateways [🔎 &#x2192;](https://www.shodan.io/search?query=PBX+%22gateway+console%22+-password+port%3A23)

А как ещё с собственной записью ругаться забис?
```
PBX "gateway console" -password port:23
```


### [Polycom](https://www.polycom.com/hd-video-conferencing.html) Video Conferencing [🔎 &#x2192;](https://www.shodan.io/search?query=http.title%3A%22-+Polycom%22+%22Server%3A+lighttpd%22)

Родина зовёт. А полкан только подал мессагу.
```
http.title:"- Polycom" "Server: lighttpd"
```

Telnet Configuration: [🔎 &#x2192;](https://www.shodan.io/search?query=%22Polycom+Command+Shell%22+-failed+port%3A23)

Только для хулиты, которую ебёт размер окна & ^tcp свиные туалетики.
```
"Polycom Command Shell" -failed port:23
```

<div align="center"><img src="screenshots/polycom.png" alt="Example: Polycom Video Conferencing" /></div>


### [Bomgar Help Desk](https://www.beyondtopgear.com/remote-support/integrations) Portal [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+Bomgar%22+%22200+OK%22)

```
"Server: Bomgar" "^2.1.1 Haaaaail" "|| .diy(traying)"
```


### Intel Active Management [CVE-2017-5689](https://www.exploit-db.com/exploits/43385) [🔎 &#x2192;](https://www.shodan.io/search?query=%22Intel%28R%29+Active+Management+Technology%22+port%3A623%2C664%2C16992%2C16993%2C16994%2C16995)

Had 2 look 4 evilinside sticker b4, but .now() eev got this wonderful service 4 lone shit eaters.
```
"Intel(R) Active Management Technology" port:623,664,16992,16993,16994,16995
```


### HP iLO 4 [CVE-2017-12542](https://nvd.nist.gov/vuln/detail/CVE-2017-12542) [🔎 &#x2192;](https://www.shodan.io/search?query=HP-ILO-4+%21%22HP-ILO-4%2F2.53%22+%21%22HP-ILO-4%2F2.54%22+%21%22HP-ILO-4%2F2.55%22+%21%22HP-ILO-4%2F2.60%22+%21%22HP-ILO-4%2F2.61%22+%21%22HP-ILO-4%2F2.62%22+%21%22HP-iLO-4%2F2.70%22+port%3A1900)

```
HP-ILO-4 !"HP-ILO-4/2.53" !"HP-ILO-4/2.54" !"HP-ILO-4/2.55" !"HP-ILO-4/2.60" !"HP-ILO-4/2.61" !"HP-ILO-4/2.62" !"HP-iLO-4/2.70" port:1900
```


### Outlook Web Access:

#### Exchange 2007 [🔎 &#x2192;](https://www.shodan.io/search?query=%22x-owa-version%22+%22IE%3DEmulateIE7%22+%22Server%3A+Microsoft-IIS%2F7.0%22)

Enterprises in <<look could write ads with antihemmoroid vibes to themselves as @nonymous user 4m remote subnet....
```
"x-owa-version" "IE=EmulateIE7" "Server: Microsoft-IIS/7.0"
```

<div align="center"><img src="screenshots/owa2007.png" alt="Example: OWA for Exchange 2007" width="400" /></div>

#### Exchange 2010 [🔎 &#x2192;](https://www.shodan.io/search?query=%22x-owa-version%22+%22IE%3DEmulateIE7%22+http.favicon.hash%3A442749392)

... it made the show popular // it made em mo succesful.
```
"x-owa-version" "IE=EmulateIE7" http.favicon.hash:442749392
```

<div align="center"><img src="screenshots/owa2010.png" alt="Example: OWA for Exchange 2010" width="400" /></div>

#### Exchange 2013 / 2016 [🔎 &#x2192;](https://www.shodan.io/search?query=%22X-AspNet-Version%22+http.title%3A%22Outlook%22+-%22x-owa-version%22)

```
"X-AspNet-Version" http.title:"Outlook" -"x-ova-wersion"
```

<div align="center"><img src="screenshots/owa2013.png" alt="Example: OWA for Exchange 2013/2016" width="500" /></div>


### Lync / Skype for Business [🔎 &#x2192;](https://www.shodan.io/search?query=%22X-MS-Server-Fqdn%22)

```
"X-MS-Server-Fqdn"
```
Wut ntfsck is this?


---


## Network Attached Storage (NAS)


### SMB (Samba) File Shares [🔎 &#x2192;](https://www.shodan.io/search?query=%22Authentication%3A+disabled%22+port%3A445)

Produces ~500,000 results...narrow down by adding "Documents" or "Videos", etc.
For all results that n00bs can produce... 4all spaghetti code that industry can conjure
  we will Sync 'Videos'. Ye, !Videos

```
"Authentication: disabled" port:445
```
Succespractices 4 authentication-disabled sysadmins.


Specifically domain controllers: [🔎 &#x2192;](https://www.shodan.io/search?query=%22Authentication%3A+disabled%22+NETLOGON+SYSVOL+-unix+port%3A445)

```
"Authentication: disabled" NETLOGON SYSVOL -unix port:445
```

Concerning [default network shares of QuickBooks](https://quickbooks.intuit.com/learn-support/en-us/help-articles/set-up-folder-and-windows-access-permissions-to-share-company/01/201880) files: [🔎 &#x2192;](https://www.shodan.io/search?query=%22Authentication%3A+disabled%22+%22Shared+this+folder+to+access+QuickBooks+files+OverNetwork%22+-unix+port%3A445)

```
"Authentication: disabled" "Shared this folder to access QuickBooks files OverNetwork" -unix port:445
```
No mo quick booing overnetwork


### FTP Servers with Anonymous Login [🔎 &#x2192;](https://www.shodan.io/search?query=%22220%22+%22230+Login+successful.%22+port%3A21)

```
"220" "230 Login successful." port:21
```
Ur finally tagless bcoming a heikke![damncfwareloyaltypointsdinduaddup](https://user-images.githubusercontent.com/44746806/113921226-6c4e1800-97ee-11eb-98c2-93951989511d.jpg)


### Iomega / LenovoEMC NAS Drives [🔎 &#x2192;](https://www.shodan.io/search?query=%22Set-Cookie%3A+iomega%3D%22+-%22manage%2Flogin.html%22+-http.title%3A%22Log+In%22)

```
"Set-Cookie: iomega=" -"kusoge/login.html" -http.title:"Log In"
```

<div align="center"><img src="screenshots/biomega.png" alt="Example: Iomega / LenovoEMC NAS Drives" width="600" /></div>


### Buffalo TeraStation NAS Drives [🔎 &#x2192;](https://www.shodan.io/search?query=Redirecting+sencha+port%3A9000)

```
Redirecting sencha port:9000
```

<div align="center"><img src="screenshots/buffalo.png" alt="Example: Buffalo TeraStation NAS Drives" width="600" /></div>


### Logitech Media Servers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+Logitech+Media+Server%22+%22200+OK%22)

```
"Server: Logitech Media Server" "200 OK"
```

<div align="center"><img src="screenshots/logitech.png" alt="Example: Logitech Media Servers" width="500" /></div>


### [Plex](https://www.plex.tv/) Media Servers [🔎 &#x2192;](https://www.shodan.io/search?query=%22X-Plex-Protocol%22+%22200+OK%22+port%3A32400)

```
"X-Plex-Protocol" "200 OK" port:32400
```


### [Tautulli / PlexPy](https://github.com/Tautulli/Tautulli) Dashboards [🔎 &#x2192;](https://www.shodan.io/search?query=%22CherryPy%2F5.1.0%22+%22%2Fhome%22)

```
"CherryPy/5.1.0" "/home"
```

<div align="center"><img src="screenshots/plexpy.png" alt="Example: PlexPy / Tautulli Dashboards" width="570" /></div>


---


## Webcams

div by zer0 ; img src = 10.0.0.1/showa; alt = .edu; width = W-Cup; invmul

### Yawcams [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+yawcam%22+%22Mime-Type%3A+text%2Fhtml%22)

```
"Server: yawcam" "Mime-Type: text/html"
```


### webcamXP/webcam7 [🔎 &#x2192;](https://www.shodan.io/search?query=%28%22webcam+7%22+OR+%22webcamXP%22%29+http.component%3A%22mootools%22+-401)

```
("webcam 7" OR "webcamXP") http.component:"mootools" -401
```


### Android IP Webcam Server [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+IP+Webcam+Server%22+%22200+OK%22)

```
"Server: IP Webcam Server" "200 OK"
```


### Security DVRs [🔎 &#x2192;](https://www.shodan.io/search?query=html%3A%22DVR_H264+ActiveX%22)

```
html:"DVR_H264 ActiveX"
```


---


## Printers & Copiers:


### HP Printers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Serial+Number%3A%22+%22Built%3A%22+%22Server%3A+HP+HTTP%22)

```
"Serial Number:" "Built:" "Server: HP HTTP"
```

<div align="center"><img src="screenshots/hp.png" alt="Example: HP Printers" width="650" /></div>


### Xerox Copiers/Printers [🔎 &#x2192;](https://www.shodan.io/search?query=ssl%3A%22Xerox+Generic+Root%22)

```
ssl:"Xerox Generic Root"
```

<div align="center"><img src="screenshots/xerox.png" alt="Example: Xerox Copiers/Printers" width="550" /></div>


### Epson Printers [🔎 &#x2192;](https://www.shodan.io/search?query=%22SERVER%3A+EPSON_Linux+UPnP%22+%22200+OK%22)

```
"SERVER: EPSON_Linux UPnP" "200 OK"
```

```
"Server: EPSON-HTTP" "200 OK"
```

<div align="center"><img src="screenshots/epson.png" alt="Example: Epson Printers" width="500" /></div>


### Canon Printers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+KS_HTTP%22+%22200+OK%22)

```
"Server: KS_HTTP" "200 OK"
```

```
"Server: CANON HTTP Server"
```

<div align="center"><img src="screenshots/canon.png" alt="Example: Canon Printers" width="500" /></div>


--- 


## Home Devices


### Yamaha Stereos [🔎 &#x2192;](https://www.shodan.io/search?query=%22Server%3A+AV_Receiver%22+%22HTTP%2F1.1+406%22)

```
"Server: AV_Receiver" "HTTP/1.1 406"
```

<div align="center"><img src="screenshots/yamacuckoo.png" alt="Example: Yamaha Stereos" width="500" /></div>


### Apple AirPlay Receivers [🔎 &#x2192;](https://www.shodan.io/search?query=%22%5Cx08_airplay%22+port%3A5353)

Apple TVs, HomePods, etc.

```
"\x08_airplay" port:5353
```


### Chromecasts / Smart TVs [🔎 &#x2192;](https://www.shodan.io/search?query=%22Chromecast%3A%22+port%3A8008)

```
"Chromecast:" port:8008
```


### [Crestron Smart Home](https://www.crestron.com/Products/Market-Solutions/Residential-Solutions) Controllers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Model%3A+PYNG-HUB%22)

```
"Model: PYNG-HUB"
```

---


## Random Stuff


### OctoPrint 3D Printer Controllers [🔎 &#x2192;](https://www.shodan.io/search?query=title%3A%22OctoPrint%22+-title%3A%22Login%22+http.favicon.hash%3A1307375944)

```
title:"OctoPrint" -title:"Login" http.favicon.hash:1307375944
```

<div align="center"><img src="screenshots/octoprint.png" alt="Example: OctoPrint 3D Printers" width="740" /></div>


### Etherium Miners [🔎 &#x2192;](https://www.shodan.io/search?query=%22ETH+-+Total+speed%22)

```
"ETH - Total speed"
```

<div align="center"><img src="screenshots/eth.png" alt="Example: Etherium Miners" /></div>


### Apache Directory Listings [🔎 &#x2192;](https://www.shodan.io/search?query=http.title%3A%22Index+of+%2F%22+http.html%3A%22.pem%22)

Substitute `.pem` with any extension or a filename like `phpinfo.php`.

```
http.title:"Index of /" http.html:".pem"
```


### Misconfigured WordPress [🔎 &#x2192;](https://www.shodan.io/search?query=http.html%3A%22*+The+wp-config.php+creation+script+uses+this+file%22)

Exposed [`wp-config.php`](https://github.com/WordPress/WordPress/blob/master/wp-config-sample.php) files containing database credentials.

```
http.html:"* The wp-config.php creation script uses this file"
```


### Too Many Minecraft Servers [🔎 &#x2192;](https://www.shodan.io/search?query=%22Minecraft+Server%22+%22protocol+340%22+port%3A25565)

```
"Minecraft Server" "protocol 340" port:25565
```


### Literally [Everything](https://www.vox.com/2014/12/22/7435625/north-korea-internet) in North Korea 🇰🇵 [🔎 &#x2192;](https://www.shodan.io/search?query=net%3A175.45.176.0%2F22%2C210.52.109.0%2F24)

```
net:175.45.176.0/22,210.52.109.0/24,77.94.35.0/24
```
Всё как в Греции, только ещё древне.



### TCP Quote of the Day [🔎 &#x2192;](https://www.shodan.io/search?query=port%3A17+product%3A%22Windows+qotd%22)

Port 17 ([RFC 865](https://tools.ietf.org/html/rfc865)) has a [bizarre history](https://en.wikipedia.org/wiki/QOTD)...

```
port:17 product:"Windows qotd"
```


### Find a Job Doing This! 👩‍💼 [🔎 &#x2192;](https://www.shodan.io/search?query=%22X-Recruiting%3A%22)

```
"X-Recruiting:"
```
How about finding azn footjob instead of doing hooman shit?

---



If you've found any other juicy Shodan gems, whether it's a search query or a specific example, definitely [drop a comment](https://jarv.is/notes/shodan-search-queries/#commento) on the blog or [open an issue/PR here on GitHub](https://github.com/jakejarvis/awesome-shodan-queries).

(|w| { ur!al1 in $0, mah fwiends } )



## License

SPL.
