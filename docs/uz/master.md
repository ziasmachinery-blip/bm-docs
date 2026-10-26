# Usta uchun yo'riqnoma (UZ)

Usta o'z sexining Google Jadvalida hisobni yuritadi: postlar bo'yicha smena topshirig'i, ishchilar va PIN, yorliqlar, nazorat va tuzatishlar. Yo'riqnoma barcha sexlar uchun bitta; Jadval menyusi «Меню Цех N» deb ataladi. Menyu va tugma nomlari ruscha, qavs ichida tarjimasi.

## Usta vazifasi va yangiliklar

Pallet yo'li: Заливка (Quyish) → Распалубка (Qolipdan chiqarish) → Распиловка (Arralash) → Покраска (Bo'yash) → Зона набора прочности (Mustahkamlik zonasi) → Упаковка (Qadoqlash) → Склад ГП (TM ombori). Har bir uchastkada palletni o'sha yerda ishlayotgan ishchi qabul qiladi.

Ilova va Jadvaldagi yangiliklar:

- **Quyish postlari** — smena topshirig'ida «Пост» (Post) ustuni, quyuvchi o'z postining pozitsiyalarini ko'radi.
- **Ish kuni 06:00 dan** — yarim tundan keyingi quyish oldingi kun topshirig'iga kiradi.
- **«✎ Исправить» (Tuzatish)** — istalgan ishchi istalgan uchastkada miqdor, artikul, rang, buyurtmani sababi bilan tuzatadi; qoldiqlar va topshiriq qayta hisoblanadi.
- **Mertech TSD** — to'q sariq tugma bilan skanerlash.
- **«На участке» (Uchastkada) ro'yxati** — avval yangilari, rang uchastkadagi vaqtga qarab.
- **Xprinter XP-365B da yorliqlar** va sexning o'z raqamlashi (2-sexda raqamlar PL-2000… dan boshlanadi, boshqa sexlar bilan mos kelmasligi uchun).
- **🎓 O'quv palletlari** — «Начать учёт заново» (Hisobni qaytadan boshlash) dan keyin eski palletlar mashq uchun, hisobga kirmaydi.

## Telefon va TSD dagi ilova

**Ishchi telefoni:**

1. «Меню Цех N» → «📱 Приложение с камерой» (Kamerali ilova) — havola va QR-kod.
2. Havolani Chrome da oching → ⋮ → «Добавить на главный экран» (Bosh ekranga qo'shish).
3. Ishchi «Цех ▾» (Sex) ni tanlaydi, PIN bilan kiradi, uchastkani tanlaydi. Uchastkani tekshiring — «✓ Принять» (Qabul qilish) tugmasi unga bog'liq.

**Mertech TSD (bir marta):**

1. **Barcode Utility** ilovasi → Function Settings → chiqish rejimi **«Simulate keystroke»** (klaviatura emulyatsiyasi), suffiks **Enter**.
2. Ilovani telefondagidek o'rnating.
3. Profilda (yuqorida ismni bosing) **«Это ТСД со встроенным сканером»** (Bu o'rnatilgan skanerli TSD) belgisini qo'ying.
4. Tekshirish: to'q sariq tugma yorliqqa — pallet kartochkasi ochiladi.

**Usta ilovada nimani ko'radi:** «📊 Отчёты» (Hisobotlar) → «Задание заливки» (Quyish topshirig'i, postlar bo'yicha jami) va «Шт на этапах» (Bosqichlardagi dona); istalgan palletni skanerlash — tarix: kim, qachon, nima qilgan.

## Smena topshirig'i: postlar, ish kuni

Ochish: «Меню Цех N» → **«📋 Сменное задание: открыть»** (Smena topshirig'ini ochish).

| Ustun | Nima yoziladi |
| --- | --- |
| Дата (Sana) | Ish kuni sanasi |
| № заказа, Контрагент (Buyurtma №, Kontragent) | Buyurtmadan |
| Артикул | Ro'yxatdan tanlang |
| Цвет (Rang) | Rang / pigment |
| **План форм** (Qolip rejasi, sariq) | Nechta qolip quyiladi |
| Комментарий (Izoh) | Xohishga ko'ra |
| **Пост** (oxirgi ustun) | Post 1 / 2 / 3. **Bo'sh — pozitsiyani hamma postlar ko'radi** |

**Qoidalar:**

- Bitta qator = buyurtma + artikul + rang + post. Pozitsiyani postlar orasida bo'lish uchun turli postli ikki qator qiling va rejani bo'ling.
- **Ish kuni 06:00 da boshlanadi.** 00:00 dan 06:00 gacha quyish **oldingi** kun topshirig'iga hisoblanadi. Soat «Настройки» (Sozlamalar) → «Начало рабочих суток, ч» da o'zgartiriladi.
- Post nomlari — «Настройки» → «Посты заливки» (vergul bilan).
- Topshiriqni o'zgartirgandan keyin quyuvchilarga ilovada **⟳** ni bosishni ayting.
- Menyu filtrlari: «сегодня» (bugun), «завтра» (ertaga), «все» (hammasi).
- Факт va «Выполнено» (Bajarildi) ga tegmang — ular o'zi hisoblanadi.

## Nazorat, hisobotlar, tuzatishlar

- Topshiriqdagi **Факт / Выполнено** quyuvchilar skaneri bo'yicha avtomatik to'ldiriladi. Topshiriqsiz quyish «вне задания» (topshiriqdan tashqari) qatorlariga tushadi — smena oxirida tekshiring.
- Uchastkalar bo'yicha qoldiqlar va dashbordlar o'zi yangilanadi. Raqamlar g'alati ko'rinsa — «Меню Цех N» → **«🔄 Пересчитать всё»** (Hammasini qayta hisoblash).
- Ishchilar istalgan bosqichda **«✎ Исправить»** tugmasi bilan pallet ma'lumotini tuzatishi mumkin. Har bir tuzatish tarixga ishchi ismi bilan **«Инвентаризация ±»** (Inventarizatsiya) deb yoziladi — bunday qatorlarni tekshirib boring.
- Xato amalni ishchi o'zi bekor qiladi: «Мои действия» (Mening amallarim) → bekor qilish.
- Pallet xato quyilgan bo'lsa → «Паллеты» varag'ida qatorni belgilang → **«↩ Паллеты: сбросить выделенные»** (Belgilangan palletlarni tozalash).
- Mustahkamlik zonasidan muddatidan oldin chiqarish — faqat usta qarori bilan.
- Eski yozuvlarda tungi quyish boshqa kunga tushib qolgan bo'lsa — **«Рабочие сутки: применить к старым записям»** (Ish kunini eski yozuvlarga qo'llash). Qayta ishga tushirish mumkin, ikki marta surmaydi.

## Foydalanuvchilar, XP-365B yorliqlari, o'quv palletlari

**Foydalanuvchilar.** «Меню Цех N» → foydalanuvchi qo'shish → tizim PIN beradi, uni ishchiga shaxsan bering. PIN unutilsa — yangisini bering. Ishdan ketsa — «Активен» (Faol) ustuniga **Нет** (Yo'q) qo'ying (qatorni o'chirmang — tarix saqlanadi).

**Xprinter XP-365B da yorliqlar:**

1. «🏷 QR-этикетки: напечатать новые…» (Yangi QR-yorliqlarni chop etish) → sonini kiriting.
2. **«🖨 Открыть для печати на XP-365B»** (XP-365B da chop etish uchun ochish) ni bosing.
3. Chop etish oynasida: printer XP-365B, qog'oz o'lchami = yorliq o'lchami (E×B), chegaralar **yo'q**, masshtab **100%**, kolontitullar **o'chirilgan**.
4. Yorliq o'lchami: «🏷 Этикетки: размер для принтера». Sex raqamlashi: «🏷 Этикетки: своя нумерация цеха».
5. Buzilgan yorliqni qayta chop etish: «Паллеты» da qatorlarni belgilang → belgilanganlarni qayta chop etish. Ombor manzil lavhalari ham shu yerda chop etiladi.

**Hisobni qaytadan boshlash va o'qitish:**

- **«🧹 Начать учёт заново»** (Hisobni qaytadan boshlash) — barcha eski ma'lumotlar Google Diskdagi arxiv jadvaliga o'tadi, eski palletlar **o'quv** palletiga aylanadi («🎓 УЧЕБНАЯ» belgisi, hisobga kirmaydi). Yangi hisob boshlanishidan oldin bir marta qilinadi.
- **«🎓 Учебные паллеты: завершить обучение»** (O'qitishni yakunlash) — hamma o'rganib bo'lgach, o'quv palletlari olib tashlanadi.
- **«🗂 Вкладки: упорядочить»** (Varaqlarni tartiblash) — kerakli varaqlar chapda, xizmat varaqlari yashirin. «показать все» (hammasini ko'rsatish) — yashirini kerak bo'lsa.
- «Настройки» varag'idagi **E11** katakda sex kodi turishi kerak (2-sex uchun c2, 3-sex uchun c3). Uni o'zgartirmang.

## Agar nimadir noto'g'ri ketsa

| Nima bo'ldi | Nima qilish kerak |
| --- | --- |
| Quyuvchida «Нет задания на сегодня» (Bugunga topshiriq yo'q) | Topshiriqdagi sanani tekshiring (06:00 ni esda tuting). ⟳ ni bossin |
| Postda pozitsiya ko'rinmaydi | «Пост» ustunida boshqa post turibdi. Tuzating yoki bo'sh qoldiring |
| «Нет «Шт в форме»» (Qolipdagi dona yo'q) | Artikullar ro'yxatida shu artikul uchun «Шт в форме» ni to'ldiring |
| Ilovada aloqa yo'q | Wi-Fi / internetni tekshiring. Amalni aloqa tiklangach takrorlang |
| «Лог\_форм» da «ОШИБКА» (Xato) qatori | Xato matnini o'qing, ma'lumotni tuzating, kerak bo'lsa — «🔄 Пересчитать всё» |
| «Меню Цех N» chiqmayapti | Jadval sahifasini yangilang, 10–20 soniya kuting |
| TSD kodni o'zi kiritmayapti | Barcode Utility → «Simulate keystroke» + suffiks Enter; profilda «Это ТСД» belgisi |
| Yorliqlar sahifasi — 404 xatosi | GitHub da **labels.html** fayli yo'q (nomi aynan .html bilan) |
| «Не указан код цеха» (Sex kodi ko'rsatilmagan) | «Настройки» varag'ida E11 ga sex kodini yozing (c2 / c3) |

> **Asosiy qoida:** «Движение», «Паллеты», «Остатки» varaqlarini va topshiriqdagi fakt ustunlarini qo'lda o'zgartirmang. Barcha tuzatishlar — ilova yoki menyu orqali.
