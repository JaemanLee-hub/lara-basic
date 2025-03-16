# lara-basic

간단한 Laravel + Breeze + Sail 기본 세팅 프로젝트입니다.

## 🛠️ 기술 스택

- Laravel 10.x
- Breeze (Blade + React)
- Docker (Sail)
- MySQL
- Tailwind CSS

## 📦 설치 방법

```bash
git clone git@github.com:JaemanLee-hub/lara-basic.git lara-app
cd lara-basic
cp .env.example .env
sail up -d
sail artisan migrate
sail npm install
sail npm run dev
