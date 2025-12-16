# Project installeren (Laravel)

Volg de onderstaande stappen om het project correct te installeren.

---

## 1. Project clonen
Clone het project via Git:

```bash
git clone <repository-url>
```

---

## 2. Dependencies installeren
Ga in de terminal naar de map van het zojuist gedownloade project en voer uit:

```bash
composer install
```

---

## 3. `.env` bestand aanmaken
Kopieer het voorbeeldbestand en hernoem het naar `.env`:

```bash
cp .env.example .env
```

**Resultaat:**
- `.env`
- `.env.example` (voor hergebruik)

---

## 4. Applicatiesleutel genereren
Genereer de Laravel applicatiesleutel met:

```bash
php artisan key:generate
```

---

✅ **Je project is nu klaar voor gebruik.**
