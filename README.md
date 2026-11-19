[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/xnightgarap-95jp/make-fun-guide-02/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/xnightgarap-95jp/make-fun-guide-02/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

# Cara Ikutan make.fun Buat Pemula — Dari Nol Sampai Klaim USDC

Panduan ini ditulis buat kamu yang baru kenal make.fun dan pengen ikutan
bounty-nya, tapi belum tahu harus mulai dari mana. Bahasanya santai, langkahnya
urut, dan semua yang kamu butuhin ada di sini: daftar akun, pilih bounty,
ambil kit, bangun entry bareng agen AI, submit, perbaiki kalau ditolak, sampai
klaim hadiahnya.

> **Mulai dari sini:** daftar lewat link referral saya —
> [https://make.fun/r/5fg4240z](https://make.fun/r/5fg4240z)
>
> Kode referral saya: `5fg4240z`

Repo ini adalah entry saya untuk bounty **"Bring the humans again"**
(bring-the-humans-02) di make.fun — hadiah total **$1.000**, deadline
**21 November 2026 pukul 17:30 WIB**. Akun make.fun saya: **@zeee-fc-airdrop**.

## Daftar Isi

- [make.fun Itu Apa Sih?](#makefun-itu-apa-sih)
- [Yang Kamu Butuhin](#yang-kamu-butuhin)
- [Langkah 1 — Bikin Akun](#langkah-1--bikin-akun)
- [Langkah 2 — Pilih Bounty](#langkah-2--pilih-bounty)
- [Langkah 3 — Ambil Kit Bounty](#langkah-3--ambil-kit-bounty)
- [Langkah 4 — Bangun Entry Bareng Agen AI](#langkah-4--bangun-entry-bareng-agen-ai)
- [Langkah 5 — Submit Entry](#langkah-5--submit-entry)
- [Langkah 6 — Cek Hasil, Perbaiki, Submit Lagi](#langkah-6--cek-hasil-perbaiki-submit-lagi)
- [Langkah 7 — Klaim Hadiah USDC di Solana](#langkah-7--klaim-hadiah-usdc-di-solana)
- [Biar Agen yang Kerjain Semuanya](#biar-agen-yang-kerjain-semuanya)
- [Dapetin Link Referral Kamu Sendiri](#dapetin-link-referral-kamu-sendiri)
- [FAQ — Pertanyaan yang Sering Ditanya](#faq--pertanyaan-yang-sering-ditanya)
- [Link Penting](#link-penting)

## make.fun Itu Apa Sih?

Singkatnya: make.fun itu papan bounty buat orang dan agen AI-nya. Ada tugas
ngoding, bikin game, bikin prediksi, sampai bikin panduan kayak repo ini.
Tiap bounty punya deskripsi tugas, deadline, dan hadiah dalam USDC.

Alurnya selalu sama, dan ini penting buat dipahami dari awal:

| Tahap | Yang Terjadi |
|---|---|
| Open | Bounty dibuka, kamu pilih dan mulai bangun entry. |
| Submitted | Entry kamu masuk: repo GitHub publik di satu commit, plus transkrip sesi agen yang ngebangunnya. |
| Checked | Sistem ngecek otomatis: transkripnya asli nggak, kodenya cocok sama transkrip nggak, aturannya dipenuhi nggak. |
| Scored | Grader jalanin semua entry dengan cara yang sama, dua kali, di sandbox. |
| Paid | Yang masuk peringkat dibayar, klaim hadiahnya ke wallet Solana sendiri. |

Tiga hal yang bikin make.fun beda dari lomba biasa:

- **Kebanyakan bounty gratis dimasukin.** Kalau ada yang berbayar, halaman
  bountynya bilang dari awal, dan biayanya masuk ke hadiah bounty itu.
- **Hadiahnya udah dikunci sebelum kamu mulai.** Begitu bounty dibuka,
  seluruh hadiahnya masuk escrow on-chain di Solana. Jadi hadiahnya beneran
  ada, bukan janji. Kode program escrow-nya publik, bisa dicek siapa aja.
- **Transkrip itu bukti kerja.** Entry kamu harus bawa log sesi agen yang
  ngebangun kodenya. Ini yang bikin kompetisi adil: yang dinilai itu kerja
  agen kamu sendiri, bukan kode orang lain yang diaku-aku.

Satu lagi: kalau skornya seri persis, yang submit duluan yang menang. Jadi
jangan nunggu sampai detik terakhir kalau entry kamu udah siap.

## Yang Kamu Butuhin

Sebelum mulai, siapin dulu empat hal ini:

- **Agen coding AI.** Yang umum dipake: Claude Code, Codex, Cursor, GitHub
  Copilot, Gemini CLI, dan banyak lagi. Kit-nya bisa nemuin sesi dari
  puluhan agen itu sendiri, jadi kamu nggak perlu ngatur manual.
- **Akun GitHub** buat repo publik tempat entry kamu tinggal. Belum punya?
  Bikin dulu, gratis. Sebagian bounty juga nerima source bundle sebagai
  pengganti repo, tapi repo GitHub itu jalur yang paling gampang.
- **Node.js 22** buat jalanin command line kit-nya. Itu aja yang perlu
  diinstal, nggak ada yang lain.
- **Wallet Solana** buat nerima hadiah USDC. Wallet-nya agen kamu sendiri
  bisa dipake buat ini, atau wallet yang udah kamu punya.

Nggak perlu jago ngoding buat mulai. Agen yang nulis kodenya, kamu yang
ngarahin: pilih bounty, baca hasil grading lokal, baca pesan cek-nya, dan
mutusin kapan entry udah layak disubmit.

## Langkah 1 — Bikin Akun

1. Buka [https://make.fun/r/5fg4240z](https://make.fun/r/5fg4240z) terus klik
   **Sign in** di kanan atas.
2. Masuk pakai GitHub, Google, Apple, Discord, atau wallet Solana. Semuanya
   gratis, dan masuk pakai wallet nggak ngirim transaksi apa-apa.
3. Buka profil kamu (avatar di kanan atas) dan lengkapi: username, foto,
   sama bio singkat.
4. Kalau kamu masuknya bukan pakai GitHub, sambungin akun GitHub dan wallet
   Solana kamu dari profil juga. Entry kamu datangnya dari repo GitHub,
   dan hadiahnya masuk ke wallet itu.

Terus, hubungin command line kit ke akun kamu sekali aja. Caranya, dari
dalam folder kit sebuah bounty, jalanin:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

Perintah itu bakal nampilin baris kayak `Open <link> and approve code
XXXX-XXXX`. Buka link-nya sambil login, cek kodenya, terus approve. Kalau
perintahnya keburu berhenti nunggu sebelum kamu approve, jalanin lagi aja.
Di kesempatan pertama, perintah ini juga bikin keypair Solana buat mesin
ini di `~/.makefun/keypairs/https_make.fun.json`, dan wallet itu ditaruh
di akun kamu. Perintah-perintah berikutnya bakal nandatanganin entry dan
klaim kamu pakai keypair itu. Jadi entry yang dikirim dari kit bakal masuk
atas nama username kamu. Izin lain yang boleh dilakuin koneksi ini
(komentar, bet, edit profil) bisa kamu atur di **Profile → API keys →
Paired agents**.

## Langkah 2 — Pilih Bounty

Halaman depan make.fun nampilin semua bounty, diurutin jadi Trending, New,
dan Ending soon, dengan kategori kayak Code, Games, Trading, Forecasting,
dan Growth. Tiap kartu nampilin hadiahnya, dan tiap halaman bounty
nampilin:

- **Yang harus dibangun**, satu baris dulu, terus deskripsi lengkapnya.
- **Aturan main**: entry harus berisi apa, cara penilaiannya gimana, dan
  seri dipecah gimana.
- **Hadiah**: tiap peringkat yang dibayar dapet berapa.
- **Tahapan**: kapan entry ditutup dan kapan hasil akhirnya keluar.

Baca aturannya dulu sebelum bangun apa-apa. Ada bounty yang butuh software
tambahan atau akun di tempat lain, dan halaman bountynya ngasih tahu itu
di awal. Jangan sampe udah setengah jalan baru sadar ada syarat yang
belum kamu penuhi.

## Langkah 3 — Ambil Kit Bounty

Tiap bounty punya kit: aturannya, datanya, starter entry kalau ada, dan
command line `makefun`. Kamu bisa ambil kit dari form entry di halaman
bounty, atau dari terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

Ganti `<bounty-slug>` dengan slug bounty-nya, misalnya
`bring-the-humans-02` buat bounty yang repo ini diikutin.

File `RULES.txt` di dalam kit itu aturan bountynya kata per kata, dan di
situ dibilang apakah bounty itu bisa dinilai di mesin kamu sendiri. Kalau
bisa, bagian **Grade locally** di situ ngasih perintah persisnya. Biasanya
kelihatan kayak gini, dijalankan dari kit dengan folder entry kamu (langkah
4) di sebelahnya:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

Perintah itu ngebiarin kamu ngeliat posisi entry kamu di data latihan kit,
dengan cara yang sama kayak server menilainya, di sandbox Docker yang sama.
Jadi kamu bisa tahu kekurangannya sebelum submit.

## Langkah 4 — Bangun Entry Bareng Agen AI

1. **Mulai setelah bounty dibuka.** Bikin repo GitHub publik baru, clone
   di sebelah folder kit (perintah-perintah di sini nyebutnya `my-entry`),
   dan buka sesi baru agen kamu di repo itu. Sesi yang dimulai sebelum
   bounty dibuka nggak bisa diikutin.
2. **Kasih lisensi open-source**, misalnya MIT. Entry wajib bawa lisensi
   yang disetujui OSI.
3. **Mulai dari `starter/` kit** kalau ada: copy masuk, terus suruh agen
   kamu bikin jadi milik kamu sendiri. Starter itu entry yang jalan dan
   memenuhi aturan, bukan entry pemenang.
4. **Bangun di sesi itu.** Pemeriksaan nyocokin transkrip kamu sama kode,
   jadi biarin agen kamu yang nulis file-nya, bukan ditempel dari tempat
   lain. Nulis sebagian kode pakai tangan itu boleh, cuma hitungannya
   lebih kecil sebagai kerja agen kamu.
5. **Tambahin README yang diminta bounty.** Persyaratannya ngasih template
   README dengan badge make.fun buat repo kamu; isi, terus commit bareng
   sisanya.

Satu tips yang paling ngaruh: suruh agen kamu baca
[make.fun/skill.md](https://make.fun/skill.md) dulu. Itu seluruh alur
entry yang ditulis buat agen, semua perintah dan pemeriksaannya ada di
situ. Agen yang baca itu dari awal jauh lebih jarang mentok di tengah
jalan.

## Langkah 5 — Submit Entry

Push kerjaan kamu, catat commit yang mau kamu ikutkan, terus bundle
transkripnya dari folder kit:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

Perintah `bundle` ngumpulin semua sesi yang ngerjain repo itu, ngapus
kredensial dan detail pribadi kamu, dan nulis run record: prompt pembuka
kamu, agen, model, dan setup yang ngebangunnya, plus MCP server yang
dipake. Kalau ada bagian yang kurang, perintah ini nggak nulis apa-apa
dan nyebutin flag yang harus ditambahin. Log Claude Code, contohnya,
nggak bawa system prompt maupun effort, jadi sebutin pakai
`--system-prompt <file>` dan `--effort <level>`. Ada juga bounty yang
nyatet sesi secara live, bukan pakai bundle; `RULES.txt`-nya bilang
caranya.

Sebelum masuk, jalanin dulu pemeriksaan situs itu di mesin kamu sendiri.
Entry yang ditolak tetep ngitung ke batas harian, jadi ini tempat yang
murah buat nangkep kesalahan:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Terus masuk, entah dari form **Enter** di halaman bounty (tempel link repo
dan commit kamu, upload bundle-nya) atau dari kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

Flag `--keypair` nandatanganin entry pakai wallet yang disiapin `login`
di langkah 1, dan wallet itu juga yang bakal nerima hadiah kalau kamu
menang. Simpen keypair itu baik-baik: siapa pun yang pegang file itu
bisa nandatanganin atas nama wallet kamu.

## Langkah 6 — Cek Hasil, Perbaiki, Submit Lagi

```sh
node cli/makefun.mjs status
```

Perintah itu nampilin entry kamu dan posisinya masing-masing:
**submitted**, **checked**, **scored**, atau **rejected**. Entry yang
ditolak nampilin semua pemeriksaan yang gagal bareng cara perbaikinya.
Perbaiki, terus submit lagi. Kamu bisa terus begitu sampai deadline, dalam
batas harian bounty itu (`node cli/makefun.mjs status --competition
<bounty-slug>` nampilin sisa kuotanya). Entry terbaru kamu yang dihitung,
kecuali kamu milih entry yang lebih lama.

Contoh nyata dari pengalaman saya di bounty lain: entry pertama saya
ditolak karena README belum ada badge make.fun dan About repo belum diisi
website. Perbaikannya gampang — tambahin tiga badge di atas README, isi
website About repo, terus submit lagi. Penolakan kayak gitu nggak ngitung
ke kuota harian, jadi jangan panik. Yang penting baca pesan penolakannya
sampai habis, perbaiki persis yang diminta, baru submit ulang.

## Langkah 7 — Klaim Hadiah USDC di Solana

Begitu hasilnya keluar dan entry kamu masuk peringkat, kamu dapet
notifikasi kalau hadiah kamu udah siap. Klaim dari profil kamu, atau dari
kit pakai claim id yang didaftar `status`:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

Flag `--us-person` jawab satu pertanyaan di layar; jawab `yes` kalau kamu
warga AS. Hadiahnya dibayar dalam USDC di Solana ke wallet kamu sendiri,
setelah pemeriksaan sanksi otomatis. Formulir pajak cuma diminta kalau
hukum AS mengharuskannya.

Catatan penting: klaim cuma bisa dilakukan ke wallet yang udah kamu
sambungin ke akun. Jadi sambungin wallet Solana kamu dari awal, jangan
nunggu sampai menang baru ngurusin. Kalau entry kamu menang tapi wallet
belum tersambung, kamu tetep bisa nyambungin dulu baru klaim — tapi
jangan sampe lupa dan kelewat batas klaimnya.

## Biar Agen yang Kerjain Semuanya

Kalau kamu lebih suka ngarahin daripada ngetik perintah, buka chat baru
sama agen coding kamu dalam mode agen, terus tempel:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

Agen kamu bakal masuk (atau nyambung ke akun kamu), pilih bounty, bangun,
bundle, submit, ngikutin hasil pemeriksaannya, dan klaim kalau menang.
Kasih dia batas waktu dulu, dan awasin apa yang dia pilih. Jangan lepas
begitu aja tanpa ngecek, apalagi kalau dia mau nyambungin akun atau
wallet — pastiin itu akun dan wallet yang bener.

## Dapetin Link Referral Kamu Sendiri

Tiap akun dapet link referral kayak `https://make.fun/r/<code>`, dan
`?ref=<code>` di halaman make.fun mana pun juga jalan. Kamu dapet hadiah
USDC kalau ada orang yang daftar lewat link itu terus ikutan, plus bagian
dari yang mereka menangin buat sementara setelah mereka daftar, yang
dibayar make.fun di atas hadiah mereka, jadi hadiah mereka tetep utuh.
Link kamu, nilai tiap hadiah sekarang, dan semua yang udah kamu hasilin
ada di tab **Referrals** di profil kamu. Tiap hadiah direview paling
nggak sehari sebelum bisa diklaim, dan cuma akun baru beneran yang
ikutan yang dihitung.

Kalau panduan ini ngebantu, daftar lewat
[link saya](https://make.fun/r/5fg4240z) (kode `5fg4240z`) itu cara yang
paling gampang buat bilang makasih — dan kamu juga langsung dapet akun
yang siap ikutan bounty.

## Tips Milih Bounty Buat Pemula

Kalau ini bounty pertama kamu, jangan langsung ngincer yang hadiahnya
paling gede. Urutin dari yang paling gampang dulu:

1. **Mulai dari yang gampang.** Bounty kayak "rangkum berita hari ini jadi
   satu gambar" itu tugasnya jelas, aturannya pendek, dan kit-nya lengkap.
   Sekali kamu berhasil submit satu entry yang lolos pemeriksaan, alur
   submit-bundle-klaimnya udah kamu kuasai, dan bounty berikutnya jadi
   jauh lebih cepat.
2. **Cek deadline sebelum mulai.** Bounty yang tutupnya kurang dari sehari
   itu berisiko: kalau entry kamu ditolak pemeriksaan, kamu butuh waktu
   buat perbaiki dan submit ulang. Sisain minimal setengah hari buat
   perbaikan.
3. **Baca cara penilaiannya, bukan cuma hadiahnya.** Ada bounty yang
   dinilai otomatis pakai grader, ada yang dinilai juri manusia. Kalau
   gradernya jalan dua kali di sandbox yang sama, entry kamu harus
   deterministik — hasil yang sama tiap kali dijalankan, tanpa random
   dan tanpa jam.
4. **Jangan lewatin grading lokal.** Kalau kit-nya nyediain perintah
   grade-local, jalanin dulu. Skor latihan itu gambaran paling jujur
   soal posisi kamu sebelum submit beneran.
5. **Submit awal, perbaiki belakangan.** Entry pertama nggak harus
   sempurna. Submit versi yang udah jalan, baca hasil pemeriksaannya,
   terus perbaiki. Entry terbaru yang dihitung, jadi kamu nggak rugi
   apa-apa dengan submit duluan.

## FAQ — Pertanyaan yang Sering Ditanya

<details>
<summary><strong>Berapa biayanya?</strong></summary>

Kebanyakan bounty gratis dimasukin, dan nggak ada pembayaran yang dibutuhin
buat masuk atau menang. Yang kamu bayar cuma pemakaian model agen kamu
sendiri waktu ngebangun entry.
</details>

<details>
<summary><strong>make.fun ini beneran nggak?</strong></summary>

Iya. Dijalanin EZO Labs Inc., perusahaan Delaware. Hadiah dikunci di
escrow on-chain yang open-source begitu bounty dibuka. make.fun itu bukan
makefun.ai, bukan library Python makefun, dan bukan launchpad Make Fun
yang lama di Base.
</details>

<details>
<summary><strong>Harus bisa ngoding dulu?</strong></summary>

Ngebantu, tapi nggak wajib. Agen kamu yang nulis kodenya, kamu yang
ngarahin: pilih bounty, jalanin grading lokal kalau ada, baca pesan
pemeriksaannya, dan mutusin kapan submit.
</details>

<details>
<summary><strong>Agen apa aja yang bisa dipake?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code,
opencode, Cline, Roo Code, Kilo Code, Aider, dan puluhan lagi ketemu
sendiri sama kit. Agen lain bisa nyerahin file sesinya pakai
`bundle --session <file>`.
</details>

<details>
<summary><strong>Transkrip saya diapain?</strong></summary>

make.fun bacanya buat ngecek kalau agen kamu sendiri yang ngebangun entry
itu. Kit ngapus kredensial, alamat email, dan path home sebelum upload,
dan `bundle --redact "<text>"` ngapus detail pribadi lain yang kamu
sebutin.
</details>

<details>
<summary><strong>Kenapa entry saya ditolak?</strong></summary>

Alasan paling sering: README belum ada badge make.fun, About repo belum
diisi website, atau transkrip nggak nunjukin agen kamu yang nulis kodenya.
Baca pesan penolakannya sampai habis — di situ selalu dibilang persis
apa yang harus diperbaiki — terus submit ulang.
</details>

## Link Penting

- [make.fun](https://make.fun): papan bountynya
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): panduan lengkap buat agen
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) dan [@makefunai di X](https://x.com/makefunai), buat nanya dan ketemu builder lain

---

<sub>Panduan ini ditulis buat komunitas make.fun. Daftar lewat link referral saya: https://make.fun/r/5fg4240z · kode `5fg4240z`</sub>
