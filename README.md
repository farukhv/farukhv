<!-- ╔═══════════════════════════════════════════════════════════════════════════╗
     ║  farukhv/farukhv — GitHub profil README'si  (v4 · kapsamlı)                ║
     ║  Görseller GitHub Action'larca üretilip repoya commit'lenir:              ║
     ║    · output dalı                     → yılan animasyonu (snake.yml)        ║
     ║    · profile-summary-card-output dalı → istatistik kartları (summary.yml)  ║
     ║    · main:github-metrics.svg          → zengin metrik kartı (metrics.yml)   ║
     ║  <!-- DÜZENLE --> işaretli yerleri kendine göre güncelle.                 ║
     ╚═══════════════════════════════════════════════════════════════════════════╝ -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F0A,45:00FF9C,100:00E5FF&height=210&section=header&text=%24%20ssh%20farukhv%40github&fontColor=0B0F0A&fontSize=40&fontAlignY=35&desc=Fullstack%20Developer%20%2F%2F%20Offensive%20Security%20%2F%2F%20Linux%20%26%20CI%2FCD&descAlignY=57&descSize=16&animation=fadeIn" width="100%" alt="header"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=900&color=00FF9C&center=true&vCenter=true&width=780&height=46&lines=multi-tenant+API'ler+tasarl%C4%B1yorum+(NestJS+%2B+Prisma);%C3%B6nce+k%C4%B1r%C4%B1yorum%2C+sonra+sertle%C5%9Ftiriyorum;React+%2B+Vite+%2B+Tailwind+cephede;Linux+%C2%B7+Docker+%C2%B7+GitHub+Actions+dipte;canl%C4%B1da+do%C4%9Frulanmayan+i%C5%9F+bitmemi%C5%9Ftir." alt="typing"/>

<br/>

<a href="mailto:mfarukmenek@gmail.com"><img src="https://img.shields.io/badge/e--mail-0B0F0A?style=for-the-badge&logo=gmail&logoColor=00E5FF" alt="mail"/></a>
<img src="https://komarev.com/ghpvc/?username=farukhv&style=for-the-badge&color=00FF9C&labelColor=0B0F0A&label=VISITORS" alt="views"/>
<img src="https://img.shields.io/github/followers/farukhv?style=for-the-badge&logo=github&logoColor=00FF9C&labelColor=0B0F0A&color=0B0F0A" alt="followers"/>
<!-- DÜZENLE: LinkedIn / kişisel site rozetlerini ekle
<a href="https://linkedin.com/in/KULLANICI"><img src="https://img.shields.io/badge/linkedin-0B0F0A?style=for-the-badge&logo=linkedin&logoColor=00E5FF"/></a>
<a href="https://SITEN"><img src="https://img.shields.io/badge/website-0B0F0A?style=for-the-badge&logo=firefoxbrowser&logoColor=00FF9C"/></a>
-->

</div>

---

## `~$ whoami`

```console
farukhv@github:~$ cat ./profile.json
{
  "name"        : "Muhammed Faruk Menek",
  "roles"       : ["Fullstack Developer", "Offensive Security Enthusiast"],
  "location"    : "Türkiye",
  "currently"   : "çok kiracılı (multi-tenant) belediye erişilebilirlik platformu",
  "backend"     : "NestJS · TypeScript · Prisma · PostgreSQL · Redis · REST + WebSocket",
  "frontend"    : "React · Vite · Tailwind · TypeScript",
  "ops"         : "Docker · GitHub Actions · Linux · OpenLiteSpeed / Nginx · PM2",
  "principle"   : "passing tests != deployed  —  canlıda doğrulanmayan iş bitmemiştir",
  "learning"    : ["sistem & container sertleştirme", "tehdit modelleme", "observability / tracing"],
  "open_to"     : "API tasarımı · multi-tenant mimari · güvenli-varsayılan sistemler · erişilebilirlik"
}
```

---

## `~$ cat ./focus.md`

- **Backend mimarisi** — çok kiracılı izolasyon, rol tabanlı yetkilendirme (RBAC), tutarlı yanıt zarfı + hata sözleşmesi, hız sınırlama, denetim günlüğü (audit log), el yazımı ve geri-alınabilir veritabanı migration'ları.
- **API sözleşmesi** — OpenAPI/Swagger ile üretilen, istemci ekiplerinin (web + mobil) tek kaynaktan tükettiği 200+ uçlu REST + Socket.IO yüzeyi; her istekte `x-request-id` korelasyonu.
- **CI/CD** — push → test → otomatik deploy; migration'ların gerçekten uygulandığını doğrulayan, mock testleri "kanıt" saymayan bir hat.
- **Güvenlik** — yetkili sızma testi, defansif güvenlik, en az yetki (least-privilege) servis çalıştırma, doğrudan port erişiminin kapatılması, TLS-only.
- **Erişilebilirlik** — WCAG 2.2 AA sonradan-ekleme değil, gereksinim.

---

## `~$ cat ./work.md`

### 🏢 Kaya Software · Fullstack Developer

Belediyeler için **erişilebilir dijital sistemler** geliştiriyorum — dezavantajlı
vatandaşların da tam kullanabildiği, çok kiracılı (multi-tenant) hizmet platformları.

<table>
<tr>
<td valign="top" width="50%">

**Backend platformu**

```text
· NestJS · Prisma · PostgreSQL · Redis
· 200+ REST ucu + Socket.IO (canlı destek, araç takibi)
· JWT + refresh token rotation · 4 rollü RBAC
· tek kiracı izolasyonu + global katalog modeli
· global response envelope + hata sözleşmesi
· hız sınırlama · audit log · belge doğrulama akışı
· el yazımı, geri-alınabilir DB migration + baseline
· OpenAPI/Swagger'dan üretilen tek-kaynak API sözleşmesi
```

![NestJS](https://img.shields.io/badge/-NestJS-0B0F0A?style=flat-square&logo=nestjs&logoColor=E0234E)
![Prisma](https://img.shields.io/badge/-Prisma-0B0F0A?style=flat-square&logo=prisma&logoColor=2D3748)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-0B0F0A?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/-Redis-0B0F0A?style=flat-square&logo=redis&logoColor=DC382D)

</td>
<td valign="top" width="50%">

**Web istemcisi & deploy**

```text
· React + Vite + TypeScript + Tailwind
· axios: token rotation interceptor,
  401 → refresh → retry, oturum-çalma koruması
· x-request-id korelasyonu, tipli response zarfı
· WCAG 2.2 AA hedefi · SPA fallback
· GitHub Actions: push → test → otomatik deploy
· ters vekil + TLS-only, doğrudan port erişimi kapalı
```

![React](https://img.shields.io/badge/-React-0B0F0A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/-Vite-0B0F0A?style=flat-square&logo=vite&logoColor=646CFF)
![TypeScript](https://img.shields.io/badge/-TypeScript-0B0F0A?style=flat-square&logo=typescript&logoColor=3178C6)
![GitHub Actions](https://img.shields.io/badge/-Actions-0B0F0A?style=flat-square&logo=githubactions&logoColor=2088FF)

</td>
</tr>
</table>

### ♿ Erişilebilir Sistemler — çalışma prensibim

- Erişilebilirlik (WCAG 2.2 AA) tasarımın en başında; klavye, ekran okuyucu ve
  düşük görüş senaryoları test kapsamında.
- Hata mesajları, form doğrulama ve durum bildirimleri makine + insan tarafından
  okunabilir; her yanıt bir `requestId` ile izlenebilir.
- "Herkes için çalışır" = performans, düşük bant genişliği ve eski cihaz da dahil.

---

## `~$ nmap -sV --script=skills localhost`

<table>
<tr>
<td valign="top" width="50%">

**`3000/tcp` — backend**

![NestJS](https://img.shields.io/badge/NestJS-0B0F0A?style=flat-square&logo=nestjs&logoColor=E0234E)
![Node.js](https://img.shields.io/badge/Node.js-0B0F0A?style=flat-square&logo=nodedotjs&logoColor=339933)
![TypeScript](https://img.shields.io/badge/TypeScript-0B0F0A?style=flat-square&logo=typescript&logoColor=3178C6)
![Prisma](https://img.shields.io/badge/Prisma-0B0F0A?style=flat-square&logo=prisma&logoColor=2D3748)
![Express](https://img.shields.io/badge/Express-0B0F0A?style=flat-square&logo=express&logoColor=FFFFFF)
![Socket.io](https://img.shields.io/badge/Socket.io-0B0F0A?style=flat-square&logo=socketdotio&logoColor=FFFFFF)
![Jest](https://img.shields.io/badge/Jest-0B0F0A?style=flat-square&logo=jest&logoColor=C21325)
![Swagger](https://img.shields.io/badge/OpenAPI-0B0F0A?style=flat-square&logo=swagger&logoColor=85EA2D)

**`5173/tcp` — frontend**

![React](https://img.shields.io/badge/React-0B0F0A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-0B0F0A?style=flat-square&logo=vite&logoColor=646CFF)
![Tailwind](https://img.shields.io/badge/Tailwind-0B0F0A?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![React Router](https://img.shields.io/badge/Router-0B0F0A?style=flat-square&logo=reactrouter&logoColor=CA4245)
![Vitest](https://img.shields.io/badge/Vitest-0B0F0A?style=flat-square&logo=vitest&logoColor=6E9F18)
![Axios](https://img.shields.io/badge/Axios-0B0F0A?style=flat-square&logo=axios&logoColor=5A29E4)

**`5432/tcp` — data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0B0F0A?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0B0F0A?style=flat-square&logo=redis&logoColor=DC382D)
![Prisma](https://img.shields.io/badge/Prisma%20ORM-0B0F0A?style=flat-square&logo=prisma&logoColor=2D3748)

</td>
<td valign="top" width="50%">

**`443/tcp` — security & offensive**

![Kali](https://img.shields.io/badge/Kali%20Linux-0B0F0A?style=flat-square&logo=kalilinux&logoColor=00E5FF)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-0B0F0A?style=flat-square&logo=burpsuite&logoColor=FF6633)
![Metasploit](https://img.shields.io/badge/Metasploit-0B0F0A?style=flat-square&logo=metasploit&logoColor=2596CD)
![Nmap](https://img.shields.io/badge/Nmap-0B0F0A?style=flat-square&logo=&logoColor=00FF9C)
![Wireshark](https://img.shields.io/badge/Wireshark-0B0F0A?style=flat-square&logo=wireshark&logoColor=1679A7)
![OWASP](https://img.shields.io/badge/OWASP-0B0F0A?style=flat-square&logo=owasp&logoColor=00FF9C)
![JWT](https://img.shields.io/badge/JWT-0B0F0A?style=flat-square&logo=jsonwebtokens&logoColor=FFFFFF)

**`22/tcp` — devops & infra**

![Docker](https://img.shields.io/badge/Docker-0B0F0A?style=flat-square&logo=docker&logoColor=2496ED)
![GitHub Actions](https://img.shields.io/badge/Actions-0B0F0A?style=flat-square&logo=githubactions&logoColor=2088FF)
![Linux](https://img.shields.io/badge/Linux-0B0F0A?style=flat-square&logo=linux&logoColor=FCC624)
![Nginx](https://img.shields.io/badge/Nginx-0B0F0A?style=flat-square&logo=nginx&logoColor=009639)
![PM2](https://img.shields.io/badge/PM2-0B0F0A?style=flat-square&logo=pm2&logoColor=2B037A)
![Bash](https://img.shields.io/badge/Bash-0B0F0A?style=flat-square&logo=gnubash&logoColor=4EAA25)

**`8080/tcp` — tooling**

![Git](https://img.shields.io/badge/Git-0B0F0A?style=flat-square&logo=git&logoColor=F05032)
![VS Code](https://img.shields.io/badge/VS%20Code-0B0F0A?style=flat-square&logo=visualstudiocode&logoColor=007ACC)
![Postman](https://img.shields.io/badge/Postman-0B0F0A?style=flat-square&logo=postman&logoColor=FF6C37)
![Figma](https://img.shields.io/badge/Figma-0B0F0A?style=flat-square&logo=figma&logoColor=F24E1E)

</td>
</tr>
</table>

---

## `~$ ./contributions.sh --animate`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/farukhv/farukhv/output/github-snake-dark.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/farukhv/farukhv/output/github-snake.svg"/>
</picture>

</div>

---

## `~$ git shortlog -sn --all`

<div align="center">

<img src="https://raw.githubusercontent.com/farukhv/farukhv/profile-summary-card-output/2077/0-profile-details.svg" width="98%" alt="profile-details"/>

<img src="https://raw.githubusercontent.com/farukhv/farukhv/profile-summary-card-output/2077/3-stats.svg" width="49%" alt="stats"/>
<img src="https://raw.githubusercontent.com/farukhv/farukhv/profile-summary-card-output/2077/4-productive-time.svg" width="49%" alt="productive-time"/>

<img src="https://raw.githubusercontent.com/farukhv/farukhv/profile-summary-card-output/2077/1-repos-per-language.svg" width="49%" alt="repos-per-language"/>
<img src="https://raw.githubusercontent.com/farukhv/farukhv/profile-summary-card-output/2077/2-most-commit-language.svg" width="49%" alt="most-commit-language"/>

<br/><br/>

<img src="https://streak-stats.demolab.com/?user=farukhv&hide_border=true&background=0B0F0A&stroke=00FF9C&ring=00E5FF&fire=00FF9C&currStreakLabel=00FF9C&sideNums=C9D1D9&sideLabels=C9D1D9&dates=8B949E" width="98%" alt="streak"/>

</div>

---

## `~$ ./metrics --full --plugins=all`

<div align="center">

<!-- METRICS_TOKEN secret'ı eklenince dolar. İstemezsen bu bloğu sil. -->
<img src="https://raw.githubusercontent.com/farukhv/farukhv/main/github-metrics.svg" width="98%" alt="metrics"/>

</div>

---

## `~$ tail -f /var/log/now.log`

```log
[focus ] backend güvenliği: servisleri root'tan çıkarma, systemd/container sertleştirme
[focus ] observability: yapılandırılmış log + request tracing + sağlık uçları
[read  ] OWASP ASVS · "Designing Data-Intensive Applications" · Linux hardening kılavuzları
[goal  ] açık kaynak bir NestJS multi-tenant starter'ı yayınlamak
[goal  ] TryHackMe / HackTheBox düzenli pratik  <!-- DÜZENLE: gerçek profillerini ekle -->
```

---

## `~$ ./connect.sh`

<div align="center">

<a href="mailto:mfarukmenek@gmail.com"><img src="https://img.shields.io/badge/Gmail-0B0F0A?style=for-the-badge&logo=gmail&logoColor=EA4335"/></a>
<a href="https://github.com/farukhv"><img src="https://img.shields.io/badge/GitHub-0B0F0A?style=for-the-badge&logo=github&logoColor=FFFFFF"/></a>
<!-- DÜZENLE:
<a href="https://linkedin.com/in/KULLANICI"><img src="https://img.shields.io/badge/LinkedIn-0B0F0A?style=for-the-badge&logo=linkedin&logoColor=0A66C2"/></a>
<a href="https://twitter.com/KULLANICI"><img src="https://img.shields.io/badge/X-0B0F0A?style=for-the-badge&logo=x&logoColor=FFFFFF"/></a>
<a href="https://SITEN"><img src="https://img.shields.io/badge/Website-0B0F0A?style=for-the-badge&logo=firefoxbrowser&logoColor=FF7139"/></a>
-->

<br/><br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=algolia" alt="quote"/>

<br/>

`[ EOF ] — thanks for reading the source`

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,55:00FF9C,100:0B0F0A&height=110&section=footer" width="100%" alt="footer"/>
