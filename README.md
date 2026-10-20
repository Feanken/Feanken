<div align="center">
  <img src="asset/fotoProfile.png" alt="Foto profil Fransisco" width="150" />

  <h1>Halo! 👋 Saya Fransisco</h1>

  <p><strong>Cloud Engineering | Huawei Cloud | Linux | Containers &amp; Networking</strong></p>

  <p>Mahasiswa Computer Science di <strong>BINUS University</strong> yang berfokus pada cloud infrastructure, deployment, troubleshooting, dan cloud architecture.</p>

  <p>
    <a href="https://www.linkedin.com/in/fransiscoskw/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn" /></a>
    <a href="https://drive.google.com/file/d/1Ic_1j2mTqPEJGLNN07vkgBqXPzA_W3iP/view?usp=sharing"><img src="https://img.shields.io/badge/View%20My%20CV-24292F?style=for-the-badge&amp;logo=googledrive&amp;logoColor=white" alt="View My CV" /></a>
  </p>
</div>

---

## ☁️ Tentang Saya

Saya sedang mengembangkan karier di bidang **Cloud Engineering** dengan fokus pada **Huawei Cloud**. Saya tertarik pada bagaimana infrastruktur cloud dirancang, dijalankan, diamankan, dipantau, dan dipulihkan saat terjadi masalah.

Selain mempelajari konsep, saya melakukan **hands-on lab dan proof of concept (POC)** menggunakan Linux, virtual machine, container, web server, networking, dan database. Latar belakang Software Engineering membantu saya memahami kebutuhan aplikasi yang berjalan di atas infrastruktur tersebut.

**Area yang saya tekuni:** Cloud Infrastructure • Networking • Linux Administration • Containers • Database Migration • Backup & Disaster Recovery

## 🛠️ Teknologi & Pengalaman Teknis

| Area | Teknologi dan hal yang dipelajari |
| --- | --- |
| **Cloud Platform** | Huawei Cloud: ECS, VPC, EIP, Security Group, RDS for PostgreSQL, DRS, CDN, DNS, SFS Turbo |
| **Compute & Linux** | Ubuntu Server, SSH, Nginx, HTTPS/TLS, troubleshooting service dan konektivitas |
| **Networking** | IP addressing, subnet/CIDR, routing, firewall/security group, DNS records, reverse proxy, CDN caching |
| **Containers** | Docker, Dockerfile, Docker Compose, image, container, network, volume, logs, `docker exec` |
| **Database** | PostgreSQL, MySQL, `pg_dump`/`pg_restore`, pengenalan WAL, logical replication, CDC, primary/standby HA |
| **Tools** | Git, GitHub, Bash/Linux CLI, Python (dasar/scripting), SQL, Notion |

> **Catatan:** Daftar di atas mencakup pengalaman praktik dan topik yang sedang saya dalami, bukan klaim keahlian production-level untuk seluruh layanan.

### Sedang diperdalam

- **Cloud architecture & migration:** CBR, SMS, OMS, DRS, konsep RPO/RTO dan disaster recovery.
- **Kubernetes & monitoring:** Huawei Cloud CCE, metrik jaringan antarpod, AOM 2.0, Prometheus, dan observability.
- **Advanced cloud networking:** desain VPC/subnet, routing, konektivitas privat, serta network troubleshooting.
- **Tahap belajar berikutnya:** Infrastructure as Code (Terraform), CI/CD, Kubernetes operations, dan security best practices.

## 🚀 Cloud Engineering Labs & POC

Berikut rangkuman praktik yang pernah atau sedang saya kerjakan. **Repository dan dokumentasi publik untuk sebagian lab masih dalam proses penyusunan.**

### 1. 🌐 Web Deployment dengan CDN, DNS & SFS Turbo

**Status:** Hands-on lab

Membangun skenario hosting aplikasi berbasis **Huawei Cloud ECS** dengan **Nginx, HTTPS, DNS, CDN, dan SFS Turbo** untuk penyimpanan file. Mempelajari alur request dari pengguna ke CDN dan origin server.

**Pembelajaran utama:** DNS/CNAME, origin server, cache hit/miss, TLS, serta perbedaan traffic **GET (cacheable)** dan **POST/upload (diteruskan ke origin)**.

### 2. 🗄️ PostgreSQL Migration ke Huawei Cloud RDS

**Status:** POC dan pengujian

Menguji migrasi database PostgreSQL dari server berbasis ECS ke **RDS for PostgreSQL**, termasuk penggunaan **`pg_dump` + `pg_restore`** dan eksplorasi **Data Replication Service (DRS)**.

**Pembelajaran utama:** migrasi PostgreSQL 14 → 17 melalui dump/restore berhasil diuji; persiapan WAL/logical replication, konektivitas, cutover, CDC, serta konsep high availability primary/standby. **Sinkronisasi incremental DRS masih merupakan area pengujian/troubleshooting.**

### 3. 🐳 MyFlix — Web App dengan Docker Compose

**Status:** Lab selesai

Menjalankan aplikasi katalog video sederhana pada **Huawei Cloud ECS (Ubuntu)** menggunakan **Docker Compose** dan **Nginx container**, serta mengaksesnya melalui **SSH tunnel**.

**Pembelajaran utama:** lifecycle container, Docker image, Compose, port mapping, konfigurasi web server, dan troubleshooting HTTP.

### 4. 📝 Notepad — Arsitektur 3 Container

**Status:** Dalam pengembangan

Merancang aplikasi CRUD sederhana dengan tiga komponen terpisah: **frontend, backend, dan database**, dihubungkan menggunakan **Docker bridge network**.

**Fokus belajar:** komunikasi antarkontainer, Docker networking, penyimpanan database, dan pemisahan komponen aplikasi.

## 📈 Fokus Pembelajaran Saat Ini

```text
Cloud Engineering
├── Advanced Networking (VPC, Subnet, Routing, DNS, Security)
├── Linux & Server Administration
├── Containers (Docker → Kubernetes/CCE)
├── Database Migration, HA & Disaster Recovery
├── Monitoring & Observability
└── Automation (Bash/Python → Terraform & CI/CD)
```

Target saya adalah membangun portofolio **berbasis dokumentasi teknis**, bukan hanya membuat resource cloud: mulai dari tujuan, arsitektur, implementasi, pengujian, troubleshooting, sampai hasil pembelajaran.

## 💻 Background Software Engineering

Sebelum berfokus pada cloud, saya mempelajari **Java, C, C++, C#, HTML/CSS, SQL**, OOP, data structures, software design patterns, dan software engineering. Pengetahuan tersebut tetap saya gunakan untuk memahami aplikasi yang akan di-deploy dan dikelola di cloud.

<details>
<summary><strong>🎓 Lihat proyek software & kampus</strong></summary>

- **[Promigo](https://bit.ly/3FZMhHz)** — Platform informasi promo berbasis web. *React, Supabase, Laravel.* [Dokumentasi](https://bit.ly/4l5uwp6).
- **[JAwels & Diamonds](https://github.com/Feanken/Proyek_Pattern_Software_Design.git)** — Sistem manajemen item dengan penerapan *Strategy Pattern*. *Laravel, MySQL, Bootstrap.*
- **[Automatic License Plate Recognition](https://drive.google.com/drive/folders/1lXHBlc7O2RNH4PZBO6qLio90aBSur4Cg?usp=drive_link)** — Prototipe pengenalan plat kendaraan. *Python.*
- **[UI/UX Pariwisata Indonesia](https://www.figma.com/proto/eDqUFcYOg39vRn5vtabPbP/Figma-HCI?node-id=1-3&p=f&t=qRGJ9P7BjC0fLwiF-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A3)** — Prototipe website wisata. *Figma.*
- **[DiamondCuts Motors](https://www.figma.com/proto/lr3KauIxPFvJmG0qExRmwn/Untitled?node-id=3-4&starting-point-node-id=3%3A4)** — Prototipe dan frontend website showroom. *Figma, HTML, CSS, JavaScript.*

</details>

---

## 📫 Connect with Me

Saya terbuka untuk berdiskusi mengenai **cloud infrastructure, Huawei Cloud, Linux, Docker, cloud migration**, dan pembelajaran teknologi.

- **LinkedIn:** [fransiscoskw](https://www.linkedin.com/in/fransiscoskw/)
- **Email:** [fransisco001@binus.ac.id](mailto:fransisco001@binus.ac.id)
