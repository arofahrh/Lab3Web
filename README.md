# praktikum 3
## Pertanyaan dan tugas :
### Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
### <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/e9bc4133-9cc3-445b-87f4-ca8d2960c880" />
### <img width="1916" height="919" alt="image" src="https://github.com/user-attachments/assets/45669107-0e0b-431b-91f6-0a0a06b9ae81" />
### Penjelasan
## Penjelasan

Pada praktikum ini dibuat sebuah form HTML yang berisi dua jenis input, yaitu **dropdown menu** dan **listbox dengan multiple selection**.

### 1. Dropdown Menu

Dropdown dibuat menggunakan tag `<select>` tanpa atribut `multiple`.
Tujuannya agar user hanya bisa memilih satu pilihan saja.
Pada contoh, dropdown digunakan untuk memilih **Jurusan** dengan tiga pilihan:

* Teknik Informatika
* Sistem Informasi
* Rekayasa Perangkat Lunak

**Contoh kode:**

```html
<select name="jurusan" id="jurusan">
    <option value="TI">Teknik Informatika</option>
    <option value="SI">Sistem Informasi</option>
    <option value="RPL">Rekayasa Perangkat Lunak</option>
</select>
```

### 2. Listbox Multiple Selection

Listbox dibuat juga dengan tag `<select>`, tetapi ditambahkan atribut `multiple` dan `size`.
Dengan cara ini, user bisa memilih lebih dari satu opsi.
Pada contoh, listbox digunakan untuk memilih **Genre Film**:

* Action
* Comedy
* Drama
* Horror
* Romance
* Sci-Fi

**Contoh kode:**

```html
<select name="genre[]" id="genre" multiple size="6">
    <option value="action">Action</option>
    <option value="comedy">Comedy</option>
    <option value="drama">Drama</option>
    <option value="horror">Horror</option>
    <option value="romance">Romance</option>
    <option value="sci-fi">Sci-Fi</option>
</select>
```

### 3. Tampilan Form dengan CSS

Untuk mempercantik tampilan, ditambahkan style **CSS dengan tema warna coklat**.

* Background halaman dibuat coklat muda.
* Border dan tombol menggunakan warna coklat tua.
* Font warna gelap supaya mudah dibaca.

**Potongan CSS:**

```css
body {
    background-color: #f5f0eb;
    color: #4b2e2e;
}
input[type="submit"] {
    background-color: #8b4513;
    color: white;
}
```

---

## Kesimpulan

* **Dropdown** digunakan untuk satu pilihan saja.
* **Listbox multiple** digunakan untuk lebih dari satu pilihan.
* Penambahan **CSS** membuat form lebih rapi dan menarik.
arik.
