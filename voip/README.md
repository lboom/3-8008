## Life without copper
----------------------
Unifinshed thoughts on augmenting our BBS plans with internet phones.

# Bulk providers
----------------
- [Voip.ms](https://voip.ms)
- [Callcentric](https://www.callcentric.com/)

Voip.ms
-------
- US DID numbers $4.25/month
- Lower 48: 0.0100/min
- Canada: 0.0052/min(mostly)
- Variable outbound DID allowed
- Incoming rate the same?

Callcentric
-----------
- Free DID (NY number only)
- Inbound 0.015/min USA + Canada
- Lower 48: 0.0198/min
- Canada: 0.0198/min
- No DID changing
- Bulk deals available

# Router
--------
You will want to use real firmware for your router to make your life easier when working with your ATA. I use [DD-WRT](https://dd-wrt.com/), but the 1337 among us probably prefer [OpenWrt](https://openwrt.org/). Either of these should work well for you.

# ATA
-----
We have choices here and as long as the device is not carrier locked(see also: Vonage) then it will probably work. I have primarily used Linksys(rebranded Sipura Technology) devices so my notes will be specific to those.

Linksys SPA-3102
----------------
- NAT settings can be variable. Will depend on router settings
- Turn off echo cancellation
- Set Network Jitter Level to 'High'
- Turn off Jitter Correction
- Use G.711 (u-law or a-law)
