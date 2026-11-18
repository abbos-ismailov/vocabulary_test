<div align="center">

<img src="icon-192.png" alt="Vocabulary App logo" width="120" height="120">

# 📚 Vocabulary App

### So‘zlarni yodlang. Ularning o‘sishini kuzating. 🌰 → 🌱 → 🌿 → 🌸

Inglizcha so‘zlarni bo‘limlarga ajratib, kartochka, test va yozish orqali yodlashga yordam beradigan oddiy va chiroyli veb-ilova.

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

</div>

---

## ✨ Imkoniyatlar

| | Imkoniyat | Tavsif |
|---|---|---|
| 📂 | **Bo‘limlar** | So‘zlarni mavzu yoki unit bo‘yicha guruhlang |
| ⚡ | **Ko‘p so‘z birdan** | 10, 20 yoki undan ko‘p so‘zni bitta oynada qo‘shing |
| 💬 | **Namuna gap** | Har bir so‘zga misol gap qo‘shing (mashq paytida javob yashirin turadi) |
| 🃏 | **Kartochkalar** | 3D aylanadigan kartochkalar bilan yodlang |
| ✅ | **Test** | 4 ta variantdan to‘g‘ri so‘zni toping |
| ⌨️ | **Yozish** | So‘zni o‘zingiz yozib mashq qiling |
| 🌱 | **O‘sish jarayoni** | Har bir so‘z urug‘dan gulgacha o‘sadi |
| ✏️ | **Tahrirlash** | So‘z, ta’rif va namuna gapni istalgan vaqt o‘zgartiring |
| ☁️ | **Sinxronlash** | Kompyuterda kiriting, telefonda yodlang |
| 🌙 | **Ikki rejim** | Tungi va kunduzgi dizayn |
| 📱 | **Telefonga o‘rnatish** | Bosh ekranga alohida ilova sifatida qo‘shiladi |

---

## 🌱 So‘z qanday yodlanadi?

Har bir so‘z **3 marta to‘g‘ri topilganda** yodlangan hisoblanadi. Xato qilsangiz, so‘z qaytadan boshlanadi.

| Bosqich | Belgi | Ma’nosi |
|:---:|:---:|---|
| 0 | 🌰 | Yangi so‘z (urug‘) |
| 1 | 🌱 | 1 marta to‘g‘ri topildi |
| 2 | 🌿 | 2 marta to‘g‘ri topildi |
| 3 | 🌸 | **Yodlandi!** |

> ❌ Xato javob so‘zni yana 🌰 holatiga qaytaradi.

Raundda doim **eng kam yodlangan 10 ta so‘z** tanlanadi va aralashtirib beriladi, xato qilingan so‘z esa to‘g‘ri topilguncha raund oxirida yana so‘raladi.

---

## 🎯 Yodlash rejimlari

### 🃏 Kartochkalar
Ta’rifni ko‘rasiz, kartochkani bosib aylantirasiz, javobni ko‘rib **Bildim** yoki **Bilmadim** deb belgilaysiz.

### ✅ Test
Ta’rif bo‘yicha 4 ta variantdan to‘g‘ri so‘zni tanlaysiz. Javobdan keyin natija rangli blokda ko‘rinadi va 2 soniyadan keyin keyingi so‘zga o‘tiladi.

### ⌨️ Yozish
Ta’rif bo‘yicha inglizcha so‘zni yozasiz.
- ✅ To‘g‘ri bo‘lsa, **1 soniyadan** keyin keyingisiga o‘tadi.
- ❌ Xato bo‘lsa, to‘g‘ri javob ko‘rsatilib, **2,5 soniyadan** keyin o‘tadi.

---

## ✍️ So‘z qo‘shish formati

Har bir qatorga bitta so‘z yoziladi. Namuna gap ixtiyoriy va `|` belgisidan keyin yoziladi:

```text
apple - a round red or green fruit | I eat an apple every day
brave - ready to face danger | The brave firefighter saved the cat
laugh - to make sounds that show you are happy
```

Ajratgich sifatida `-`, `=`, `:` yoki `Tab` ishlatish mumkin.

---

## 🎨 Dizayn

- 🌙 **Tungi rejim:** to‘q ko‘k fon, yashil tugmalar, sariq sarlavhalar. Ko‘zni charchatmaydi.
- ☀️ **Kunduzgi rejim:** iliq shaftoli fon, qora matn, gul ranglaridagi tugmalar.
- 🔤 Inglizcha so‘z **katta va rangli**, ta’rif esa **kichik va boshqa rangda**, shuning uchun ikkalasini adashtirmaysiz.

---

## 🛠️ Texnologiyalar

- **Frontend:** oddiy HTML, CSS va JavaScript (framework yo‘q, bitta fayl)
- **Ma’lumotlar bazasi:** Firebase Firestore
- **Kirish:** Firebase Authentication (Google)
- **Hosting:** Vercel
- **PWA:** manifest va ikonkalar orqali telefonga o‘rnatiladi

---

## 📁 Loyiha tuzilmasi

```text
📦 vocabulary-app
 ┣ 📄 index.html              # Butun ilova (HTML + CSS + JS)
 ┣ 📄 manifest.webmanifest    # PWA sozlamalari
 ┣ 🖼️ icon-192.png            # Ilova ikonkasi
 ┣ 🖼️ icon-512.png            # Katta ikonka
 ┣ 🖼️ apple-touch-icon.png    # iPhone uchun ikonka
 ┗ 📄 README.md
```

---

## 🚀 O‘rnatish

### 1️⃣ Firebase ni sozlash

1. [Firebase Console](https://console.firebase.google.com/) da yangi loyiha yarating.
2. **Build → Firestore Database → Create database** (production mode).
3. **Build → Authentication → Sign-in method** da **Google** ni yoqing.
4. **Project settings → Your apps → Web (`</>`)** da web ilova qo‘shing va `firebaseConfig` ni nusxalang.
5. `index.html` ichidagi `var FB={...}` qatoriga o‘z configingizni qo‘ying.

### 2️⃣ Xavfsizlik qoidalari

**Firestore → Rules** bo‘limiga quyidagini qo‘yib, **Publish** qiling. Shunda har kim faqat o‘z ma’lumotini o‘qiy va yoza oladi:

```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /users/{uid} {
      allow read, write: if request.auth != null && request.auth.uid == uid;
    }
  }
}
```

### 3️⃣ Vercel ga joylash

1. Loyihani GitHub ga yuklang.
2. [Vercel](https://vercel.com/) da **Add New → Project** orqali repository ni ulang.
3. Deploy tugagach, manzilni (masalan, `your-app.vercel.app`) nusxalang.
4. Firebase da **Authentication → Settings → Authorized domains → Add domain** orqali shu domenni qo‘shing. Bu bo‘lmasa, Google orqali kirish ishlamaydi.

---

## 📱 Telefonga o‘rnatish

1. Telefon brauzerida (Chrome) ilovani oching.
2. Menyu (⋮) → **Install app** yoki **Add to Home screen** ni tanlang.
3. Bosh ekranda 📚 ikonkali **Vocabulary** ilovasi paydo bo‘ladi.

---

## 🔄 Qurilmalar o‘rtasida sinxronlash

1. Kompyuterda **Google bilan kirish** tugmasi orqali kiring va so‘zlarni kiriting.
2. Telefonda ham shu Google akkaunt bilan kiring.
3. Ma’lumotlar ikkalasida bir xil bo‘ladi. Yuqori chapdagi yozuv holatni ko‘rsatadi:
   - ☁️ **Sinxronlangan** — hammasi saqlangan
   - ⏳ **Ulanmoqda...** — Firebase ga ulanyapti
   - 📴 **Faqat shu qurilmada** — kirilmagan, ma’lumot faqat shu brauzerda turibdi

---

## 💡 Maslahatlar

- 📝 So‘zlarni kompyuterda katta ro‘yxat qilib kiriting, mashqni telefonda qiling.
- 🔁 Har kuni 1–2 raund qilish haftada bir marta uzoq o‘tirishdan yaxshiroq.
- 💬 Namuna gap qo‘shing: so‘z kontekstda ancha tez yodlanadi.

---

<div align="center">

**Yodlashda omad! 🌸**

Agar loyiha yoqsa, ⭐ qo‘yishni unutmang.

</div>
