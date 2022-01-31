### Soal - 01

Jawablah pertanyaan di bawah ini

1. Apa itu synchronous?
2. Apa itu asynchronous?
3. Dapatkah kita menerapkan konsep asynchronous pada browser?
4. Ada berapa cara/metode untuk menghandle kode asynchronous? sebutkan!
5. Buatlah analisa terhadap kode dibawah ini!

```Javascript
console.log("perintah 1")

setTimeout(() => {
  console.log("perintah 2")
}, 0)

console.log("perintah 3")

// hasil
// perintah 1
// perintah 3
// perintah 2
```

---

### Soal - 02

Buatlah sebuah web yg dapat mengambil data API :

- https://api.github.com/users/YOUR_USERNAME
- https://digimon-api.vercel.app/api/digimon

Dengan ketentuan:

- Gunakan `fetch` untuk mengambil data dari API
- Gunakan metode `promise` dan `async await` pada masing-masing API
- Buat file yg berbeda untuk penggunaan `promise` dan `async await`, contoh:

```
tugas-asynchronous
- index.html         // terhubung ke promise.html dan async-await.html
- async-await.js     // ambil data digimon dan github menggunakan async-await
- async-await.html   // tampilan data dari hasil async-await
- promise.js         // ambil data digimon dan github menggunakan promise
- promise.html       // tampilan data dari hasil promise
```

- Cek data yg diambil menggunakan `console.log()`
- Tampilkan data menggunakan DOM
