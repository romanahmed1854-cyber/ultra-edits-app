# Ultra Edits — Edit Without Limits

Complete React + Tailwind CSS mobile & desktop video editor app.

## 1. GitHub দিয়ে সরাসরি Android APK বিল্ড করার নিয়ম (PC ছাড়াই)
1. GitHub-এ নতুন একটি Repository (যেমন `ultra-edits`) তৈরি করুন।
2. এই ফোল্ডারের সব ফাইল (`.github` ফোল্ডারসহ) সেই রিপোজিটরিতে আপলোড / পুশ করুন।
3. রিপোজিটরির **Actions** ট্যাবে যান—`Build Ultra Edits (Web & Android APK)` অটোমেটিক রান হবে।
4. বিল্ড শেষ হলে নিচে **Artifacts** থেকে `ultra-edits-debug-apk` ডাউনলোড করে ফোনে ইন্সটল করুন!

## 2. নিজের কম্পিউটারে রান করতে
```bash
npm install
npm run dev
```

## 3. Web App / PWA হিসেবে হোস্ট করতে
GitHub রিপোটি **Vercel** বা **Netlify**-এ কানেক্ট করলে অটোমেটিক লাইভ হয়ে যাবে।
