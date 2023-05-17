# AI Condition Analysis

Dibuat dengan :

- Python
- Flask
- Pandas
- Numpy
- Scikit-learn
- Sklearn


# How To Use Git Properly 

### If you new in this project Read the Initial Setup Section

# Contribution Guide

# Please DO NOT Direct PUSH to main Branch

## Braching Guide

- if you do improve

  > `git checkout -b "improvement/apa-yang-di-improve`

- if you do bugfix

  > `git checkout -b "bugfix/apa-yang-di-fix`

- if you do create a new feature
  > `git checkout -b "feature/fitur-apa-yang-di-buat`

## Commit Message Guide

- if you do improve

  > `git commit -m "improvement: apa yang di improve`

- if you do bugfix

  > `git commit -m "bugfix: apa yang di fix`

- if you do create a new feature
  > `git commit -m "feature: fitur apa yang di buat`

## Conflict Resolve Guide

- 1.Stash dulu kerjaan kamu supaya gak ilang

` git stash`

- 2.1 Setelah itu kamu perlu pull perubahan dari branch main

`git pull origin main`

- 2.2 Setelah kamu berhasil melakukan pembaruan dari branch main selanjutnya kamu perlu mengembalikan pekerjaan mu sebelum nya yang ter stash

`git stash pop`

- 2.3 Lanjutkan Pekerjaan dengan Semestinya

- 3 Tapi jika ketika melakukan step kedua terjadi error conflitc atau karena ketololan kamu, maka ikuti langkah yang bawah

## Conflict Resolve Guide V2

- 1 Pindah dulu ke Branch main

`git checkout main`

- 2 Kemudian pull perubahan terbaru dari branch main

`git pull`

- 3 Kemudian Pindah lagi ke branch dirimu

`git checkout <branch mu>`

- 4 Selanjutnya kita perlu merge perubahan terbaru dari main

`git merge main`

# Please USE Python 3.9

## Recomendation Code Editor

Visual Studio Code

### Recomendation Extension

- Thunderclient

## Initial Setup

- Clone Project ini ( Direkomendasikan menggunakan SSH )

> `git clone git@github.com:magang-mknows/ai-credit-scoring`

## Install Python

- Anda perlu menginstall dulu Python ( Direkomendasikan menggunakan Python versi 3.9 )

> silahkan akses link berikut untuk instalasi `https://www.python.org/downloads/release/python-3916/`

## Aktifkan terlebih dahulu ENV

- membuat environment menggunakan perintah berikut

> `python -m venv env`

- aktivasi environment menggunakan perintah berikut

> `. env/bin/activate`

## Install Dependency

- Pasang Dependency

> `pip install -r requirements.txt`

## Run Development Server

- Project bisa dijalankan dengan metode berikut

> `python app.py`


## Development with Docker

Docker harus di pasang dulu jika belum ada

- Pasang Docker bisa di unduh di https://docker.com

- Setup Docker

> `docker compose up`



