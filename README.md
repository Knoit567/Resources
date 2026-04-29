# Resources
Use these resources and tools to make objectionable content less accessible and to aid in your recovery.  No one resource will suffice.

1. Cisco FamilyShield DNS

In my opinion, all home routers should be configured to use Cisco's FamilyShield DNS servers by default.  Any device connected to your wi-fi or ethernet will automatically use their list to only resolve website domain names for non adult sites. 

This has the advantage of being set-and-forget for any new or old devices in your home. Smart phones and TVs are more annoying to manually set back to an 'unsafe' DNS server than Windows.   
    
Unfortunately Cisco can lag behind blocking new sites and this is not hard to circumvent using cell data or VPN.

Set your router's DNS servers to 208.67.222.123 and 208.67.220.123 (check link in case they update).

https://www.cisco.com/c/en/us/support/docs/security/umbrella/225803-understand-opendns-familyshield.html

Screenshot for some Netgear devices.  
<img width="825" height="155" alt="image" src="https://github.com/user-attachments/assets/76c5d022-09c8-406d-8e52-0520f59e0cac" />

2. Leechblock

Use the Leechblock browser extension to block or time limit mindless short video sites like Facebook/Insta reels, Youtube shorts, X, and Tiktok.  If you use those sites for legitimate purposes, this prevents clicking a video and being stuck in a dopamine loop.  Facebook and Youtube insidiously ignore when you click their option to see fewer short videos or if something objectionalbe appears and you click to see less of it.
```
*facebook.com/reel*
*youtube.com/shorts/*
```
<img width="815" height="1113" alt="image" src="https://github.com/user-attachments/assets/c67e4f32-bda1-4710-a7c5-ace330c475ff" />
<img width="894" height="1106" alt="image" src="https://github.com/user-attachments/assets/468c8949-4117-4934-9a60-facdad261643" />

3. uBlock

   Use with leechblock to hide potentially harmful elements on pages if you have other legitimate uses for the site.
```
facebook.com##[aria-label="Reels"]
facebook.com##a[href*="/reel/"]
!facebook.com##div:has-text(Reels)
||facebook.com/reel/*
||facebook.com/reel/?*
||facebook.com/reel^
!facebook.com##body:has-text(/reel/i)
```
   <img width="548" height="532" alt="image" src="https://github.com/user-attachments/assets/302e9cd9-f455-44dc-aa0e-a019ea47eb7c" />  
  
4. Timer

Use a receptacle timer on your router.  Maybe start by having it turn off your router for a few hours when you know everyone will be asleep (2-5 AM) and increase over time.  I have found this to help avoid phone browsing before sleep and after waking up.  Great for improving sleep hygiene but this is obviously dependent on the lifestyle/schedule of everyone in the house.

https://www.amazon.com/Century-Indoor-24-Hour-Mechanical-Outlet/dp/B01LPT0IQA/ref=sr_1_6_pp

<img width="463" height="480" alt="image" src="https://github.com/user-attachments/assets/8fa5a4e5-ad52-4732-beae-e3fb26422995" />
 

  
5. Accountability software

There is no substitute for accountability software like Covenant Eyes' Victory.

https://www.covenanteyes.com/victory/

https://everaccountable.com/

6. 'Kosher' phone

   A flip phone or 'kosher' phone may be a necessary step if your phone is a temptation at your current stage of recovery.

   https://search.brave.com/search?q=kosher+phone&

4/27/2026
