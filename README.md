# Truth or Dare Game 🎯

## 📁 Ye Files Hai Jo Tumhe Chahiye

Is folder mein complete Truth or Dare game hai jo WordPress mein embed kar sakte ho!

---

## 🚀 Deploy Karne Ke 3 Tariqe

### Method 1: Vercel (Sabse Best) ⭐⭐⭐⭐⭐

**Step 1: GitHub Pe Upload**
```
1. GitHub.com pe jao aur login karo
2. New Repository banao
3. "truth-or-dare-game" naam do
4. Is folder ke saare files upload karo
```

**Step 2: Vercel Connect**
```
1. Vercel.com pe jao
2. "Sign Up with GitHub" karo
3. "New Project" pe click karo
4. Apna repository select karo
5. "Deploy" pe click karo
6. 2-3 min wait karo
7. LIVE! 🎉
```

---

### Method 2: Netlify ⭐⭐⭐⭐

```
1. Netlify.com pe jao
2. "Add new site" → "Import from Git"
3. GitHub connect karo
4. Repository select karo
5. Build command: bun run build
6. Publish directory: out
7. Deploy!
```

---

### Method 3: Manual Hosting

```
1. Hosting provider se Node.js support wala plan lo
2. Ye saare files upload karo
3. npm install ya bun install chalao
4. npm run build chalao
5. npm start se server chalao
```

---

## 📱 WordPress Mein Embed Karna

Jab website deploy ho jaye, to WordPress mein ye code dalo:

```html
<!-- Custom HTML Block mein paste karo -->
<div style="width: 100%; max-width: 100%; margin: 0 auto;">
  <iframe 
    src="https://TUMHARI-URL.vercel.app" 
    width="100%" 
    height="800" 
    frameborder="0" 
    scrolling="yes"
    style="border: none; border-radius: 20px; box-shadow: 0 10px 40px rgba(0,0,0,0.2);"
    allow="fullscreen">
  </iframe>
</div>
```

**Important:** `TUMHARI-URL` ko apni asal URL se replace karo!

---

## 📂 Folder Structure

```
truth-or-dare-game/
├── src/
│   ├── app/
│   │   ├── page.tsx        (Main Game)
│   │   ├── layout.tsx      (Page Layout)
│   │   └── globals.css     (Styles)
│   ├── components/ui/      (UI Components)
│   ├── lib/
│   │   └── questions.ts    (5000+ Questions)
│   └── hooks/
├── public/                  (Images/Icons)
├── package.json            (Dependencies)
├── tailwind.config.ts      (Styling Config)
├── next.config.ts          (Next.js Config)
└── tsconfig.json           (TypeScript Config)
```

---

## ⚡ Quick Commands

```bash
# Install dependencies
bun install

# Run development server
bun run dev

# Build for production
bun run build

# Start production server
bun run start
```

---

## 🎮 Game Features

- ✅ 5000+ Questions (Truth & Dare)
- ✅ 7 Categories (Romantic, Funny, Wild, etc.)
- ✅ Beautiful Animations
- ✅ Mobile Responsive
- ✅ WordPress Embeddable
- ✅ No Database Required

---

## ❓ Agar Koi Problem Ho

1. **Build Error?** → Node.js 18+ use karo
2. **Styles nahi dikh rahe?** → Tailwind CSS install check karo
3. **WordPress mein nahi dikh raha?** → URL sahi hai check karo

---

## 🔗 Important Links

- Vercel: https://vercel.com
- Netlify: https://netlify.com
- GitHub: https://github.com

---

Made with ❤️ by AI
