# APT IRAN Research Center
-----------------------------------------------------------------
### 5 . The monopolistic line of the cafebazaar mafia to deal with Google Play under the pretext of self-sufficiency ( Related to Rubika ) 
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/cafebazaar1.jpg?raw=true)
##### As you know, Cafe Bazaar has become a source for spreading malware in Iran
##### It is not a myth to think that all the cafebazaar mafia or Rubika Gardan decide for us what to use!
##### In this created topic, we are trying to introduce a part of the dirty game of CafeBazaar.
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/cafebazaar2.png?raw=true)
#### In the picture above, you can see something called "Bazaar Security Shield".
#### The criterion for detecting malware in the cafebazaar is actually Google Play Protect itself !!
##### Now cafebazaar has arrogantly claimed something called "Bazaar Security Shield", which is not true, in fact Cafebazaar is using Google Play Protect.
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/Rubika1.png?raw=true)
#### As you can see in the photo above, after some time Google Play Protect detects Rubika as a malware.
##### Let's look at the matter a little more closely.
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/Rubika2.png?raw=true)
#### No warning will be received from Google Play Protect before opening Rubika.
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/Rubika3.png?raw=true)
#### Here, we make sure that Rubica has not received any access from the target device.
##### But in some cases, you see a warning to users on higher Androids and the latest version of Google Play.
##### In the previous years, an exploit was registered for Google Play Protect : shorturl.at/ceLM4 
##### With this exploit, the user was able to easily bypass Google Play's security shield
##### Decreasing and increasing the "TargetSdkVersion" entry on the target malware caused the malware to be ignored.
##### Neither Cafe Bazaar nor Google Play can be trusted because Cafe Bazaar itself uses Google Play's criteria to identify malware.


### 4 . Arvancloud Origin ip Disclosure ( Arvancloud is built to help hackers ! ) 

##### In this section, we will review Skyroom : 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/5-1-0.png?raw=true)

##### The IP is not revealed and we see Arvancloud 
##### But this is a ridiculous joke :-)

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/5-1-1.png?raw=true)

##### Mapping the domain ( Graph ) => 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/5-1-2.png?raw=true)

##### We see IPs that are exposed due to incorrect configuration !

##### Attackers get IPs after checking some values:
###### 1 . DNS Servers 
###### 2 . MX Records 
###### 3 . TXT Records 
###### 4 . Host (A) Records ( static database ) 
###### 5 . Domain Map

##### In the following, we take a look at some of the exposed IPs :
 
![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/5-1-3.png?raw=true)

##### More important risks are lurking in ASIATECH data center and Arvancloud

### 3 . Some important organizations and institutions of Iran are exposed to the vulnerability of CVE-2022-26134 ( OGNL injection Atlassian Confluence ) 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-4.jpg?raw=true)

##### Announcing the red status for:
<div dir="rtl">
"سازمان انرژی اتمی ایران" 
</div>


![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-5.jpg?raw=true)

<div dir="rtl">
"بانک مسکن | BANK MASKAN"
</div>
<div dir="rtl"> 
"بانک رفاه | BANK REFAH"
</div>
<div dir="rtl">
"همراه اول | hamrahe aval"
</div>
<div dir="rtl">
"شركت مديريت فناوري بورس تهران"
</div>
<div dir="rtl">
"توسن | TOSAN"
</div>
<div dir="rtl">
"ابرآروان  | ArvanCloud"
</div>
<div dir="rtl">
"بیمه کوثر | kins"
</div>
<div dir="rtl">
"بانک پاسارگاد | bpi"
</div>

##### A typical test Or POC : 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-6.png?raw=true)

### 2 .  Fact or lie? A superficial review of the latest attack on the National Bank server (mail.sadad.co.ir | mail.bmi.ir | mail.mail2.bmi.ir) 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-1.png?raw=true)

#### Engineer Hakimi from Sadad Collection :
<div dir="rtl">
"پاسخ مهندس حکیمی از مجموعه سداد در مورد حمله اخیر:
سلام به همه دوستان گرامی
پیرو فیلم منتشر شده کاربر 3ackd0or در Twitter در مورد ادعای نفوذ  به سیستم ایمیل شرکت سداد و بانک ملی، توضیحات زیر را عرض می‌کنم.
در فیلم منتشر شده، نشان داده می‌شود که اتصال به Exchange برقرار می‌شود و نسخه آن شناسایی می‌شود و بعد SID دومین و کاربر Administrator آن شناسایی می‌شود و براساس آن Token دریافت می‌شود و همه جا هم در اسکریپت اجرا شده پیام Successfully Parsed نشان داده می‌شود ولی همه موارد Fake است و واقعیت ندارد.
با وجود این که در فیلم مشخص است که اطلاعات واقعی نیست، ولی با توجه به شرایطی که در آن به سر می‌بریم باید هر احتمالی ولو ضعیف با دقت بررسی شود. لذا تمامی لایه‌های زیرساخت Exchange سداد (و دیگر سرویس‌های سازمانی) با دقت مورد بررسی قرار گرفت و مشخص شد اثری از نفوذ دیده نمی‌شود.
با بررسی انجام شده، مشخص است که این ادعا کاملا نادرست است.
در مورد دیگر ادعاهای این فرد و فیلم دیگری که در مورد سرویس شرکت دیگری منتشر کرده است نظری ندارم و در جایگاه تایید یا رد نیستم. حتما دیگر دوستان/شرکت‌ها و سازمان‌هایی که در مورد آن سرویس‌ها مسئولیت دارند می‌بایست نسبت به این ادعا و هر ادعای دیگری حساسیت داشته باشند و با دقت مورد بررسی قرار دهند.
با امید حفظ امنیت زیرساخت فناوری اطلاعات در کشور با سپاس-حکیمی"
</div>


##### And now everything has become clear with the investigations of the APT research center : 


###### mail.sadad.co.ir

###### mail.bmi.ir

###### mail.mail2.bmi.ir

##### vulnerability : 

###### Microsoft Exchange Deserialization RCE (CVE-2021-42321)

###### Microsoft Exchange ( CVE-2020-0688 )

###### EXCHANGE SHELL DROP POC ( CVE-2021–26855, CVE-2021–26857, CVE-2021–26858, CVE-2021–270658 )

###### Microsoft SharePoint Server CVE-2021-26420） 

###### Apache Root Privilege Escalation CVE-2019-0211

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-0.png?raw=true)

##### Security updates

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1.png?raw=true)

##### The interesting part is that these vulnerabilities still exist ! 

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-2.png?raw=true)

##### We can conclude that this attack is undeniable and it is better to consider these bugs

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/4-1-3.jpg?raw=true)

-----------------------------------------------------------------
### 1 . CVE-2022-26134 : Critical severity unauthenticated remote code execution vulnerability in Confluence Server and Data Center(0day) [CHANNEL POST](https://t.me/c/1448596903/204)

##### This vulnerability also existed in Iran☫ and you were unaware of it... ⚠

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/1-1.jpg?raw=true)

##### Many servers were affected by this vulnerability, despite reports of such cases, these vulnerabilities still exist !

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/2-2.jpg?raw=true)

##### The photo you see is only a part of this disaster... 
##### Universities, banks, call management center, refineries are only a small part of the story .

![alt text](https://github.com/APTIRAN/CENTER/blob/gh-pages/images/1-3.jpg?raw=true)
