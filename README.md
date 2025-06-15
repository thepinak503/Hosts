# Hosts

A curated collection of **publicly available hosts files** to **block ads**, **trackers**, **malware**, **phishing**, and other unwanted content. This repository aims to consolidate and provide easy access to high-quality blocklists from trusted sources for use with DNS-based blockers like Pi-hole, AdGuard Home, and similar tools.

---

## 📜 Description

This repository serves as a centralized list of **host files sourced from multiple public blocklists**. These lists can be used to block:
- 🛑 Ads
- 📦 Trackers
- 🐛 Malware domains
- 🎣 Phishing & scam sites
- 🔞 Adult content
- 🕹️ Gambling domains
- 🤳 Social media access
- And more...

Ideal for use in:
- **Pi-hole**
- **AdGuard Home**
- **Unbound**
- **dnsmasq**
- Any system-level DNS-based ad blocker

---

## 🌐 Source Lists

Some of the included sources:
- [StevenBlack/hosts](https://github.com/StevenBlack/hosts)
- [AdAway](https://adaway.org/)
- [GoodbyeAds](https://github.com/jerryn70/GoodbyeAds)
- [Energized Protection](https://energized.pro)
- [OISD Blocklist](https://oisd.nl/)
- [Phishing Army](https://phishing.army)
- [Blocklist Project](https://blocklistproject.github.io)
- [MVPS Hosts](https://winhelp2002.mvps.org/hosts.htm)
- [ntop Adblocker Hostnames](http://blacklists.ntop.org/adblocker-hostnames.txt)
- [ntop Blacklist Hostnames](http://blacklists.ntop.org/blacklist-hostnames.txt)
- [Denis Ovs Adblock](http://denis-ovs.narod.ru/adblock.txt)
- [Ayucat List](http://git.sourceforge.jp/view?p=ayucat-list/ayucat-list.git;a=blob_plain;f=ayucat-list.txt;hb=b254c74c132832a3ade7b9d42c2ef8d3dd59fdb9)
- [IPVerse CN IPv6](http://ipverse.net/ipblocks/data/countries/cn-ipv6.zone)
- [IPVerse CN](http://ipverse.net/ipblocks/data/countries/cn.zone)
- [Malware Domains Dynamic DNS](http://malwaredomains.lehigh.edu/files/dynamic_dns.txt)
- [Phishing Bad Sites](http://phishing.mailscanner.info/phishing.bad.sites.conf)
- [0xacab Porn Filters](https://0xacab.org/my-privacy-dns/matrix/-/raw/master/source/porn_filters/explicit_content/wildcard.list)
- [OISD.nl ABP](https://abp.oisd.nl/)
- [AdAway Hosts](https://adaway.org/hosts.txt)
- [Energized Adult Blocklist](https://block.energized.pro/assets/mirror/ut1-adult.txt)
- [EasyList](https://easylist.to/easylist/easylist.txt)
- [Fanboy Annoyance List](https://easylist-downloads.adblockplus.org/fanboy-annoyance.txt)
- [AdGuard SDNS Filter](https://raw.githubusercontent.com/AdguardTeam/AdGuardSDNSFilter/master/Filters/rules.txt)


> Full list of URLs is available in the configuration file inside the repo.

---

## 🛠 Usage

You can import these host files directly into your DNS-based blocker or system using the raw URLs. For example, with Pi-hole:

```bash
Settings > Adlists > Add URL
````

Then paste any of the raw URLs from this repository.

---

## 🧪 Compatibility

These hosts files are compatible with:

* ✅ Pi-hole
* ✅ AdGuard Home
* ✅ dnsmasq
* ✅ Router-level DNS resolvers
* ✅ Local `/etc/hosts` manipulation

---

## 📄 License

Each source retains its **own license**. This repository simply aggregates publicly available resources and does not claim ownership over any list.

---

## 🤝 Contributing

Have a list to add or suggest improvements?

1. Fork this repo
2. Add your list entry
3. Open a pull request

Please ensure sources are publicly accessible and regularly maintained.

---

## ⭐️ Support

If you find this repository helpful, consider starring it to help others discover it!
