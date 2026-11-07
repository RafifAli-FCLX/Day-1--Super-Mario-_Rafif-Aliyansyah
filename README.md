# Dokumentasi Workshop Day 1 - HIMATIK

**Nama:** Rafif Aliyansyah  
**Kelompok:** Super Mario (06)  

---

## Deskripsi Repository
Repo ini dibuat buat menampung seluruh berkas, catatan, dan dokumentasi tugas selama ngerjain misi praktikum di Workshop Day 1 HIMATIK. Selain buat tempat penyimpanan, repo ini juga jadi sarana latihan langsung dalam nerapin *version control* pakai Git dan GitHub.

---

## Tujuan Repository
* Mengumpulkan tugas misi individu Day 1 sesuai arahan panitia.
* Mempraktikkan alur kerja Git dan GitHub langsung di direktori proyek.
* Punya catatan pembelajaran yang rapi dan bisa diakses publik secara online.

---

## Dokumentasi Kegiatan Workshop (Day 1)

### 1. Rangkuman Materi Workshop
Di sesi Day 1 ini, pembahasan terbagi ke beberapa topik utama:

* **Prompt Engineering AI:**
  * Bahas teknis merancang prompt biar jawaban dari AI presisi, enggak ngawur, dan langsung sesuai kebutuhan.
  * Formula prompt yang ideal harus mencakup: **Role** (peran AI), **Task** (tugas spesifik), **Context** (latar belakang masukan), dan **Format** (bentuk luaran yang diharapkan).
  * Pemakaian prompt yang terstruktur terbukti bikin hasil respon AI lebih terarah, terminimalisir dari bias, dan efisien.

* **Git & GitHub:**
  * **Git:** Tool *Distributed Version Control* lokal buat nyatet dan melacak setiap riwayat perubahan kode/file di komputer.
  * **Git Workflow:** Alur perpindahan berkas dari *Working Directory* (area edit), masuk ke *Staging Area* (penandaan file lewat `git add`), sampai resmi tersimpan ke *.git directory* pas di-`commit`.
  * **GitHub:** Platform cloud buat menyimpan repositori Git secara online supaya bisa diakses dan dikolaborasikan bareng tim.
  * **Setup & Command Dasar:** 
    * Set identitas awal pakai `git config --global user.name` dan `user.email`.
    * Perintah dasar repositori lokal: `git init`, `git add .`, dan `git commit -m "pesan"`.
    * Hubungin ke remote repo: `git remote add`, `git push origin main`, dan `git pull origin main`.
    * Setting autentikasi aman ke GitHub memanfaatkan SSH Key (Ed25519).

* **Tata Tertib & Prosedur Kampus:**
  * Aturan kedisiplinan mahasiswa PNJ, mulai dari etika pakaian, kerapian rambut pria, sampai norma akademik di lingkungan kampus.
  * SOP peminjaman ruang dan alat di laboratorium (baik buat pemakaian di lab maupun dipinjam bawa pulang).
  * Alur dan tahapan penanganan sanksi kalau ada pelanggaran tata tertib.

---

### 2. Poin-Poin Penting & Pengetahuan Baru
* **Pengaruh Context di Prompting:** Makin jelas konteks dan batasan (*constraints*) yang dikasih ke AI, hasil kodenya bakal jauh lebih terstruktur dan minim bug dibanding cuma ngasih perintah umum.
* **Beda Git vs GitHub:** Git itu *tools*-nya yang jalan di lokal buat nyatet riwayat berkas, sedangkan GitHub itu wadah/platform *online*-nya.
* **Fungsi Staging Area:** File yang diubah ga langsung kesimpan permanen di riwayat proyek sebelum dimasukkan dulu ke staging area lewat `git add`.
* **Koneksi SSH Key:** Bikin proses *push* dan *pull* ke GitHub jauh lebih praktis dan aman dibanding ketik password berulang kali.

---

### 3. Pendapat Pribadi Tentang Day 1 Proyek Workshop
Materi Day 1 ini daging banget buat dasar anak informatika. Sesi prompt engineering ngebuka insight gimana cara manfaatin AI secara maksimal buat bantu nugas tanpa asal copas. Terus praktikum Git & GitHub-nya langsung ngelatih *mindset* kerja standar industri, mulai dari racik repo lokal sampai koneksi SSH ke GitHub.
