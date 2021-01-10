# Encrypted DNS Party

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fencrypted-dns.party)](https://encrypted-dns.party)
[![Netlify Status](https://api.netlify.com/api/v1/badges/88d7577b-37b3-41e9-978b-2fb76375992a/deploy-status)](https://app.netlify.com/sites/mobileconfigs/deploys)
[![License](https://img.shields.io/badge/licensed-ethically-%234baaaa)](https://firstdonoharm.dev/)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/1?domain=https%3A%2F%2Fnitro.horse&style=social)](https://nitro.horse/@andreas)

https://encrypted-dns.party

Configuration files to easily set your Apple device to use encrypted DNS by your chosen provider systemwide.

## Install Instructions from [NextDNS' Profile Generator](https://apple.nextdns.io)

Install on iOS and iPadOS
1. Use Safari web browser for opening the `.mobileconfig` to recieve the install prompt.

Install on macOS
1. Open the downloaded `.mobileconfig` file.
2. Open System Preferences.
3. Go to Profiles.
4. Click Install.

Install on tvOS
1. Open the Settings app.
2. Go to General → Privacy.
3. Hover over "Share Apple TV Analytics" without pressing.
4. Press Play on the remote.
5. Select Add Profile.
6. Make the downloaded `.mobileconfig` file accessible publicly and enter its URL. You can use [TinyURL](https://tinyurl.com).
7. Install the profile following the onscreen instructions.

## Validate

You can use these online tools for validating your DNS resolver:
- https://browserleaks.com/dns
- https://dnsleaktest.com
- https://ipleak.net
- https://which.nameserve.rs

## Note

If you're not comfortable installing from the website, you can also install straight from GitLab.com by navigating to a profile (in Safari) within [/mobileconfig](https://gitlab.com/nitrohorse/ios14-encrypted-dns-mobileconfigs/-/tree/master/mobileconfig) and selecting "Open raw." For example, this is 42l's DoH profile from the repo:
- https://gitlab.com/nitrohorse/ios14-encrypted-dns-mobileconfigs/-/raw/master/mobileconfig/42l-doh.mobileconfig

Site based on the [john-doe template](https://github.com/cadars/john-doe/).

## Licenses

[DNS icon](https://icons8.com/icons/set/dns--v1) by [Icons8](https://icons8.com).
