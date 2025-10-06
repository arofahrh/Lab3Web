# praktikum 3
        Nama  : Arofah Raudlatul Hasanah
        Kelas : TI.24.A2
        Nim   : 312410231
        
## Pertanyaan dan tugas :
### Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection.
### <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/e9bc4133-9cc3-445b-87f4-ca8d2960c880" />
### <img width="1916" height="919" alt="image" src="https://github.com/user-attachments/assets/45669107-0e0b-431b-91f6-0a0a06b9ae81" />
### Penjelasan
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

### Kesimpulan

* **Dropdown** digunakan untuk satu pilihan saja.
* **Listbox multiple** digunakan untuk lebih dari satu pilihan.
* Penambahan **CSS** membuat form lebih rapi dan menarik.
arik.

## Latihan
### **1. Membuat Ordered List**
<img width="1919" height="658" alt="image" src="https://github.com/user-attachments/assets/50747b96-5e45-4985-95d6-247e84f47475" />
<img width="1915" height="316" alt="image" src="https://github.com/user-attachments/assets/aa98c69f-9b56-4f11-a547-27187be338e1" />

### **2. Membuat Unorderd List**
<img width="1919" height="838" alt="image" src="https://github.com/user-attachments/assets/757ce5ef-5b4f-4bdd-b72f-f7e03ce78e74" />
<img width="1915" height="316" alt="image" src="https://github.com/user-attachments/assets/17b168bd-bd89-4274-8297-bc00b2b8852c" />

### **3. Membuat Description List**
<img width="1919" height="490" alt="image" src="https://github.com/user-attachments/assets/b2396b0b-550d-418b-9c58-9fdd98feb9b1" />
<img width="1914" height="315" alt="image" src="https://github.com/user-attachments/assets/614ca881-2294-42f1-879d-4a4fb6069a27" />

### **4. Membuat Tabel**
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a31143da-360d-43b7-9dfe-bb16862992a6" />
<img width="1919" height="338" alt="image" src="https://github.com/user-attachments/assets/28f83565-186f-4bf6-a083-2f96b32a5b8f" />

### **5. Mengatur Margin dan Padding
<img width="1919" height="905" alt="image" src="https://github.com/user-attachments/assets/1e40d753-39e5-47f6-9f52-184d18ac5175" />
<img width="1919" height="313" alt="image" src="https://github.com/user-attachments/assets/e20310cb-ec89-4b97-950f-ac2ca6b09c83" />

### **6. Menggabungkan Sel Data**
<img width="1919" height="962" alt="image" src="https://github.com/user-attachments/assets/f93e41ef-54b4-4890-a460-adf0906b3a71" />
<img width="1919" height="345" alt="image" src="https://github.com/user-attachments/assets/c3d0d747-e6c1-4fae-b1fe-31964c6abfda" />

### **7. Membuat Form**
<img width="1910" height="953" alt="image" src="https://github.com/user-attachments/assets/f2d47a7c-105f-424f-802a-c00c36f7ff02" />
<img width="1919" height="500" alt="image" src="https://github.com/user-attachments/assets/94898436-1625-4a7a-b4f0-ab464ea46ca1" />

### **8. Membuat Style Pada Form**
<img width="1915" height="1077" alt="image" src="https://github.com/user-attachments/assets/ff7e20ba-0411-4714-a018-95c297040bdd" />
<img width="1919" height="493" alt="image" src="https://github.com/user-attachments/assets/d59ede1d-31ff-4a4e-894e-213ac64f2e1c" />













