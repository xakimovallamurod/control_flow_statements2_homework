# elif operatori bilan ishlash

## if01

Allamurodning uch oylik daromadi berilgan. `max()` funksiyasidan foydalanmasdan eng katta daromadni qaytaring.

**Misol 1:**

```Python
Kirish: a=6500000, b=7200000, c=6800000
Chiqarish: 7200000
```

**Misol 2:**

```Python
Kirish: a=-5, b=-3, c=-1
Chiqarish: -1
```

---

## if02

Allamurodning yoshi va akasining yoshi berilgan. Agar ular teng bo'lsa 0, aks holda kattasini qaytaring.

**Misol 1:**

```Python
Kirish: a=26, b=29
Chiqarish: 29
```

**Misol 2:**

```Python
Kirish: a=26, b=26
Chiqarish: 0
```

---

## if03

Hafta kuni raqami (1–7) berilgan. `elif` yordamida kun nomini qaytaring: 1 — "Dushanba", 2 — "Seshanba", 3 — "Chorshanba", 4 — "Payshanba", 5 — "Juma", 6 — "Shanba", 7 — "Yakshanba". Boshqa qiymatlar uchun "Noto'g'ri kun" qaytaring.

**Misol 1:**

```Python
Kirish: n=1
Chiqarish: "Dushanba"
```

**Misol 2:**

```Python
Kirish: n=5
Chiqarish: "Juma"
```

**Misol 3:**

```Python
Kirish: n=8
Chiqarish: "Noto'g'ri kun"
```

---

## if04

Oy raqami (1–12) berilgan. `elif` yordamida oy nomini qaytaring: "Yanvar", "Fevral", "Mart", "Aprel", "May", "Iyun", "Iyul", "Avgust", "Sentyabr", "Oktyabr", "Noyabr", "Dekabr". Boshqa qiymatlar uchun "Noto'g'ri oy" qaytaring.

**Misol 1:**

```Python
Kirish: n=3
Chiqarish: "Mart"
```

**Misol 2:**

```Python
Kirish: n=12
Chiqarish: "Dekabr"
```

**Misol 3:**

```Python
Kirish: n=0
Chiqarish: "Noto'g'ri oy"
```

---

## if05

Allamurodning bahosi berilgan. Baho so'z bilan qaytarilsin: 5 — "A'lo", 4 — "Yaxshi", 3 — "Qoniqarli", 2 — "Qoniqarsiz". Boshqa qiymatlar uchun "Noto'g'ri baho" qaytaring.

**Misol 1:**

```Python
Kirish: baho=5
Chiqarish: "A'lo"
```

**Misol 2:**

```Python
Kirish: baho=3
Chiqarish: "Qoniqarli"
```

**Misol 3:**

```Python
Kirish: baho=7
Chiqarish: "Noto'g'ri baho"
```

---

## if06

Allamurodning uchta fandan olgan bali berilgan. Eng katta va eng kichik ball orasidagi (o'rtadagi) balni qaytaring. `max()`, `min()` va `sorted()` dan foydalanmang.

**Misol 1:**

```Python
Kirish: a=87, b=92, c=78
Chiqarish: 87
```

**Misol 2:**

```Python
Kirish: a=5, b=5, c=-1
Chiqarish: 5
```

---

## if07

Allamurodning ofisdagi xona raqami — ikki xonali son berilgan. Uning raqamlaridan kattasini qaytaring.

**Misol 1:**

```Python
Kirish: n=85
Chiqarish: 8
```

**Misol 2:**

```Python
Kirish: n=39
Chiqarish: 9
```

**Misol 3:**

```Python
Kirish: n=77
Chiqarish: 7
```

---

## if08

Allamurod oddiy kalkulyator yozmoqda. Amal belgisi ("+", "-", "*", "/") va ikki son berilgan. Amal natijasini qaytaring. Agar bo'luvchi 0 bo'lsa "Nolga bo'lish mumkin emas", amal belgisi noma'lum bo'lsa "Noma'lum amal" matnini qaytaring.

**Misol 1:**

```Python
Kirish: belgi="+", a=12, b=5
Chiqarish: 17
```

**Misol 2:**

```Python
Kirish: belgi="*", a=12, b=5
Chiqarish: 60
```

**Misol 3:**

```Python
Kirish: belgi="/", a=12, b=5
Chiqarish: 2.4
```

**Misol 4:**

```Python
Kirish: belgi="/", a=12, b=0
Chiqarish: "Nolga bo'lish mumkin emas"
```

**Misol 5:**

```Python
Kirish: belgi="%", a=12, b=5
Chiqarish: "Noma'lum amal"
```

---

## if09

Allamurod shahar ichida mashina haydamoqda, tezligi (km/soat) berilgan. 60 gacha (60 ham kiradi) "Me'yorda", 61–80 "Ogohlantirish", 81–100 "Jarima", 100 dan yuqori bo'lsa "Guvohnoma olib qo'yiladi" matnini qaytaring.

**Misol 1:**

```Python
Kirish: tezlik=55
Chiqarish: "Me'yorda"
```

**Misol 2:**

```Python
Kirish: tezlik=75
Chiqarish: "Ogohlantirish"
```

**Misol 3:**

```Python
Kirish: tezlik=95
Chiqarish: "Jarima"
```

**Misol 4:**

```Python
Kirish: tezlik=130
Chiqarish: "Guvohnoma olib qo'yiladi"
```

---

## if10

Allamurodning uch oylik foydasi berilgan. Ular orasida nechta musbat son borligini qaytaring.

**Misol 1:**

```Python
Kirish: a=500000, b=-200000, c=100000
Chiqarish: 2
```

**Misol 2:**

```Python
Kirish: a=-1, b=-2, c=0
Chiqarish: 0
```

---

## if11

Allamurodning talabalik ID raqami — besh xonali son berilgan. Uning eng katta raqamini qaytaring. `max()` dan foydalanmang.

**Misol 1:**

```Python
Kirish: n=47215
Chiqarish: 7
```

**Misol 2:**

```Python
Kirish: n=10203
Chiqarish: 3
```

**Misol 3:**

```Python
Kirish: n=99999
Chiqarish: 9
```

---

## if12

Besh xonali son berilgan. Eng katta raqam chapdan nechanchi o'rinda turganini qaytaring (o'rinlar 1 dan boshlanadi). Eng katta raqam bir necha marta uchrasa, birinchisining o'rnini qaytaring.

**Misol 1:**

```Python
Kirish: n=47215
Chiqarish: 2
```

**Misol 2:**

```Python
Kirish: n=12345
Chiqarish: 5
```

**Misol 3:**

```Python
Kirish: n=90919
Chiqarish: 1
```

---

## if13

Toshkentdagi uch kunlik harorat berilgan. `sorted()`, `max()` va `min()` dan foydalanmasdan ularni o'sish tartibida bo'sh joy bilan ajratilgan matn ko'rinishida qaytaring.

**Misol 1:**

```Python
Kirish: a=35, b=18, c=27
Chiqarish: "18 27 35"
```

**Misol 2:**

```Python
Kirish: a=-5, b=3, c=0
Chiqarish: "-5 0 3"
```

---

## if14

Allamurod xaritada do'kon joylashuvini belgiladi, koordinatalari x va y berilgan. Nuqta qaysi chorakda ekanini qaytaring: "I chorak", "II chorak", "III chorak" yoki "IV chorak". Agar nuqta koordinata o'qlaridan birida yotsa "Koordinata o'qida" qaytaring.

**Misol 1:**

```Python
Kirish: x=3, y=4
Chiqarish: "I chorak"
```

**Misol 2:**

```Python
Kirish: x=-3, y=4
Chiqarish: "II chorak"
```

**Misol 3:**

```Python
Kirish: x=-3, y=-4
Chiqarish: "III chorak"
```

**Misol 4:**

```Python
Kirish: x=3, y=-4
Chiqarish: "IV chorak"
```

**Misol 5:**

```Python
Kirish: x=0, y=5
Chiqarish: "Koordinata o'qida"
```

---

## if15

Allamurodning kun tartibi: 9:00 gacha — "Ishga tayyorgarlik", 9:00–12:59 — "Ish", 13:00–13:59 — "Tushlik", 14:00–17:59 — "Ish", 18:00 dan keyin — "Dam olish". Soat va daqiqa berilgan, shu vaqtdagi mashg'ulotni qaytaring.

**Misol 1:**

```Python
Kirish: soat=8, daqiqa=45
Chiqarish: "Ishga tayyorgarlik"
```

**Misol 2:**

```Python
Kirish: soat=10, daqiqa=30
Chiqarish: "Ish"
```

**Misol 3:**

```Python
Kirish: soat=13, daqiqa=15
Chiqarish: "Tushlik"
```

**Misol 4:**

```Python
Kirish: soat=18, daqiqa=0
Chiqarish: "Dam olish"
```

---

## if16

Allamurod bankomatdan pul yechmoqda. Bankomatda 100000, 50000 va 10000 so'mlik kupyuralar bor va u eng kam sonli kupyura beradi. Summa berilgan. Agar summa musbat bo'lmasa yoki 10000 ga karrali bo'lmasa "Bu summani berib bo'lmaydi" matnini qaytaring. Aks holda "100000 x <soni>, 50000 x <soni>, 10000 x <soni>" ko'rinishidagi matnni qaytaring.

**Misol 1:**

```Python
Kirish: summa=280000
Chiqarish: "100000 x 2, 50000 x 1, 10000 x 3"
```

**Misol 2:**

```Python
Kirish: summa=40000
Chiqarish: "100000 x 0, 50000 x 0, 10000 x 4"
```

**Misol 3:**

```Python
Kirish: summa=125000
Chiqarish: "Bu summani berib bo'lmaydi"
```

---

## if17

Tug'ilgan kun va oy berilgan. Burjni qaytaring: Qo'y (21.03–19.04), Buzoq (20.04–20.05), Egizaklar (21.05–20.06), Qisqichbaqa (21.06–22.07), Arslon (23.07–22.08), Parizod (23.08–22.09), Tarozi (23.09–22.10), Chayon (23.10–21.11), O'qotar (22.11–21.12), Tog' echkisi (22.12–19.01), Qovg'a (20.01–18.02), Baliqlar (19.02–20.03). Masalan, Allamurod 15-martda tug'ilgan — "Baliqlar".

**Misol 1:**

```Python
Kirish: kun=15, oy=3
Chiqarish: "Baliqlar"
```

**Misol 2:**

```Python
Kirish: kun=21, oy=3
Chiqarish: "Qo'y"
```

**Misol 3:**

```Python
Kirish: kun=5, oy=1
Chiqarish: "Tog' echkisi"
```

**Misol 4:**

```Python
Kirish: kun=10, oy=8
Chiqarish: "Arslon"
```

---

## if18

Allamurodning oylik elektr sarfi (kVt·soat) berilgan. Pog'onali tarif bo'yicha to'lov summasini qaytaring: dastlabki 200 kVt·soat — 600 so'mdan, 201–500 — 900 so'mdan, 500 dan yuqorisi — 1200 so'mdan.

**Misol 1:**

```Python
Kirish: kwh=150
Chiqarish: 90000
```

**Misol 2:**

```Python
Kirish: kwh=300
Chiqarish: 210000
```

**Misol 3:**

```Python
Kirish: kwh=600
Chiqarish: 510000
```

---

## if19

Allamurodning uchburchak gulzori tomonlari a, b, c ixtiyoriy tartibda berilgan. Eng uzun tomonni aniqlang va uchburchak turini qaytaring: agar uchburchak yasab bo'lmasa "Uchburchak emas"; qisqa tomonlar kvadratlari yig'indisi eng uzun tomon kvadratiga teng bo'lsa "To'g'ri burchakli", katta bo'lsa "O'tkir burchakli", kichik bo'lsa "O'tmas burchakli".

**Misol 1:**

```Python
Kirish: a=5, b=3, c=4
Chiqarish: "To'g'ri burchakli"
```

**Misol 2:**

```Python
Kirish: a=5, b=5, c=5
Chiqarish: "O'tkir burchakli"
```

**Misol 3:**

```Python
Kirish: a=3, b=4, c=6
Chiqarish: "O'tmas burchakli"
```

**Misol 4:**

```Python
Kirish: a=1, b=2, c=5
Chiqarish: "Uchburchak emas"
```

---

## if20

Sana kun, oy va yil ko'rinishida berilgan (sana to'g'ri ekani kafolatlanadi). Keyingi kun sanasini "kun.oy.yil" ko'rinishida (oldida nolsiz) qaytaring. Oy oxiri, yil oxiri va kabisa yilini hisobga oling.

**Misol 1:**

```Python
Kirish: kun=15, oy=3, yil=2000
Chiqarish: "16.3.2000"
```

**Misol 2:**

```Python
Kirish: kun=28, oy=2, yil=2000
Chiqarish: "29.2.2000"
```

**Misol 3:**

```Python
Kirish: kun=28, oy=2, yil=2026
Chiqarish: "1.3.2026"
```

**Misol 4:**

```Python
Kirish: kun=31, oy=12, yil=2025
Chiqarish: "1.1.2026"
```

