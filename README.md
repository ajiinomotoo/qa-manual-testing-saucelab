# Manual QA Testing Portfolio – SauceDemo

## Project Overview

Project ini merupakan latihan **Manual Software Testing** yang dilakukan pada website demo e-commerce SauceDemo.
Tujuan dari pengujian ini adalah untuk memverifikasi apakah fitur utama aplikasi berjalan sesuai dengan yang diharapkan serta untuk mengidentifikasi potensi bug pada sistem.

Website yang diuji:
https://www.saucedemo.com

---

## Testing Scope

Pengujian difokuskan pada fitur utama aplikasi e-commerce berikut:

* Login
* Product List
* Add to Cart
* Cart Page
* Checkout Flow

---

## Testing Types

Jenis pengujian yang dilakukan pada project ini:

* Positive Testing
* Negative Testing
* Functional Testing
* Validation Testing
* UI Behaviour Testing
* Navigation Testing

---

## Test Documentation

Dokumentasi pengujian yang tersedia pada repository ini meliputi:

* **Test Plan**
  Menjelaskan tujuan pengujian, scope testing, environment, serta deliverables.

* **Test Scenario**
  Berisi daftar skenario pengujian berdasarkan fitur yang diuji.

* **Test Case**
  Berisi langkah-langkah pengujian, test data, expected result, dan actual result.

* **Bug Report**
  Dokumentasi bug yang ditemukan selama proses testing.

* **Test Summary Report**
  Ringkasan hasil pengujian yang mencakup jumlah test case, hasil eksekusi, dan kesimpulan testing.

---

## Test Execution Result

| Metric              | Result |
| ------------------- | ------ |
| Total Test Scenario | 13     |
| Total Test Case     | 13     |
| Test Case Passed    | 12     |
| Test Case Failed    | 1      |
| Defects Found       | 1      |

---

## Defect Found

Selama proses testing ditemukan satu bug pada fitur checkout.

**Bug Title:**
User dapat memulai proses checkout meskipun cart kosong.

**Deskripsi:**
Sistem tetap mengizinkan user mengakses halaman checkout meskipun tidak ada produk di dalam cart.

Bug evidence dapat dilihat pada folder:

```
bug_evidence
```

---

## Testing Environment

Browser:

```
Google Chrome
```

Operating System:

```
Windows
```

---

## Conclusion

Berdasarkan hasil pengujian, sebagian besar fitur utama seperti login, product list, add to cart, dan checkout berjalan sesuai dengan yang diharapkan.

Namun ditemukan satu bug pada fitur checkout yang memungkinkan user memulai proses checkout meskipun cart kosong.

---

## Author

Aji Nugroho

Mahasiswa Informatika

Manual QA Testing Portfolio
