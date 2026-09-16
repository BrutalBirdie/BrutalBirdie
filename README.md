<!--
  ╔═══════════════════════════════════════════════════════════════════╗
  ║  Oh. You opened the raw markdown.                                 ║
  ║                                                                   ║
  ║  🥚 ACHIEVEMENT UNLOCKED: "View Source"             [ egg 1 / 5 ]  ║
  ║                                                                   ║
  ║  There are four more hidden in this file. Some are in the         ║
  ║  rendered page, some only live down here in the dark.             ║
  ║  Good luck. Bring a lamp. -- BB                                   ║
  ╚═══════════════════════════════════════════════════════════════════╝
-->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=190&section=header&text=BrutalBirdie&fontColor=ffffff&fontSize=62&fontAlignY=36&desc=Elias%20Hackradt%20%C2%B7%20Berlin%20%C2%B7%20self-hosting%2C%20mesh%20radio%20and%20questionable%20amounts%20of%20YAML&descSize=14&descAlignY=57" alt="BrutalBirdie" />
</p>

<p align="center">
  <img width="440" src="https://media.giphy.com/media/Nx0rz3jtxtEre/giphy.gif" alt="Obi-Wan Kenobi saying Hello There" />
</p>

<p align="center">
  <a href="https://knowyourmeme.com/memes/hello-there"><sub>(obligatory)</sub></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3200&pause=900&center=true&vCenter=true&width=760&lines=Customer+Success+Engineer+%40+Cloudron;I+package+open+source+apps+so+you+can+self-host+them;If+it+breaks+behind+a+reverse+proxy%2C+I+fix+it+upstream;Ansible+role+behind+a+lot+of+German+university+BBB;CloudFest+Hackathon+lifer+since+2016" alt="what I do" />
</p>

<p align="center">
  <a href="https://www.cloudron.io/"><img src="https://img.shields.io/badge/Cloudron-Customer%20Success%20Engineer-31a3d9?style=for-the-badge&logo=cloudron&logoColor=white" alt="Cloudron" /></a>
  <a href="https://forum.cloudron.io/user/brutalbirdie"><img src="https://img.shields.io/badge/Cloudron%20Forum-1.4k%20posts%20%C2%B7%201.8k%20rep-31a3d9?style=for-the-badge&logo=nodebb&logoColor=white" alt="Cloudron Forum" /></a>
  <a href="https://ca.cloudron.io/"><img src="https://img.shields.io/badge/Community%20Apps-4%20published-31a3d9?style=for-the-badge&logo=cloudron&logoColor=white" alt="Cloudron Community Apps" /></a>
</p>

<p align="center">
  <a href="https://matrix.to/#/@brutalbirdie:deadsec.net"><img src="https://img.shields.io/badge/Matrix-%40brutalbirdie%3Adeadsec.net-0DBD8B?style=for-the-badge&logo=matrix&logoColor=white" alt="Matrix" /></a>
  <a href="https://keyoxide.org/3EFABCB708412AEE165EDC6C7B17D07087F79F9E"><img src="https://img.shields.io/badge/Keyoxide-verify%20me-5f4dd0?style=for-the-badge&logo=gnuprivacyguard&logoColor=white" alt="Keyoxide" /></a>
  <a href="https://www.linkedin.com/in/elias-hackradt/"><img src="https://img.shields.io/badge/LinkedIn-Elias%20Hackradt-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://ko-fi.com/C0C7MDQO7"><img src="https://img.shields.io/badge/Ko--fi-buy%20me%20a%20coffee-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white" alt="Ko-fi" /></a>
</p>

---

## `whoami`

```console
$ ssh brutalbirdie@deadsec.net
Last login: probably still logged in, actually

$ whoami && cat /etc/motd
elias

  ┌─ Customer Success Engineer @ Cloudron UG ────────────────────────┐
  │  Cloudron turns a server into an app platform: install open      │
  │  source software in one click, get backups, SSL, SSO and         │
  │  updates for free. My job is the "one click" part, and the       │
  │  part where it keeps working at 23:00 on a Sunday.               |
  |  Or something like that (:                                       │
  └──────────────────────────────────────────────────────────────────┘

$ groups
cloudron  docker  ansible  nodebb  meshtastic  meshcore  reticulum  cloudfest

$ uptime
 on GitHub since 2016 · still here · load average: yes, yes, yes
```

---

## ☁️ Cloudron & the Open Source It Runs

[Cloudron](https://www.cloudron.io/) ([@cloudron-io](https://github.com/cloudron-io)) is a platform for self-hosting open source apps without becoming a sysadmin. Most of the **100+ apps in the [Cloudron App Store](https://www.cloudron.io/store/)** I have packaged, debugged, updated, or walked somebody through at some point.

### 📦 Apps I package and maintain

Published on [Cloudron Community Apps](https://ca.cloudron.io/):

| App | What it is | Source |
|---|---|---|
| **Tachyon** | Webmail client | [cloudron-tachyon-app](https://github.com/BrutalBirdie/cloudron-tachyon-app) |
| **PILOS** | Front end for BigBlueButton video conferencing | [ca.cloudron.io](https://ca.cloudron.io/) |
| **FoundryVTT** | Virtual tabletop. The dragons must be self-hosted too | [cloudron-foundryvtt](https://github.com/BrutalBirdie/cloudron-foundryvtt) |
| **Zabbix** | Enterprise-class distributed monitoring | [ca.cloudron.io](https://ca.cloudron.io/) |

and more!

### 🔧 Upstream, where the real work happens

A package is only as good as the app inside it. When an app can't cope with running behind a reverse proxy, as a non-root user, against an external database, with OIDC wired in and a read-only filesystem, the honest fix is upstream, so **everyone** gets it and not just Cloudron users.

Patches, packaging fixes and docs I've sent to projects that also live in the Cloudron store:

<p align="center">
  <a href="https://github.com/immich-app/immich"><img alt="immich" src="https://img.shields.io/badge/immich-000?style=flat-square&logo=immich&logoColor=fff" /></a>
  <a href="https://github.com/NodeBB/NodeBB"><img alt="NodeBB" src="https://img.shields.io/badge/NodeBB-000?style=flat-square&logo=nodebb&logoColor=fff" /></a>
  <a href="https://github.com/discourse/discourse"><img alt="Discourse" src="https://img.shields.io/badge/Discourse-000?style=flat-square&logo=discourse&logoColor=fff" /></a>
  <a href="https://github.com/knadh/listmonk"><img alt="listmonk" src="https://img.shields.io/badge/listmonk-000?style=flat-square&logo=listmonk&logoColor=fff" /></a>
  <a href="https://github.com/baserow/baserow"><img alt="Baserow" src="https://img.shields.io/badge/Baserow-000?style=flat-square&logo=baserow&logoColor=fff" /></a>
  <a href="https://github.com/pixelfed/pixelfed"><img alt="Pixelfed" src="https://img.shields.io/badge/Pixelfed-000?style=flat-square&logo=pixelfed&logoColor=fff" /></a>
  <a href="https://github.com/espocrm/espocrm"><img alt="EspoCRM" src="https://img.shields.io/badge/EspoCRM-000?style=flat-square" /></a>
  <a href="https://github.com/pentacent/keila"><img alt="Keila" src="https://img.shields.io/badge/Keila-000?style=flat-square&logo=elixir&logoColor=fff" /></a>
  <a href="https://github.com/miroslavpejic85/mirotalksfu"><img alt="MiroTalk SFU" src="https://img.shields.io/badge/MiroTalk%20SFU-000?style=flat-square&logo=webrtc&logoColor=fff" /></a>
  <a href="https://github.com/LibreChat-AI/librechat.ai"><img alt="LibreChat" src="https://img.shields.io/badge/LibreChat-000?style=flat-square" /></a>
  <a href="https://github.com/linkwarden/docs"><img alt="Linkwarden" src="https://img.shields.io/badge/Linkwarden-000?style=flat-square" /></a>
  <a href="https://github.com/louislam/uptime-kuma-wiki"><img alt="Uptime Kuma" src="https://img.shields.io/badge/Uptime%20Kuma-000?style=flat-square&logo=uptimekuma&logoColor=fff" /></a>
  <a href="https://github.com/miniflux/website"><img alt="Miniflux" src="https://img.shields.io/badge/Miniflux-000?style=flat-square&logo=rss&logoColor=fff" /></a>
  <a href="https://github.com/kontron/redmine_oauth"><img alt="Redmine OAuth" src="https://img.shields.io/badge/Redmine%20OAuth-000?style=flat-square&logo=redmine&logoColor=fff" /></a>
  <a href="https://github.com/joomla-projects/docker-images"><img alt="Joomla Docker" src="https://img.shields.io/badge/Joomla%20Docker-000?style=flat-square&logo=joomla&logoColor=fff" /></a>
  <a href="https://github.com/s3s-project/s3s"><img alt="s3s" src="https://img.shields.io/badge/s3s-000?style=flat-square&logo=rust&logoColor=fff" /></a>
</p>

<sub>~100 pull requests across ~30 repositories. Mostly *"this works everywhere except in a container"*, *"your docs are wrong"*, and *"here, have OIDC."*</sub>

---

## 🧰 Things I Point At Servers

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,ansible,bash,linux,debian,nginx,postgres,redis,nodejs,js,python,php,wordpress,git,gitlab,githubactions,grafana,cloudflare,vscode&perline=10" alt="tech stack" />
</p>

---

## 📦 Stuff I Built (or rescued)

| Project | What it is | |
|---|---|---|
| **[ansible-role-bigbluebutton](https://github.com/ebbba-org/ansible-role-bigbluebutton)** | The Ansible role that put BigBlueButton on a lot of German university servers when everyone suddenly needed it in 2020. Still maintained. | ![stars](https://img.shields.io/github/stars/ebbba-org/ansible-role-bigbluebutton?style=flat-square&label=&color=fbbf24) |
| **[nodebb-plugin-internalnotes](https://github.com/cloudron-io/nodebb-plugin-internalnotes)** | Internal staff notes and topic assignment for NodeBB, invisible to everyone but your team. Built for running a real support forum. | ![stars](https://img.shields.io/github/stars/cloudron-io/nodebb-plugin-internalnotes?style=flat-square&label=&color=fbbf24) |
| **[cloudron-foundryvtt](https://github.com/BrutalBirdie/cloudron-foundryvtt)** | Foundry VTT, packaged for Cloudron. | ![stars](https://img.shields.io/github/stars/BrutalBirdie/cloudron-foundryvtt?style=flat-square&label=&color=fbbf24) |
| **[zabbix-template-cloudron-by-api](https://github.com/BrutalBirdie/zabbix-template-cloudron-by-api)** | Monitor a whole Cloudron from Zabbix over the API. | ![stars](https://img.shields.io/github/stars/BrutalBirdie/zabbix-template-cloudron-by-api?style=flat-square&label=&color=fbbf24) |
| **[nodebb-plugin-usercleaner](https://github.com/BrutalBirdie/nodebb-plugin-usercleaner)** | Bulk-delete dormant, abandoned and spam accounts from a NodeBB forum. | ![stars](https://img.shields.io/github/stars/BrutalBirdie/nodebb-plugin-usercleaner?style=flat-square&label=&color=fbbf24) |
| **[nodebb-plugin-username-denylist](https://github.com/BrutalBirdie/nodebb-plugin-username-denylist)** | Block usernames at registration with literals or regex. | ![stars](https://img.shields.io/github/stars/BrutalBirdie/nodebb-plugin-username-denylist?style=flat-square&label=&color=fbbf24) |
| **[bookmark-tabgroup-manager](https://github.com/BrutalBirdie/bookmark-tabgroup-manager)** | Browser extension: bookmarks that remember which tab group they belong to. | ![stars](https://img.shields.io/github/stars/BrutalBirdie/bookmark-tabgroup-manager?style=flat-square&label=&color=fbbf24) |

---

## 🎢 CloudFest Hackathon

The [CloudFest Hackathon](https://hackathon.cloudfest.com/) is a three-day hackathon held as part of CloudFest, the internet infrastructure festival, at **Europa-Park in Rust, Germany**. Project leads bring not-for-profit, interoperable, **open source** projects; teams of maintainers, hosters and developers from all over the industry build them out together and present what they shipped on the last day.

I have been going **since 2016**. **2027 will be my tenth year.**

<table>
<tr>
<td align="center" width="33%">

### 🎢
**80+**<br />
roller coaster rides<br />
in Europa-Park<br />
<sub>at *least*. Silver Star does<br />not count itself.</sub>

</td>
<td align="center" width="33%">

### 🤝
**Since 2016**<br />
the same hallway track<br />
<sub>friends from every hoster,<br />CMS and registrar you've<br />heard of</sub>

</td>
<td align="center" width="33%">

### 🍹
**1 open bar**<br />
crowd-funded off a QR code<br />
<sub>see below</sub>

</td>
</tr>
</table>

### 🍸 The Crowd-Funded Open Bar

A hackathon runs on conversations, and conversations run on someone having bothered to bring the drinks. So in 2026 I did: bought the beverages, sourced cocktail shakers, ice, mixers, the lot. Set it all up and pinned a **QR code** next to it so anyone who wanted to could chip in.

No sponsor logo. No budget approval. No invoice. Just a bar that existed because a QR code was pinned to it. People **loved** it.

<p align="center">
  <img width="150" src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&ecc=M&margin=12&data=https%3A%2F%2Fko-fi.com%2FC0C7MDQO7" alt="QR code to Ko-fi" /><br />
  <sub>the spiritual successor · scan it, or just <a href="https://ko-fi.com/C0C7MDQO7">click here</a> like a normal person</sub>
</p>

<details>
<summary><b>⚠️ Do not open this. Seriously. Nothing good is in here.</b></summary>

<br />

🥚 **egg 2 / 5**: you have no self-control and I respect that enormously.

**⚔️ Footnote: the 2026 project.** I was on the team behind **[SWORD](https://github.com/SynioBE/SWORD)** (*Self-hosted WordPress Optimized Runtime on Docker*), a lightweight open source control panel that cuts the middleman out of WordPress hosting. One-click sites, SSL, caching, backups, DNS. Every stretch goal shipped.

It took **Overall Winner**, **Dream Team Award** and **Pitch Perfect Award**. We delivered the final pitch **in full knight roleplay, with foam swords.** Three awards later, I maintain this was a sound engineering decision.

```
      ___
     /   \      "None shall pass."
    | o o |
    |  >  |     - me, to a misconfigured reverse proxy
     \___/
    /|   |\
   / |   | \    'Tis but a scratch.
     |   |      (it was a full outage)
```

[Read the 2026 recap →](https://www.cloudfest.com/blog/cloudfest-hackathon-2026-recap)

</details>

---

## 📡 Berlin Chaos Mesh

Off-grid radio, because not everything should need a datacentre.
[Meshtastic](https://meshtastic.org/) · [MeshCore](https://meshcore.io/) · [Reticulum](https://reticulum.network/)

```
          (o)                       (o)
           |  ~ ~ ~ LoRa ~ ~ ~ ~ ~ ~ |
        [node]────────────────────[node]
           \                         /
            \       868 MHz         /
             \                     /
              `~ ~ ~ ~ [c-base] ~ '
                          |
                 forum.chaosmesh.net
```

I sponsor and host **[forum.chaosmesh.net](https://forum.chaosmesh.net/)**, Berlin's public forum for all the mesh protocols, where we work out governance, presets, channel docs, and the eternal question of whether the repeater on that roof is actually still up.

We meet **every 2nd Wednesday of the month, 19:00, at [c-base](https://c-base.org)**. No registration, no fee, bring a node.

<p align="center">
  <img width="130" src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&ecc=M&margin=12&data=https%3A%2F%2Fforum.chaosmesh.net%2F" alt="QR code to forum.chaosmesh.net" /><br />
  <sub>scan this at c-base and pretend you already knew about us</sub>
</p>

---

## 🌐 Side Quest

**[hackradt.com](https://www.hackradt.com/)**: managed self-hosting on German servers, for people who want digital sovereignty without reading a single `docker-compose.yml`. Nextcloud, GitLab, Element, n8n, mail, and 100+ more, kept patched and backed up so the customer doesn't have to think about it.

---

## 📊 The Obligatory Widgets

<!--
  🥚 egg 3 / 5

  The real stat is the one no dashboard renders: roughly 1,400 forum posts
  on forum.cloudron.io answering "why doesn't my reverse proxy work".
  That number is the actual career. -- BB

  (The contribution-snake image lives in .github/workflows/snake.yml.
   Run that workflow once (it creates the `output` branch), then drop
   this line back in:

   <img alt="contribution snake" src="https://raw.githubusercontent.com/BrutalBirdie/BrutalBirdie/output/github-snake-dark.svg" />
  )
-->

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=BrutalBirdie&theme=tokyonight" alt="profile summary" />
</p>

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=BrutalBirdie&theme=tokyonight" alt="repos per language" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=BrutalBirdie&theme=tokyonight" alt="most commit language" />
  <img height="180" src="https://streak-stats.demolab.com?user=BrutalBirdie&hide_border=true&theme=tokyonight&ring=26D0CE&fire=26D0CE&currStreakLabel=26D0CE" alt="streak" />
</p>

---

## 🔐 Prove It's Me

One key signs my commits, my mail, and my identity claims:

```
3EFA BCB7 0841 2AEE 165E  DC6C 7B17 D070 87F7 9F9E
```

<table>
<tr>
<td align="center" valign="middle" width="190">
<a href="https://keyoxide.org/3EFABCB708412AEE165EDC6C7B17D07087F79F9E"><img width="160" src="https://api.qrserver.com/v1/create-qr-code/?size=320x320&ecc=M&margin=12&data=https%3A%2F%2Fkeyoxide.org%2F3EFABCB708412AEE165EDC6C7B17D07087F79F9E" alt="QR code to my Keyoxide profile" /></a>
</td>
<td valign="middle">

**[keyoxide.org/3EFA…9F9E](https://keyoxide.org/3EFABCB708412AEE165EDC6C7B17D07087F79F9E)**

Cryptographically verified claims for GitHub, Matrix, Discord and `hackradt.com`, so you can check that the person messaging you is actually me.

```bash
gpg --locate-keys elias@hackradt.com
```

</td>
</tr>
</table>

<details>
<summary>🥚 One of these is not a GPG fingerprint</summary>

<br />

```
RWdnIDQvNS4gVGhlIGxhc3Qgb25lIGlzIGF0IHRoZSB2ZXJ5IGJvdHRvbSBvZiB0aGUgcmF3IGZpbGUuIEFsc286IGFzayBtZSBhYm91dCB0aGUgZm9hbSBzd29yZHMuIC0tIEJC
```

<sub>You know what to do. (Hint: it rhymes with <code>base64 -d</code>.)</sub>

</details>

---

## 💬 Say Hello There

I don't really do social media. Matrix is the way.

<table>
<tr>
<td align="center" valign="middle" width="190">
<a href="https://matrix.to/#/@brutalbirdie:deadsec.net"><img width="160" src="https://api.qrserver.com/v1/create-qr-code/?size=320x320&ecc=M&margin=12&data=https%3A%2F%2Fmatrix.to%2F%23%2F%40brutalbirdie%3Adeadsec.net" alt="QR code to my Matrix account" /></a>
</td>
<td valign="middle">

### [`@brutalbirdie:deadsec.net`](https://matrix.to/#/@brutalbirdie:deadsec.net)

End-to-end encrypted, federated, no algorithm, no *"are you still watching"*.<br />
Scan, click, or type it into your client of choice.

Otherwise: [LinkedIn](https://www.linkedin.com/in/elias-hackradt/) · [forum.cloudron.io](https://forum.cloudron.io/user/brutalbirdie) · [forum.chaosmesh.net](https://forum.chaosmesh.net/)

</td>
</tr>
</table>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BrutalBirdie&label=humans%20who%20scrolled%20this%20far&color=26d0ce&style=flat-square" alt="profile views" />
</p>

<p align="center">
  <a href="https://ko-fi.com/C0C7MDQO7"><img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Support me on Ko-fi" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:26d0ce,100:1a2980&height=110&section=footer" alt="" />
</p>

<!--
  ╔═══════════════════════════════════════════════════════════════════╗
  ║  🥚 egg 5 / 5: the bottom of the file. You made it.               ║
  ║                                                                   ║
  ║        .-"-.                                                      ║
  ║       /     \     CONGRATULATIONS                                 ║
  ║      | () () |    You have read an entire README in raw form      ║
  ║       \  ^  /     like some kind of absolute unit.                ║
  ║        |||||                                                      ║
  ║        |||||      Message me on Matrix with the word "PACKET"     ║
  ║                   and I'll tell you a genuinely cursed            ║
  ║                   self-hosting story. There are many.             ║
  ║                                                                   ║
  ║  For the record, the eggs were:                                   ║
  ║    1. this header block                                           ║
  ║    2. the <details> you were told not to open                     ║
  ║    3. a comment above the stats widgets                           ║
  ║    4. the base64 "fingerprint"                                    ║
  ║    5. right here                                                  ║
  ║                                                                   ║
  ║  Now go and back up something. -- BB                              ║
  ╚═══════════════════════════════════════════════════════════════════╝
-->
