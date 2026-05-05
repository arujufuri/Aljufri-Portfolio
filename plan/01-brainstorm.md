# 01: Brainstorm

## Langkah

### 1. Kirim Prompt ke AI

```
Role: UX/UI consultant untuk portfolio developer.
Task: Bantu brainstorm desain portfolio untuk fresh graduate IT.

Context:
- Nama: [NAMA]
- Skills: [LIST]
- Target: [STARTUP / CORPORATE]

Constraints:
- Mobile-first
- Simple tapi stand out

Output:
1. 3 color palette options
2. Typography recommendation
3. Section structure
4. 1 unique element
```

### 2. Lanjutkan Diskusi

Tanya tentang:
- "Kenapa pilih warna ini?"
- "Inter vs Poppins, mana lebih cocok?"
- "Single page vs multi-page?"
- "Bagaimana beda dari candidate lain?"

---

## Dokumentasi

```markdown
# Brainstorm — [Aljufri]

## Prompt 1
[Role: UX/UI consultant untuk portfolio developer.
Task: Bantu brainstorm desain portfolio untuk fresh graduate IT.

Context:
- Nama: [NAMA]
- Skills: [LIST]
- Target: [STARTUP / CORPORATE]

Constraints:
- Mobile-first
- Simple tapi stand out

Output:
1. 3 color palette options
2. Typography recommendation
3. Section structure
4. 1 unique element]

## AI Response 1
[1. Color Palette Options
Pilih satu palet yang paling sesuai dengan personal brand yang ingin kamu tonjolkan:

Option A: "The Modern Engineer" (Trust & Tech)

Background: Off-White (#F8F9FA)

Primary Text: Slate Gray (#343A40)

Accent: Tech Blue (#0066FF)

Vibe: Sangat disukai Corporate. Bersih, terpercaya, dan profesional. Fokus pada konten dan keterbacaan.

Option B: "The Agile Hacker" (Bold & Minimalist)

Background: Deep Midnight (#0D1117 - ala GitHub dark mode)

Primary Text: Soft Ash (#C9D1D9)

Accent: Electric Mint/Neon Green (#2EA043 atau #00FF66)

Vibe: Menarik perhatian Startup. Memberikan kesan developer sejati, dinamis, dan terbiasa dengan terminal/CLI.

Option C: "The Solid Architect" (Earthy & Grounded)

Background: Warm Sand/Beige (#FDFBF7)

Primary Text: Dark Charcoal (#222222)

Accent: Rust Orange (#D9534F) atau Deep Forest Green (#2E4A3D)

Vibe: Unik dan stand out di tengah lautan portfolio berwarna biru/hitam. Memberikan kesan mature dan solid.

2. Typography Recommendation
Karena kita mengusung konsep simple but stand out, tipografi adalah kunci utama antarmuka (UI) kamu.

Headings (H1, H2, H3): Space Grotesk atau Syne.

Alasan: Font ini memiliki sentuhan geometris dan teknikal, sangat cocok untuk portofolio IT tanpa terlihat kaku.

Body Text: Inter atau Roboto.

Alasan: Super bersih, sangat mudah dibaca di layar mobile, dan memberikan kesan aplikasi profesional.

Micro-copy / Tech Stack Tags: Fira Code atau JetBrains Mono.

Alasan: Font monospace (ala teks di code editor) khusus untuk menuliskan skill (misal: <Golang/>, {MySQL}) untuk mempertegas identitas developer.

3. Section Structure (Mobile-First)
Desain mobile-first berarti tata letak vertikal yang mengalir natural, tidak memaksakan elemen berdampingan (side-by-side) yang membuat layar sempit.

Header & Navigation:

Logo simpel berupa inisial "AL" di kiri, tombol hamburger menu di kanan. Saat di-scroll, header berubah menjadi glassmorphism (sedikit transparan dan blur).

Hero Section:

Headline besar: "Building Robust Backends & Scalable APIs."

Sub-headline: "Hi, I'm Aljufri. A software developer specializing in Java, Python, and Golang."

Call to Action (CTA): Dua tombol bertumpuk (1. "View Projects" [Primary], 2. "Download CV" [Secondary outline]).

Tech Stack (Marquee/Pills):

Jangan gunakan progress bar (persentase skill seringkali ambigu).

Gunakan desain chip/pill yang berjajar rapi untuk: Java, Python, Golang, RESTful API, MySQL, dll.

Projects (The Core - Stacked Cards):

Karena proyek backend jarang punya screenshot UI yang cantik, gunakan desain kartu (card).

Format Kartu: Judul Proyek, Deskripsi Singkat (Fokus pada Problem & Solution), dan Tag Teknologi yang digunakan.

Experience / Education:

Desain timeline vertikal yang simpel (garis di sebelah kiri, detail di kanan).

Footer / Contact:

Teks ajakan: "Let's build something scalable together."

Ikon besar dan tappable (mudah disentuh jari) menuju GitHub, LinkedIn, dan Email.

4. Unique Element: "The API Response Card"
Karena kamu ahli di pembuatan RESTful API, mari jadikan ini daya tarik utama portofoliomu.

Idenya: Pada bagian Hero Section atau About Me, buat sebuah elemen visual berbentuk blok kode terminal atau jendela browser sederhana.

Interaksi: Alih-alih menulis paragraf "About Me" yang membosankan, tampilkan data dirimu dalam format JSON response.

Contoh Visualnya (Bisa dibuat dengan HTML/CSS sederhana):

JSON
GET /api/v1/developer/aljufri

{
  "status": 200,
  "message": "Developer data retrieved successfully",
  "data": {
    "name": "Aljufri",
    "role": "Backend Developer",
    "core_langs": ["Java", "Python", "Golang"],
    "focus": "Building reliable and fast APIs",
    "ready_for_work": true
  }
}


Elemen ini sangat simple, mudah dibuat dengan basic HTML/CSS, langsung menunjukkan pemahamanmu tentang struktur API, dan 100% akan membuat recruiter dari Tech Startup tersenyum melihatnya karena relatable.]

## Prompt 2 
[Kenapa Pilih Warna ini?]

## AI Response 2
[1. Kenapa Option A (Biru & Putih) - "The Modern Engineer"?
Psikologi Warna: Biru di dunia desain identik dengan kepercayaan, keamanan, dan stabilitas.

Target: Ini adalah "warna aman" yang sangat disukai oleh Corporate (seperti perbankan, instansi pemerintah, atau perusahaan enterprise besar).

Pesan Tersembunyi: "Saya adalah developer Java/Python yang menulis kode dengan rapi, aman, minim bug, dan bisa diandalkan untuk sistem skala besar."

2. Kenapa Option B (Gelap & Neon) - "The Agile Hacker"?
Psikologi Warna: Mode gelap (dark mode) merepresentasikan fokus, teknologi tinggi, dan modernitas. Aksen neon (seperti hijau mint atau hijau terminal) memberikan kesan enerjik dan progresif.

Target: Sangat menarik perhatian para founder atau Tech Lead di Startup. Lingkungan startup menyukai developer yang gesit dan passionate.

Pesan Tersembunyi: "Habitat asli saya adalah terminal dan code editor. Saya terbiasa dengan ekosistem modern, API, dan siap coding cepat untuk mengejar deployment."

3. Kenapa Option C (Krem & Earth Tones) - "The Solid Architect"?
Psikologi Warna: Warna membumi (earth tones) seperti krem, beige, atau merah bata (rust) memberikan kesan dewasa, elegan, dan approachable (mudah didekati/diajak kerja sama).

Target: Cocok untuk Startup yang fokus pada desain/kreativitas, atau Corporate modern yang menghargai inovasi.

Pesan Tersembunyi: Mayoritas portofolio programmer berwarna hitam atau biru. Dengan menggunakan palet ini, kamu langsung stand out. Pesan yang disampaikan adalah: "Meskipun saya orang teknis (backend), saya punya selera yang baik, rapi dalam berpikir, dan mudah berkolaborasi dengan tim lain."]

## Prompt 3
[Inter vs Poppins, mana lebih cocok?]

## AI Response 3
[1. Inter (The UI Workhorse)
Karakter: Bersih, netral, dan sangat presisi. Inter memang didesain secara khusus untuk antarmuka pengguna (UI) dan keterbacaan maksimal di layar digital.

Vibe: "Saya adalah engineer yang fokus pada efisiensi, performa, dan kode yang rapi."

Kelebihan untuk Mobile-First: Proporsi huruf Inter sedikit lebih ramping. Ini sangat menguntungkan di layar mobile karena kamu bisa memuat deskripsi proyek atau tech stack tanpa membuat layar terasa sesak.

Kecocokan Target: Sangat disukai oleh Corporate karena terasa formal, serius, dan terpercaya.

2. Poppins (The Friendly Geometric)
Karakter: Geometris dengan lengkungan yang sangat membulat (lihat huruf 'O'-nya yang bulat sempurna). Terasa hangat, modern, dan sangat bersahabat.

Vibe: "Saya inovatif, mudah diajak berkolaborasi, dan punya sentuhan tech-savvy yang kekinian."

Kelemahan untuk Mobile-First: Poppins memakan lebih banyak ruang horizontal (wide footprint). Di layar HP yang sempit, teks deskripsi yang panjang menggunakan Poppins bisa cepat turun ke baris baru dan membuat desain terasa "gemuk" atau penuh.

Kecocokan Target: Sangat disukai oleh Startup yang ingin terlihat fresh dan kreatif.

Rekomendasi Konsultan: Gunakan Kombinasi Keduanya
Karena kamu adalah seorang Backend Developer (yang identik dengan logika, presisi, dan struktur), Inter adalah pilihan yang paling aman dan solid untuk fondasi portofoliomu. Namun, karena kamu juga ingin membidik Startup, kamu tidak perlu membuang Poppins sepenuhnya.

Kamu bisa menggabungkan keduanya untuk mendapatkan porsi desain yang seimbang:

Untuk Heading/Judul (H1, H2): Gunakan Poppins (Bold). Ini akan memberikan kesan pertama yang ramah, berani, dan modern saat recruiter dari startup melihat namamu.

Untuk Body Text & Paragraf: Gunakan Inter (Regular/Medium). Ini akan memastikan deskripsi proyek API dan keahlian Java/Golang kamu sangat mudah dibaca oleh manajer HRD dari perusahaan korporat, terutama di layar HP.]

## Prompt 4
[Single page vs multi-page?]

## AI Response 4
[1. Hukum 6 Detik Rekruter (Recruiter UX)
Manajer HRD dan Tech Lead biasanya hanya menghabiskan 6-10 detik pertama untuk memindai (skimming) portofolio.

Single Page: Semua informasi penting (Skills, Tech Stack, Projects, Contact) disajikan dalam satu "piring". Mereka hanya perlu scroll ke bawah tanpa hambatan.

Multi-Page: Memaksa mereka mencari menu, mengklik, dan menunggu halaman baru dimuat. Jika mereka tidak segera melihat proyekmu di halaman depan, mereka mungkin akan langsung menutup situs tersebut.

2. Mobile-First = Scrolling > Clicking
Secara psikologis, pengguna smartphone lebih suka men-scroll layar panjang tanpa henti (seperti di Instagram atau TikTok) daripada harus mengklik tombol hamburger menu, mencari tautan navigasi, dan pindah halaman. Single page memberikan pengalaman navigasi yang jauh lebih natural di layar sentuh.

3. Menghindari Efek "Ruang Kosong" (Content Density)
Sebagai fresh graduate, jumlah proyek komersial atau pengalaman kerjamu mungkin belum sebanyak senior.

Jika kamu menggunakan multi-page dan mengalokasikan satu halaman penuh hanya untuk "About Me" atau "Experience" yang isinya baru satu atau dua poin, halamannya akan terlihat sepi dan kurang meyakinkan.

Dengan single page, semua informasi digabungkan. Ini menciptakan ilusi bahwa portofoliomu padat, berisi, dan kaya akan konten.

4. Sesuai dengan Level Keahlian Frontend
Mengingat keahlianmu fokus pada backend (Java, Python, Golang) dengan kemampuan HTML5/CSS3 yang basic, membangun satu halaman single page yang sangat solid, rapi, dan responsif jauh lebih masuk akal. Mengatur routing untuk banyak halaman akan memakan waktu yang seharusnya bisa kamu pakai untuk mempertajam logika backend proyekmu.

Tips UX/UI untuk Single Page:
Gunakan navigasi Smooth Scrolling (Anchor Links). Saat pengguna mengklik menu "Projects" di bagian atas (navigasi), halaman tidak berpindah (loading), melainkan langsung meluncur mulus ke bagian bawah yang berisi proyekmu.

Sekarang secara struktur UI sudah terbayang. Rencananya, di mana kamu akan melakukan hosting portofolio ini agar mudah diakses oleh rekruter secara gratis?]

## Prompt 5
[Bagaimana beda dari candidate lain?]

## AI Response 5
[Ini adalah pertanyaan paling krusial yang ditanyakan oleh semua fresh graduate. Mayoritas portofolio junior backend developer terlihat persis sama: berisi daftar teknologi (Java, MySQL, dll.) dan satu atau dua proyek To-Do List atau CRUD (Create, Read, Update, Delete) biasa.

Sebagai konsultan UX/UI, saran saya untuk membuatmu stand out bukan dengan menambah animasi visual yang rumit, melainkan merombak strategi konten dan cara kamu mengomunikasikan karyamu.

Berikut adalah taktik untuk membuatmu berbeda dari kandidat lain:

1. Gunakan Copywriting yang "Menjual" Kode
Kebanyakan developer menulis deskripsi proyek dengan bahasa teknis yang kaku dan membosankan. Kamu bisa mengambil pendekatan yang jauh lebih agresif dan menarik. Gunakan hook di awal deskripsi proyekmu yang langsung menyoroti nilai bisnisnya.

Biasa: "Membuat REST API menggunakan Golang dan MySQL."

Stand Out: "Membangun sistem backend yang memastikan tidak ada pesanan double saat terjadi lonjakan traffic, menggunakan Golang dan MySQL."

Jadikan deskripsi proyekmu sebagai "etalase" yang persuasif, bukan sekadar buku manual teknis.

2. Tampilkan Logika Bisnis Dunia Nyata (Bukan Sekadar Teknis)
Perusahaan—baik Startup maupun Corporate—mencari developer yang mengerti bahwa kode diciptakan untuk menyelesaikan masalah bisnis. Tampilkan proyek API yang menyentuh urat nadi operasional perusahaan.

Misalnya, buatlah proyek backend yang mengatur manajemen inventaris gudang, sistem checkout dengan kalkulasi ongkos kirim yang dinamis, atau otomatisasi penanganan keluhan dan refund pelanggan. Ketika rekruter melihat kamu bisa merancang arsitektur untuk masalah logistik atau e-commerce yang nyata, nilai jualmu langsung meroket dibandingkan kandidat yang hanya membuat aplikasi cuaca.

3. Tunjukkan Ketajaman Analisis Data
Sebagai developer spesialis Java dan Python, logika pemrosesan data adalah senjata utamamu. Jangan hanya menampilkan API penyimpan data sederhana.

Tonjolkan proyek yang melibatkan kalkulasi kompleks, pemetaan titik harga, analisis struktur data yang dinamis (seperti zona supply dan demand), atau kalkulasi finansial. Kemampuan untuk mengolah angka dan metrik yang fluktuatif akan memperlihatkan bahwa logika pemrogramanmu sangat solid dan tajam.

4. Eksekusi Elemen Unik (API Card)
Seperti yang kita bahas sebelumnya, letakkan elemen visual berupa JSON Response di hero section portofoliomu. Sementara kandidat lain menulis paragraf "Halo, saya fresh graduate yang rajin...", kamu langsung memberikan representasi visual dari keahlian utamamu di detik pertama rekruter membuka situsmu.

Dengan menggabungkan tampilan antarmuka (UI) yang bersih, tipografi Inter yang solid, dan strategi konten yang berfokus pada penyelesaian masalah bisnis, portofoliomu tidak akan terlihat seperti buatan "anak magang", melainkan seperti karya seorang profesional muda.

Untuk mulai menyusun portofolio single page ini, dari semua proyek yang pernah kamu kerjakan atau pelajari, proyek apa yang menurutmu paling kuat untuk diposisikan sebagai "Proyek Utama" di urutan teratas?]

## Key Decisions

| Decision | Value   | Why |
|----------|---------|-----|
| Color | Blue/White OR Dark/Neon | Biru memancarkan *trust* dan stabilitas (*Corporate*), sementara Gelap/Neon menunjukkan *agility* dan modernitas (*Startup*). |
| Typography| Poppins (Heading), Inter (Body), Fira Code (Tech Stack) | Poppins memberi kesan pertama yang ramah. Inter memastikan *readability* di layar *mobile*. Fira Code mempertegas identitas teknis. |
| Layout | Single Page (One-Pager) dengan *Smooth Scrolling* | Mematuhi "Hukum 6 Detik" rekruter. *Scrolling* lebih natural di *smartphone* dan menghindari kesan "ruang kosong" di portofolio. |
| Style | "API Response Card" & Business-Driven Copywriting | Visualisasi JSON di *hero section* cerdas dan *relatable* bagi orang IT. *Copywriting* berfokus pada solusi bisnis, bukan sekadar bahasa teknis. |

---

## Minimum Requirements

- ✅ Minimal 3 prompts
- ✅ 3+ decisions documented
- ✅ Reasoning untuk setiap decision
