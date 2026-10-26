O‘ZBEK KIRILL ↔ LOTIN — EXCEL 2021 OFFICE ADD-IN
==================================================

Bu paket VBA makrosidan foydalanmaydi. U Office JavaScript API bilan ishlaydigan
Office Add-in namunasi. Qo‘shimchada task pane ichida ikkita tugma bor.

MUHIM:
- Manifestdagi YOUR-USERNAME qiymatlarini o‘zingizning GitHub foydalanuvchi nomingizga almashtiring.
- taskpane.html faylini HTTPS orqali hostingga joylashtirish kerak (masalan, GitHub Pages).
- Office Add-in odatda HTTPS manzildan yuklanadi. HTML faylini shunchaki Excel ichiga
  qo‘yish yetarli emas.
- Ushbu paketda tayyor ommaviy hosting yoki Microsoft tomonidan tasdiqlangan do‘kon nashri yo‘q.
- Ish joyingizdagi Excel siyosati add-in sideload qilishni cheklashi mumkin.

O‘RNATISHNING UMUMIY YO‘LI:
1. GitHub’da yangi public repository yarating: uzbek-excel-addin
2. taskpane.html, manifest.xml va icon-32.png, icon-64.png fayllarini yuklang.
3. Repository Settings → Pages → Deploy from branch → main / root ni tanlang.
4. Manifestdagi YOUR-USERNAME ni GitHub username bilan almashtiring.
5. GitHub Pages HTTPS manzili ochilishini tekshiring.
6. Excel 2021’da Insert → My Add-ins (yoki Home → Add-ins) → Upload My Add-in
   bo‘limidan manifest.xml ni yuklash usulini tanlang, agar bu imkoniyat mavjud bo‘lsa.
7. Add-in paneli ochilgach, kataklarni belgilang va yo‘nalish tugmasini bosing.

AGAR “UPLOAD MY ADD-IN” KO‘RINMASA:
Excel versiyasi, yangilanish kanali yoki tashkilot siyosati sideload’ni cheklashi mumkin.
Bunday holda Microsoft 365 administratoridan deployment yoki qo‘llab-quvvatlanadigan
o‘rnatish usulini so‘rash kerak bo‘ladi.

KONVERTOR HAQIDA:
- Kirill → Lotin va Lotin → Kirill.
- Formula saqlangan kataklar o‘zgartirilmaydi.
- Oddiy matn kataklarining qiymati bevosita almashtiriladi.
- Matnni avval nusxalash yoki faylning zaxira nusxasini saqlash tavsiya etiladi.
- O‘zbek imlosida kontekstga bog‘liq noaniqliklar bo‘lishi mumkin; ayniqsa E/Ё,
  apostrof variantlari va ng birikmalarini muhim hujjatlarda tekshiring.
