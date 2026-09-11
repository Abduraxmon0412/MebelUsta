# Shkaf Ustasi

Brauzerda ishlaydigan **parametrik shkaf konstruktori** — korpus mebel ustalari uchun «Базис-Мебельщик»ning soddalashtirilgan bepul muqobili. O'rnatish talab qilinmaydi: bitta `index.html` faylni brauzerda ochish kifoya.

## Imkoniyatlar

- **3D model** — o'lchamlar kiritilishi bilan darhol yangilanadi (Three.js), sichqoncha bilan aylantirish/masshtablash, eshik va orqa devorni yashirish
- **Detallar ro'yxati** — har bir detal o'lchami, soni, kromka (PVX 2 mm / 0.4 mm) hisobi bilan
- **Bichuv kartasi** — detallar LDSP listlarga (2800×2070 mm) avtomatik joylashtiriladi: guillotine qatorli algoritm, kesish yo'li (kerf) 4 mm, listlar soni va to'ldirish foizi
- **Teshik chizmalari (присадка)** — har detal uchun aniq koordinatalar:
  - konfirmat Ø7 (o'tma) / Ø5 (torets)
  - polka pinlari Ø5×12, chetdan 37 mm
  - petlya kosasi Ø35×12, chetdan 22 mm
  - ruchka teshiklari Ø5, 96 mm oraliq
- **Materiallar va tannarx** — LDSP/DVP listlar, kromka metraji, furnitura soni; narxlar tahrirlanadi va brauzerda saqlanib qoladi
- **Chop etish** — chizmalarni printerga chiqarish

## Kiritiladigan parametrlar

Kenglik, balandlik, chuqurlik, LDSP qalinligi (16/18 mm), seksiyalar soni, har seksiyadagi polkalar, eshiklar soni, tsokol balandligi.

## Konstruksiya modeli

Standart korpus: yon devorlar to'liq balandlikda, kryshka/dno ular orasida, tik to'siqlar, sozlanadigan polkalar (pin ustida), nakladnoy eshiklar, DVP orqa devor (nakladnoy), old/orqa tsokol plankalari. Biriktirish — konfirmat 7×50.

## Ishga tushirish

`index.html` ni istalgan zamonaviy brauzerda oching (Three.js CDN dan yuklanadi — internet kerak).

## Reja (keyingi bosqichlar)

- [ ] Tortmalar (yashiklar)
- [ ] Kupe (sirpanuvchi) eshiklar
- [ ] Burchak shkaflar
- [ ] PDF eksport
- [ ] Loyihani fayl sifatida saqlash/ochish
