# Balimate Web

All files in `public` directory 👍

Link :
https://balimate.web.app

Tutorial deploy (jika baru mulai) :
- Clone repo ini
- Kerjakan 👍
- Pastikan sudah menginstal `firebase CLI`, jika belum :
```
npm install -g firebase-tools
```
- Login ke akun firebase
```
firebase login
```
- Inisiasi Firebase (di dalam folder project)
```
firebase init
```
- Ikuti alur seperti di bawah
<img src="https://storage.googleapis.com/gambara/Screenshot%20(767).png" />

- Deploy ke website balimate
```
firebase deploy --only hosting:balimate
```
- Sebelum di push jangan lupa di pull
