# Mode Latihan Struktur Kode (Gaya Duolingo)

## Tipe Latihan
1. **Susun Kode**
   - Pengguna menyusun baris acak menjadi program valid.
2. **Lengkapi Sintaks**
   - Pengguna mengisi bagian kosong (`__`) pada kode C.
3. **Prediksi Output**
   - Pengguna menebak keluaran program.
4. **Perbaiki Bug**
   - Pengguna memperbaiki bug kecil dalam 1-3 baris.

## Mekanisme Gamifikasi
- XP per latihan benar.
- Combo streak untuk jawaban benar beruntun.
- Heart/lives berkurang jika salah.
- Unlock level berdasarkan akumulasi XP.

## Contoh Latihan
### A. Lengkapi Sintaks
```c
#include <stdio.h>
int main() {
    int n;
    scanf("%d", &n);
    if (n % 2 == 0) {
        printf("Genap\n");
    } else {
        printf("__\n");
    }
    return 0;
}
```
**Jawaban:** `Ganjil`

### B. Susun Kode
Urutkan potongan berikut agar program dapat mencetak bilangan 1-5:
- `for (int i = 1; i <= 5; i++)`
- `printf("%d\n", i);`
- `{`
- `}`
