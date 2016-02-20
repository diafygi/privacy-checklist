# Privacy Checklist

This is a general list of stuff you can use to increase your privacy based on
ease of use. You don't have to do everything on this list, but try to do at
least the easy stuff. Pull requests welcome!

* *Easy* - Easy setup and no maintenance
* *Medium* - Requires reading to setup and maintain
* *Hard* - Must understand how the underlying system works (lots of gotchas)

## Web Browsing
* Easy
    * [ ] Use [Firefox](https://www.mozilla.org/en-US/firefox/new/) or [Chrome](https://www.google.com/chrome/browser/desktop/) - Open source browsers and frequent security updates
    * [ ] HTTPS extension ([HTTPS Everywhere](https://www.eff.org/Https-everywhere)) - use encrypted connections whenever possible
    * [ ] Use a password manager ([KeePass](http://keepass.info/), [KeePassX](https://www.keepassx.org/), [LastPass](https://lastpass.com/), [1Password](https://agilebits.com/onepassword), etc.) - Always use generated passwords for websites and save those in a password manager! Also, use [diceware](https://www.dmuth.org/diceware/) to generate a password.
    * [ ] Anti-tracking extension ([Privacy Badger](https://www.eff.org/privacybadger), [uBlock](https://github.com/gorhill/uBlock#installation), etc.) - many tracking and malware attacks are distributed by ads and analytics trackers
    * [ ] Disable third party cookies ([Firefox](https://support.mozilla.org/en-US/kb/disable-third-party-cookies), [Chrome](https://support.google.com/chrome/answer/95647?hl=en)) - prevents embedded content from setting tracking cookies
    * [ ] Click to play flash ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/flashblock/), [Chrome](https://support.google.com/chrome/answer/142064?hl=en)) - prevent embedded flash from running unless you want it to
    * [ ] Enable Two-Factor-Authentication (2FA) ([tutorial](https://ssd.eff.org/en/module/how-enable-two-factor-authentication)) - enable 2FA on logins for websites that support it
* Medium
    * [ ] OpenVPN ([Windows](https://openvpn.net/index.php/open-source/downloads.html), [Mac](https://tunnelblick.net/), [Linux](https://www.linux.com/learn/tutorials/459675:configure-linux-clients-to-connect-to-openvpn-server)) - paid, faster obfuscation of browsing ([list of VPNs](https://torrentfreak.com/anonymous-vpn-service-provider-review-2015-150228/))
    * [ ] [Tor Browser](https://www.torproject.org/projects/torbrowser.html.en) - free, slower, safer obfuscation of browsing
* Hard
    * [ ] Reduce fingerprints ([tool](https://panopticlick.eff.org/)) - really hard to totally eliminate brower fingerprints

## Email
* Easy
    * None (private email is hard)
* Medium
    * None (private email is hard)
* Hard
    * [ ] PGP ([GnuPG](https://www.gnupg.org/), [Enigmail](https://www.enigmail.net/index.php/en/)) - message encryption and signatures

## Phone calls
* Easy
    * [ ] [Signal](https://whispersystems.org/) - end-to-end encrypted phone calls on iPhone and Android

## Texting/Chatting
* Easy
    * [ ] [Signal](https://whispersystems.org/) - end-to-end encrypted phone calls on iPhone and Android
* Easy (but not as safe as Signal)
    * [iMessage](https://www.apple.com/ios/messages/) - end-to-end encrypted texts, but proprietary code (only use if Signal doesn't work)
    * [WhatsApp](https://www.whatsapp.com/) - partial end-to-end encrypted texts, but proprietary code (only use if Signal doesn't work)
* Medium
    * [ ] Off-The-Record (OTR) - [Windows](https://ssd.eff.org/en/module/how-use-otr-windows), [Mac](https://ssd.eff.org/en/module/how-use-otr-mac), [Linux](https://ssd.eff.org/en/module/how-use-otr-linux), [iPhone](https://chatsecure.org/), [Android](https://chatsecure.org/)

## File Storage
* Easy
    * [ ] Enable encryption ([iPhone](https://ssd.eff.org/en/module/how-encrypt-your-iphone), [Android](http://www.howtogeek.com/141953/how-to-encrypt-your-android-phone-and-why-you-might-want-to/), [Mac](https://support.apple.com/en-us/HT204837))
* Medium
    * [ ] Encrypted cloud backups ([SpiderOak](https://spideroak.com/)) - paid and proprietary, but easier than running your own server
* Hard
    * [ ] Windows and Linux encryption ([Windows](https://ssd.eff.org/en/module/how-encrypt-your-windows-device), [Linux](https://wiki.archlinux.org/index.php/disk_encryption))
    * [ ] PGP ([GnuPG](https://www.gnupg.org/)) - for specific file encryption on USB drive, external device, etc.

# Further Reading
* [ ] [Surveillance Self-Defense](https://ssd.eff.org/)

