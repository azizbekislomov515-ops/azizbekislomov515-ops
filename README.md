<div align="center">

# Azizbek Islomov

### Cybersecurity · DevOps · SOC · Tashkent

[![Linux](https://img.shields.io/badge/Linux-Kali_|_Ubuntu-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kali.org)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://docker.com)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)](https://terraform.io)
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)](https://ansible.com)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://postgresql.org)

![Location](https://img.shields.io/badge/Tashkent-Uzbekistan-0ea5e9?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-DevOps_&_SOC-8b5cf6?style=flat-square)
![TATU](https://img.shields.io/badge/TATU-Kiberxavfsizlik-10b981?style=flat-square)
![Approach](https://img.shields.io/badge/Offline--first-no_telemetry-6366f1?style=flat-square)

</div>

---

## 🛠️ Nima bilan shug'ullanaman

<table>
<tr>
<td width="50%" valign="top">

**Asosiy yo'nalishlar**

- Xavfsizlik siyosati: SIEM, DLP, Honeypot, WAF, Anti-DDoS
- Windows va Linux serverlar, firewall, switch va routerlar
- Docker, Kubernetes, Terraform, Ansible bilan deploy
- Monitoring: Prometheus, Grafana, Zabbix
- Xavfsizlik vositalari: log tahlili, hash, antivirus skaner

</td>
<td width="50%" valign="top">

**Nimasi bilan ajralaman**

- Hamma narsani hujjatlashtiraman: threat model, arxitektura, deploy
- Avval laboratoriyada sinab, keyin yozaman
- Ma'lumot kompyuterdan chiqmaydi: tarmoqsiz, telemetriyasiz
- Har bir loyihada testlar va CI

</td>
</tr>
</table>

---

## 💻 Loyihalar

### [🔍 LogLens](https://github.com/azizbekislomov515-ops/log-viewer) · Python · Linux

Linux'dagi barcha log manbalarini (systemd, Docker, Compose, Squid, nginx, `auth.log`)
o'zi topadi va nima bo'layotganini oddiy tilda tushuntiradi: sabab va keyingi qadam
bilan. AI'siz, tarmoqsiz, root'siz. Parol, token va kalitlar saqlashdan oldin o'chiriladi.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rules](https://img.shields.io/badge/qoidalar-224_ta_·_8_paket-6366f1?style=flat-square)
![Docker](https://img.shields.io/badge/Docker_|_systemd-2496ED?style=flat-square&logo=docker&logoColor=white)

<sub>Squid, ClamAV, Docker, Compose, sshd, nginx, systemd, kernel uchun testlangan qoidalar · [threat model](https://github.com/azizbekislomov515-ops/log-viewer/blob/main/docs/THREAT_MODEL.md)</sub>

---

### [🛡️ BlackShield](https://github.com/azizbekislomov515-ops/BlackShield) · Kotlin · C++ · FastAPI

Android uchun xavfsizlik ilovasi: imzo bazasi bo'yicha zararli APK'larni aniqlaydi.
Skaner C++ da (NDK), interfeys Jetpack Compose, imzolar FastAPI + PostgreSQL backend'dan
sinxronlanadi.

![Kotlin](https://img.shields.io/badge/Kotlin-Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C++17-NDK-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![YARA](https://img.shields.io/badge/YARA-qoidalar-8b5cf6?style=flat-square)

<sub>GoogleTest + instrumented testlar, EICAR test-ilova bilan end-to-end tekshiruv, strict lint · detekt · ktlint</sub>

---

<table>
<tr>
<td width="50%" valign="top">

### [#️⃣ HashForge](https://github.com/azizbekislomov515-ops/HASH_data)
Offline hash, HMAC va checksum kalkulyatori (PySide6). Fayl, papka, matn;
digest'ni `hmac.compare_digest` bilan solishtiradi.
<br><sub>**Tarmoqsiz · Linux va Windows**</sub>

</td>
<td width="50%" valign="top">

### [🔢 crypto-web](https://github.com/azizbekislomov515-ops/crypto-web)
Berilgan modul bo'yicha primitiv ildizlarni hisoblovchi web ilova.
<br><sub>**Next.js · Supabase · Docker**</sub>

</td>
</tr>
<tr>
<td valign="top">

### 🔒 Soloscience
Matematika va fizikani o'rganish uchun web platforma.
<br><sub>**Next.js · FastAPI · nginx · yopiq kod**</sub>

</td>
<td valign="top">

### 🔒 teachers_test_bot
O'qituvchilar attestatsiyasi uchun test boti va admin panel.
<br><sub>**Python · Telegram · Docker · yopiq kod**</sub>

</td>
</tr>
</table>

<sub>🔒 — yopiq repozitoriylar. Kodga kirish so'rov bo'yicha beriladi.</sub>

---

## 📚 Texnologiyalar

| Yo'nalish | Texnologiyalar |
| --- | --- |
| **Xavfsizlik** | SIEM, DLP, Honeypot, WAF, Anti-DDoS, firewall |
| **Infratuzilma** | Windows Server, Linux, DNS, DHCP, pochta va web serverlar |
| **DevOps** | Docker, Kubernetes, Terraform, Ansible, Redis |
| **Monitoring** | Prometheus, Grafana, Zabbix |
| **Tarmoq va VPN** | WireGuard, OpenVPN, switch va routerlar |
| **Dasturlash va BD** | Python, C++, MySQL, PostgreSQL |

---

## 💼 Tajriba va ta'lim

**System Administrator** · LOGISTIC SOLUTION OOO · 2025 (3 oy)

**Talaba, Kiberxavfsizlik** · Muhammad al-Xorazmiy nomidagi TATU · 2024-yildan
<br><sub>Mutaxassislik: kiberxavfsizlik injiniringi (DevOps va SOC analyst)</sub>

🌐 O'zbek · Rus · Ingliz

---

<div align="center">

### Bog'lanish

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Elite_azi)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/azizbekislomov515-ops)

</div>
