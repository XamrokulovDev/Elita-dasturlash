<details>
<summary>1. Bootstrapga kirish</summary>

## Bootstrapga kirish

### Bootstrap nima?

**Bootstrap** — bu **tayyor CSS va JavaScript komponentlari** to‘plami bo‘lib, u yordamida siz **zamonaviy, responsive (moslashuvchan)** veb-sahifalarni juda tez yaratishingiz mumkin.  
U **Twitter kompaniyasi** tomonidan ishlab chiqilgan va hozirda dunyodagi eng mashhur front-end frameworklardan biridir.

### Bootstrap nima uchun ishlatiladi?

Bootstrap yordamida siz:
- Saytni **tez va professional** tarzda yaratishingiz mumkin;
- **Responsive (moslashuvchan)** dizaynni avtomatik qo‘llaysiz;
- **Tayyor komponentlar** — tugmalar, kartalar, navbarlar, modallar, formalar va boshqalarni ishlatishingiz mumkin;
- Har bir sahifani **foydalanuvchi uchun qulay** va **bir xil ko‘rinishda** qilasiz.

### ⚙️ Bootstrapni ulash usullari

Bootstrap’ni saytingizga ulashning ikki usuli bor:

#### 1. **CDN orqali ulash (tavsiya etiladi)**

Eng oson usul — **Bootstrap CDN** (onlayn ulanish).  
Bu holda siz fayl yuklab olmasdan, internet orqali Bootstrapni ishlatasiz.

```html
<!-- Bootstrap CSS (boshi) -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap JS (ohiri, body ichida) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```
</details>

<details>
<summary>2. Tipografiya va ranglar</summary>

## Bootstrap: Tipografiya va ranglar

### 1. Tipografiya (Matn uslublari)

Bootstrap’da matn va sarlavhalar uchun **maxsus sinflar** mavjud.  
Ular matnni oson formatlash va responsive shriftlarni ishlatish imkonini beradi.

#### Sarlavha sinflari
Sarlavha teglari `<h1>`–`<h6>` bilan bir qatorda, `.h1`–`.h6` sinflari orqali ham ishlatiladi.

```html
<h1 class="h1">Sarlavha 1</h1>
<p class="h2">Sarlavha 2</p>
<p class="h3">Sarlavha 3</p>
```

👉 `.h1` va `<h1>` bir xil o‘lchamda chiqadi, lekin `.h1`ni siz har qanday tegga qo‘llay olasiz (masalan `<p>` yoki `<div>`).

**`.lead`**
Matnni biroz kattaroq va o‘qilishi osonroq qiladi — odatda kirish paragrafi uchun ishlatiladi.

```html
<p class="lead">
```
Bu asosiy matndan biroz kattaroq va e’tiborni tortuvchi paragraf.`</p>`

**Matn hizalash `(alignment)`**

```html
<p class="text-start">Chapga hizalangan</p>
<p class="text-center">O‘rtaga hizalangan</p>
<p class="text-end">O‘ngga hizalangan</p>
```

### Matn formatlash

| Klass | Tavsif |
|--------|--------|
| `fw-bold` | Qalin matn |
| `fw-semibold` | O‘rtacha qalin |
| `fw-light` | Ingichka shrift |
| `text-uppercase` | Hamma harf KATTA bilan |
| `text-lowercase` | Hamma harf kichik bilan |
| `text-capitalize` | Har bir so‘zning bosh harfi katta |

**Misol:**

```html
<p class="fw-bold text-uppercase">Bootstrap Matn Uslublari</p>
```

### 2. Rang sinflari

Bootstrap’da matn va fon uchun oldindan belgilangan rang sinflari mavjud.
Bu ranglar brand ranglari deb ataladi.

**`Matn ranglari`**

```html
<p class="text-primary">Asosiy (ko‘k) rang</p>
<p class="text-success">Muvaffaqiyat (yashil)</p>
<p class="text-danger">Xato (qizil)</p>
<p class="text-warning">Ogohlantirish (sariq)</p>
<p class="text-info">Axborot (ko‘k-och)</p>
<p class="text-muted">So‘nuk kulrang matn</p>
```

**`Fon ranglari`**

```html
<div class="bg-primary text-white p-2">Ko‘k fon</div>
<div class="bg-success text-white p-2">Yashil fon</div>
<div class="bg-warning text-dark p-2">Sariq fon</div>
```

### Ranglar ro‘yxati

| Rang nomi | Tavsif |
|------------|--------|
| `primary` | Asosiy rang (ko‘k) |
| `secondary` | Qo‘shimcha rang (kulrang) |
| `success` | Muvaffaqiyat (yashil) |
| `danger` | Xato (qizil) |
| `warning` | Ogohlantirish (sariq) |
| `info` | Axborot (ko‘k-och) |
| `light` | Oq rangga yaqin fon |
| `dark` | Qora rangga yaqin fon |
| `muted` | So‘nuk matn rangi |

**Amaliyot: “Maktab yangiliklari” sahifasini yasash**

</details>