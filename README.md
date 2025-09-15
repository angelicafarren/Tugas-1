# Tugas 1 - Welcome to my GitHub! 👋
Hi there 👋
My name is Angelica Farren Limzinky (NPM 6162201021)

# 🚀 Dasar Git & GitHub

## 1. Persiapan
- Install [VS Code](https://code.visualstudio.com/download) & [Git](https://git-scm.com/downloads)  
- Buat akun [GitHub](https://github.com)  

## 2. Konfigurasi Awal
```bash
git config --global user.name "yourname"
git config --global user.email "youremail@mail.com"
ssh-keygen -t ed25519 -C "youremail@mail.com"

# clone repo dari GitHub
git clone git@github.com:username/reponame.git
cd reponame

# cek status & update
git status
git pull origin main

# buat/edit file, lalu simpan perubahan
git add .
git commit -m "pesan commit"

# kirim ke GitHub
git push origin main
