# Shlepa Card

**Shlepa Card** — офлайн-кошелёк для карт лояльности. Работает в браузере, без интернета. Карты, штрихкоды и фото хранятся на телефоне.

## Возможности

- Добавление карт: название, номер, заметка, фото
- Сканирование штрихкода через камеру (EAN-13, EAN-8, UPC, CODE128)
- Фото карты прямо из приложения
- Генерация штрихкода из номера
- Нажмите на штрихкод — откроется на весь экран
- Полностью офлайн, данные в localStorage
- Работает на телефоне без установки

## Как установить

1. Скачайте `shlepa-card.html`
2. Откройте файл в браузере на телефоне
3. Добавьте на главный экран:  
   - **iPhone**: «Поделиться» → «На экран «Домой»»  
   - **Android**: Chrome → меню → «Установить приложение»

## Технологии

- HTML/CSS/JS (без сборщиков)
- JsBarcode — генерация штрихкодов
- BarcodeDetector API — сканирование
- LocalStorage — хранение

---

# Shlepa Card (English)

**Shlepa Card** — offline loyalty cards wallet. Works in browser, no internet needed. Cards, barcodes and photos are stored on your phone.

## Features

- Add cards: name, number, note, photo
- Scan barcode via camera (EAN-13, EAN-8, UPC, CODE128)
- Take a photo from within the app
- Generate barcode from card number
- Tap barcode for fullscreen view
- Fully offline, data in localStorage
- Works on phone like an app

## How to install

1. Download `shlepa-card.html`
2. Open the file in your phone browser
3. Add to home screen:  
   - **iPhone**: Share → "Add to Home Screen"  
   - **Android**: Chrome → menu → "Install app"

## Tech stack

- HTML/CSS/JS (no build tools)
- JsBarcode for generation
- BarcodeDetector API for scanning
- LocalStorage for persistence
