# HTTP Status Kodlari

HTTP status kodlari veb-serverning mijoz (odatda brauzer yoki API mijoz) tomonidan yuborilgan so'rovga bergan javobini bildiradi. Ular 3 xonali sonlardan iborat bo'lib, har birining o'ziga xos ma'nosi bor. Quyida asosiy toifalar va ba'zi keng tarqalgan status kodlarining ma'nolari keltirilgan:

## 1xx: Informatsion Javoblar
Bu toifadagi kodlar so'rov qabul qilinganligini bildiradi, ammo uni to'liq qayta ishlash hali yakunlanmagan.

- **100 Continue**: Mijoz so'rovini davom ettirishi mumkin.
- **101 Switching Protocols**: Server mijozning boshqa protokolga o'tish talabini qabul qildi.

## 2xx: Muvaffaqiyatli Javoblar
Bu kodlar server mijoz tomonidan yuborilgan so'rovni muvaffaqiyatli amalga oshirganini bildiradi.

- **200 OK**: So'rov muvaffaqiyatli bajarildi va javobda talab qilingan ma'lumotlar qaytarildi.
- **201 Created**: So'rov muvaffaqiyatli bajarildi va yangi resurs yaratildi.
- **204 No Content**: So'rov muvaffaqiyatli bajarildi, ammo javobda qaytariladigan ma'lumotlar yo'q.

## 3xx: Yo'naltirishlar
Bu kodlar mijozga boshqa manzilga o'tishni ko'rsatadi.

- **301 Moved Permanently**: Resurs doimiy ravishda boshqa manzilga ko'chirilgan.
- **302 Found**: Resurs vaqtincha boshqa manzilga ko'chirilgan.
- **304 Not Modified**: Resurs o'zgarmagan, shuning uchun mijozga keshdagi versiyani ishlatishi mumkin.

## 4xx: Mijoz Xatolari
Bu kodlar mijoz tomonidan yuborilgan so'rovda xatolik borligini bildiradi.

- **400 Bad Request**: So'rovda xato bor va server uni qayta ishlay olmaydi.
- **401 Unauthorized**: Avtorizatsiya talab qilinadi, ammo taqdim etilgan ma'lumotlar yetarli emas.
- **403 Forbidden**: So'rov qabul qilindi, ammo mijozda kerakli ruxsatlar yo'q.
- **404 Not Found**: So'ralgan resurs topilmadi.

## 5xx: Server Xatolari
Bu kodlar serverning ichki xatosi yoki muammosi borligini bildiradi.

- **500 Internal Server Error**: Serverda noma'lum xato yuz berdi.
- **502 Bad Gateway**: Server boshqa serverdan noto'g'ri javob oldi.
- **503 Service Unavailable**: Server hozirda so'rovlarni qayta ishlay olmaydi, odatda vaqtinchalik muammo sababli.

