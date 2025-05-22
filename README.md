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
- And many more...

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
