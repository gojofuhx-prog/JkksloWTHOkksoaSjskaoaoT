# 1HOSTING Premium Control Panel (v5)

Railway তে deploy করুন — 1HOSTING/ ফোল্ডারের ভিতরের সব ফাইল একসাথে upload করুন।

## Deploy Steps (Railway)
1. Railway dashboard এ নতুন Service → Upload Repository → এই ফোল্ডারের কন্টেন্ট upload করুন (GitHub ছাড়া directly deploy হয়)।
2. Railway Variables ট্যাবে (ঐচ্ছিক):
   - `PANEL_SECRET=admin123`
   - `PANEL_USER_PASS=userpass123`
3. Deploy হলে URL পাবেন — বট থেকে `/sethosting <url> admin123 admin123` পাঠান।

## Default Login
- Username: `FSFUHX` / Password: `FXFUHXFFKING` (প্রথম login এর পরে প্যানেলের Settings থেকে password পরিবর্তন করুন)

## Trusted Devices
- Login-এ "Trust this device" টিক দিলে **প্রথম ২টা ফোন** সাথে সাথে trusted হয় (password ছাড়া permanent login)।
- ৩য় ফোন login করলে Devices ট্যাবে Pending আসে — Admin Approve চাপার পর trusted হয়।

## Features
- Terminal (Package Installer সহ: pip/apt install/uninstall)
- Servers, Processes, Backup, Telegram Bot, Port Scanner, Health Score, Activity Log, Domains, Webhooks, Users, Settings
