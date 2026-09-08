<div align="center">

# 🏆 IreenTV Auto-Update Sports Playlist
### ⚡ রিয়েল-টাইম অটোমেটেড লাইভ স্পোর্টস প্লেলিস্ট ইঞ্জিন

[![Auto Update](https://img.shields.io/badge/Auto--Update-Every%202%20Minutes-brightgreen?style=for-the-badge&logo=clock)]()
[![Status](https://img.shields.io/badge/Server%20Status-Online%2024%2F7-success?style=for-the-badge&logo=render)]()
[![Python](https://img.shields.io/badge/Engine-Python%203.x-blue?style=for-the-badge&logo=python)]()
[![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)]()

<p align="center">
  <b>ক্রিকেট, ফুটবল এবং সকল বিশ্বমানের লাইভ স্পোর্টস চ্যানেলের সম্পূর্ণ অটোমেটিক প্লেলিস্ট হাব।</b><br>
  এখানে প্রতিটি সোর্স প্রতি ২ মিনিট পর পর স্বয়ংক্রিয়ভাবে স্ক্যান ও আপডেট করা হয়।
</p>

---

</div>

## 🌟 মূল বৈশিষ্ট্যসমূহ (Key Features)

- ⚡ **স্বয়ংক্রিয় আপডেট (2-Min Auto Sync):** ব্যাকগ্রাউন্ড রোবট প্রতি ২ মিনিট অন্তর সোর্স ফাইলগুলো চেক করে স্বয়ংক্রিয়ভাবে নতুন ডাটা পুশ করে।
- 🚀 **ক্যাশ বাইপাস প্রযুক্তি (Cache Buster):** গিটহাব সিডিএন ক্যাশ বাইপাস করে সরাসরি ফ্রেশ ও সচল লিংক নিশ্চিত করা হয়।
- 🌐 **সার্বক্ষণিক সক্রিয় (24/7 Uptime):** ক্লাউড সার্ভারের মাধ্যমে দিন-রাত ২৪ ঘণ্টা স্বয়ংক্রিয় মনিটরিং ব্যবস্থা।
- 📱 **সর্বজনীন সাপোর্ট:** যেকোনো IPTV প্লেয়ার (TiviMate, OTT Navigator, VLC, IPTV Smarters) এর সাথে ১০০% কমপ্যাটিবল।

---

## 📺 অন্তর্ভুক্ত স্পোর্টস নেটওয়ার্ক ও ক্যাটাগরি

| নেটওয়ার্ক / সোর্স | মূল কভারেজ | আপডেট ফ্রিকোয়েন্সি |
| :--- | :--- | :---: |
| 🏏 **Willow Cricket** | ইন্টারন্যাশনাল ক্রিকেট, আইপিএল, পিএসএল, বিগ ব্যাশ | ২ মিনিট |
| ⚽ **Sony LIV Sports** | উয়েফা চ্যাম্পিয়ন্স লিগ, লা লিগা, ডব্লিউডব্লিউই, ক্রিকেট | ২ মিনিট |
| 🎾 **Prime Video Sports** | টেনিস গ্র্যান্ড স্ল্যাম, প্রিমিয়ার লিগ ও এক্সক্লুসিভ ইভেন্ট | ২ মিনিট |
| 🥊 **Tapmad BD** | লাইভ স্পোর্টস, এশিয়া কাপ, আইসিসি ইভেন্ট ও ফুটবল | ২ মিনিট |
| 🎯 **BingStream & Others** | ২৪/৭ গ্লোবাল লাইভ স্পোর্টস চ্যানেল এবং স্পেশাল ম্যাচ | ২ মিনিট |

---

## 🚀 কীভাবে ব্যবহার করবেন? (How to Use)

আপনার পছন্দের IPTV প্লেয়ারে নিচের ফরম্যাটে সরাসরি লিংক ব্যবহার করতে পারেন:

```text
https://raw.githubusercontent.com/ireentv/IreenTv-Auto-Update-Playlist/refs/heads/main/bingstream.m3u


```


⚙️ সিস্টেম আর্কিটেকচার (How It Works)

graph LR
    A[Public GitHub Sources] -->|Monitor Every 2 Min| B(Watcher Python Engine)
    
    B -->|MD5 Hash Check| C{Change Detected?}
    
    C -->|Yes| D[Trigger GitHub Action]
    
    C -->|No| E[Sleep & Loop]
    
    D -->|Build & Update| F[Fresh Live Playlist]








⚖️ কপিরাইট ও আইনি অস্বীকৃতি (Disclaimer)


⚠️ গুরুত্বপূর্ণ বিজ্ঞপ্তি (Important Notice):
IreenTV কোনো প্রকার মিডিয়া কনটেন্ট বা ভিডিও স্ট্রিমিং সার্ভারে হোস্ট, ব্রডকাস্ট বা আপলোড করে না।
এই রিপোজিটরিতে থাকা সমস্ত প্লেলিস্ট ও লাইভ স্ট্রিমের লিংকগুলো ইন্টারনেটে উন্মুক্ত এবং বিভিন্ন পাবলিক গিটহাব (Open Source) সোর্স থেকে সংগৃহীত।
আমরা কোনো চ্যানেলের মালিকানা বা কপিরাইটের দাবিদার নই। সমস্ত স্বত্ব ও ট্রেডমার্ক সংশ্লিষ্ট ব্রডকাস্টার এবং মূল কনটেন্ট ক্রিয়েটরদের।
এই প্রজেক্টটি শুধুমাত্র প্রযুক্তিগত পরীক্ষা, অটোমেশন এবং শিক্ষামূলক (Educational) উদ্দেশ্যে তৈরি করা হয়েছে।


🤝 কৃতজ্ঞতা ও ক্রেডিট (Credits)
আমরা আন্তরিকভাবে কৃতজ্ঞ সেই সকল উন্মুক্ত ওপেন-সোর্স ডেভেলপার ও কমিউনিটির প্রতি, যাদের পাবলিক ডেটাবেজ ও এপিআই ব্যবহারের মাধ্যমে এই অটোমেশন সিস্টেমটি সম্ভব হয়েছে।
<div align="center">
<sub>Made with ❤️ by <b>IreenTV Team</b></sub>
</div>
```
