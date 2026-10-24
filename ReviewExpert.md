# Review Expert: Naratologi dan Tokoh dalam Fiksi

| | |
|---|---|
| **Reviewer** | Te Uly, pengajar kelas *Fictional Studies* |
| **Bentuk** | Pesan tertulis kepada Abraar |
| **Dicatat** | 24 Oktober 2026 |
| **Contoh yang dipakai** | *Bartleby, the Scrivener*, Herman Melville |
| **PRD terkait** | 0.0 Index, 2.1 Reference Passage, 3.1 Symbols |

> Bagian "Apa kata expert" adalah ringkasan dari pesan beliau. Bagian "Dampak ke PRD" adalah pemetaan tim ke PRD yang ada. Semua yang ditandai **Saran** belum diputuskan.

---

## Ringkasan

Beliau melihat iRead membantu pembaca dengan afantasia menikmati fiksi dengan lebih mudah. Menurut beliau, ada tiga hal penting untuk pengembangan aplikasi:

1. **Mengenali tokoh yang sama** walaupun disebut dengan cara berbeda.
2. **Menghubungkan deskripsi dengan kalimat yang paling relevan**, bukan otomatis kalimat pertama atau yang paling lengkap.
3. **Membedakan informasi yang sudah diketahui pembaca** dari informasi yang masih sengaja dirahasiakan penulis.

Ketiganya berakar pada **naratologi**, yaitu kajian tentang bagaimana cerita disampaikan dan bagaimana informasi tentang tokoh dibangun lewat teks. Tujuannya: informasi tentang tokoh jadi lebih terstruktur dan mudah diakses, **tanpa mengurangi kesempatan pembaca menafsirkan cerita sendiri**.

---

## Insight 1: Satu tokoh, banyak sebutan

### Apa kata expert

- Penulis memperkenalkan tokoh lewat **nama, ciri fisik, tindakan, dialog, atau cara tokoh lain membicarakannya**.
- Setelah itu tokoh yang sama bisa disebut lewat **nama, julukan, ciri penampilan, atau perannya** dalam cerita.
- Aplikasi perlu mengenali bahwa sebutan-sebutan itu merujuk ke tokoh yang sama.
- **Contoh Bartleby:** ia disebut dengan namanya, dengan kata ganti *he*, atau dengan pekerjaannya sebagai *scrivener*. Tapi di kantor itu ada juru tulis lain, jadi tidak setiap kata *scrivener* berarti Bartleby. Sistem harus melihat konteks kalimat.
- **Kaitan dengan afantasia:** simbol yang konsisten di samping nama dan deskripsi membantu mengenali tokoh **tanpa harus terus-menerus mengingat gambaran tokoh** di kepala.

### Dampak ke PRD

| Poin | Status di PRD | Catatan |
|---|---|---|
| Simbol konsisten untuk mengenali tokoh | **Sejalan** dengan 3.1 Symbols (Goal 1) | Beliau menguatkan alasan fitur ini dari sisi pembaca afantasia. |
| Sebutan berdasarkan **peran** ("the scrivener") dan **julukan** | **Belum jelas** | Definisi metrik di 3.1 hanya menyebut *appearance-description phrases*. Perlu diputuskan apakah sebutan peran dan julukan ikut dicakup. |
| Tokoh dikenali lewat **tindakan dan dialog** | **Belum tercakup** | PRD lebih banyak membahas deskripsi penampilan. |
| Kata ganti (*he*) | **Dikecualikan** di 0.0 Index dan 2.1 Non-goals | Beliau menyebutnya sebagai salah satu cara menyebut tokoh. Ini bukan permintaan untuk memasukkannya, tapi perlu dicatat sebagai alasan kenapa dikecualikan. |
| Satu sebutan yang cocok untuk beberapa tokoh | **Sebagian tercakup**: 2.1 A2 (tidak digarisbawahi kalau ragu) dan risiko mismatch di 3.1 §9 | Contoh *scrivener* bagus dijadikan kasus uji ambiguitas. |

---

## Insight 2: Kalimat rujukan yang paling relevan

### Apa kata expert

- Kalimat rujukan terbaik **tidak selalu kalimat pertama** yang memperkenalkan tokoh, dan **tidak selalu yang paling panjang atau lengkap**.
- Yang penting adalah **kesesuaian antara deskripsi yang sedang dibaca dan bagian teks yang menjelaskannya**, sambil mempertimbangkan konteks cerita.
- **Contoh Bartleby:**
  - Pembaca mengetuk deskripsi penampilan Bartleby → arahkan ke bagian yang menggambarkan penampilannya.
  - Pembaca ingin memahami sikapnya yang sering menolak → arahkan ke adegan *"I would prefer not to."*
- **Peringatan:** menampilkan kalimat asli **tidak otomatis** membuat pembaca afantasia bisa membayangkan penampilan tokoh.

### Dampak ke PRD

| Poin | Status di PRD | Catatan |
|---|---|---|
| Rujukan = kalimat yang paling cocok dengan frasa, bukan yang pertama | **Sejalan** dengan 2.1 §5.1 "Which passage is shown" (context passage) dan definisi di 0.0 Index | Masukan beliau menguatkan keputusan yang sudah ada. |
| Rujukan untuk **sikap atau perilaku**, bukan hanya penampilan | **Belum tercakup** | Ranking di 2.1 berbasis deskripsi. Perlu diputuskan apakah frasa tentang sikap ("the one who refuses") bisa diketuk, dan ke mana arahnya. |
| Kalimat asli ≠ kemampuan membayangkan | **Perlu dijaga di klaim produk** | Sejalan dengan arah simbol: tujuannya *mengenali*, bukan *membayangkan*. **Saran:** pastikan Problem, Goals, dan metrik tidak mengklaim pembaca jadi bisa membayangkan tokoh. |

---

## Insight 3: Hormati yang sengaja disembunyikan penulis

### Apa kata expert

- Penulis kadang **sengaja tidak menjelaskan** sesuatu secara langsung. Identitas tokoh, ciri tertentu, atau hubungan antartokoh bisa dibuat samar untuk membangun **rasa penasaran dan kejutan**.
- Aplikasi sebaiknya membantu memahami cerita **tanpa terlalu cepat mengungkap** apa yang memang dirahasiakan.
- **Contoh Bartleby:** pembaca tahu apa yang Bartleby lakukan, tapi tidak mendapat jawaban pasti tentang alasannya. **Ketidakjelasan itu bagian penting dari pengalaman membaca.**
- Aplikasi sebaiknya menunjukkan informasi **yang memang ada di teks**, tanpa memberi **kesimpulan pasti** tentang motif yang terbuka untuk ditafsirkan.
- Aplikasi juga perlu memperhatikan **posisi pembaca** dalam cerita supaya tidak membocorkan bagian berikutnya.

### Dampak ke PRD

| Poin | Status di PRD | Catatan |
|---|---|---|
| Tidak membocorkan bagian yang belum dibaca | **Sejalan** dengan 2.1 §5.4 (anti-spoiler, termasuk story updates) dan keputusan "No spoilers" di 0.0 | |
| Tidak memberi kesimpulan atau tafsiran | **Sejalan** dengan 2.1 Goal 2: yang ditampilkan kalimat asli penulis, bukan ringkasan buatan AI | Beliau memberi alasan naratologis untuk keputusan ini. |
| Identitas tokoh yang sengaja disamarkan | **Celah di 3.1** | Simbol di frasa deskriptif bisa langsung membocorkan "ini tokoh X" sebelum penulis mengungkapnya. 3.1 §5.3 Anti-spoiler rules masih `[TBD]`. |
| Hubungan antartokoh yang disamarkan | **Perlu dijaga** untuk relation map (fitur terkait di 2.1) | 2.1 belum menampilkan relasi di kartu, tapi aturan ini perlu dibawa saat relation map dibuat. |
| Isi Symbol Pop up (3.2) | **Perlu dicek** | Info karakter di pop up harus mengikuti aturan yang sama. |

---

## Tindak lanjut yang disarankan

Semua poin di bawah adalah **Saran** dan perlu keputusan tim.

| # | Saran | PRD |
|---|---|---|
| 1 | Isi aturan anti-spoiler simbol: simbol di frasa deskriptif hanya muncul kalau hubungan frasa itu dengan tokohnya sudah terungkap pada atau sebelum posisi baca | 3.1 §5.3 |
| 2 | Putuskan cakupan sebutan: penampilan saja, atau juga peran, julukan, dan sikap | 3.1 §1, §4.3; 2.1 §5.1 |
| 3 | Tambahkan kasus ambiguitas "satu sebutan, beberapa tokoh" (contoh *scrivener*) ke golden set dan test case | 2.1 §4.3, §8; 3.1 §4.3, §8 |
| 4 | Pertimbangkan *Bartleby, the Scrivener* sebagai salah satu buku uji: pendek, domain publik, dan sudah dipakai beliau untuk mengajar | 3.1 §4.3 (golden set masih `[TBD]`) |
| 5 | Jaga klaim produk: fitur membantu **mengenali** tokoh, bukan **membayangkan** tokoh | 3.1 §2, §3 |
| 6 | Catat naratologi sebagai dasar desain di Background | 0.0 §2 |

---

## Pertanyaan lanjutan untuk Te Uly (Saran)

- Untuk tokoh yang identitasnya baru diungkap belakangan, apakah simbol sebaiknya tidak muncul sama sekali, atau muncul sebagai simbol "tokoh belum dikenal"?
- Selain *Bartleby*, apakah ada cerita lain di kelas *Fictional Studies* yang cocok untuk menguji tokoh yang disebut dengan banyak cara?
- Apakah beliau bersedia menjadi salah satu anotator golden set, atau mereview hasil anotasi?
