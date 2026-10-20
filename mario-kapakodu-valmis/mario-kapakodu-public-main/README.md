# Mario Käpakodu

Käpakodu on loomade varjupaiga veebirakenduse kasutajaliidese õppeprojekt. Praegune versioon kasutab HTML-i, CSS-i ja Bootstrap 5 komponente. PHP-d ega andmebaasi selles etapis ei kasutata.

## Tehnoloogiad

- HTML5
- CSS3 (`assets/css/style.css`)
- Bootstrap 5.3 CDN-i kaudu
- Font Awesome ikoonid CDN-i kaudu

## Kaustastruktuur

```text
mario-kapakodu/
├── index.html             # Avaleht
├── animal.html            # Looma detailvaade
├── all_animals.html       # Loomade nimekiri
├── contact.html           # Kontaktileht
├── login.html             # Sisselogimise vaade
├── README.md
├── .gitignore
├── admin/
│   ├── index.html         # Administraatori avaleht
│   ├── animals.html       # Loomade haldamine
│   └── animal_add.html    # Looma lisamise/muutmise vorm
└── assets/
    ├── css/style.css
    └── images/            # Logo, bänner ja loomade pildid
```

## Käivitamine

1. Laadi projekt arvutisse ja paki ZIP-fail lahti.
2. Ava projekti kaust Visual Studio Code'is.
3. Ava `index.html` brauseris või kasuta VS Code'i Live Serveri laiendust.
4. Administraatori vaated asuvad `admin/` kaustas.

Bootstrap ja Font Awesome laaditakse CDN-i kaudu, seega on nende kuvamiseks vaja internetiühendust.

## Vaated

- `index.html` – avaleht ja tutvustus
- `all_animals.html` – loomade nimekiri
- `animal.html` – looma detailvaade
- `contact.html` – kontaktandmed ja kontaktivorm
- `login.html` – sisselogimisvorm
- `admin/index.html` – halduspaneeli ülevaade
- `admin/animals.html` – loomade haldamise tabel
- `admin/animal_add.html` – looma lisamise ja muutmise vorm

## HTML-i valideerimine

Kontrolli HTML-faile [W3C HTML validaatoriga](https://validator.w3.org/). Laadi valideerimiseks fail üles või kasuta valideerimise URL-i. Paranda kõik vead ja kontrolli lehti uuesti.

## Git ja GitHub

```bash
git init
git add .
git commit -m "Valmis Käpakodu kasutajaliides"
git branch -M main
git remote add origin https://github.com/SINU-KASUTAJANIMI/mario-kapakodu.git
git push -u origin main
```

Asenda `SINU-KASUTAJANIMI` enda GitHubi kasutajanimega. Enne `git remote add` käsku loo GitHubis uus hoidla.

## Piirangud

Tegu on kasutajaliidese prototüübiga. Vormid ja haldusvaated ei salvesta andmeid serverisse, sest PHP-d ega andmebaasi pole veel lisatud.
