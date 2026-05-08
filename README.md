# HRTI GUI Downloader

Poštovana zajednice,
predstavljam vam svoj prvi projekt rađen uz pomoć AI-a.

Ovaj projekt je GUI verzija HRTI downloader skripte napravljena kako bi korištenje bilo jednostavnije i pristupačnije korisnicima koji ne žele raditi kroz terminal i ručno unositi komande.

> ⚠️ **VAŽNO**
> Ja sam uz pomoć AI-a napravio isključivo GUI dio aplikacije.
> Sav rad vezan za originalnu skriptu i backend logiku pripada administratoru **CB**.

---

# Funkcije

* Jednostavan GUI interfejs
* Login direktno kroz aplikaciju
* Pregled dostupnog sadržaja
* Preuzimanje sadržaja kroz GUI
* Log sistem za praćenje procesa
* Bez potrebe za ručnim komandama
* Jednostavno korištenje za početnike

---

# Potrebne zavisnosti

Da bi skripta pravilno funkcionirala, potrebno je instalirati sljedeće alate i biblioteke:

## Obavezno

* Python 3.10+
* yt-dlp
* pywidevine
* xmltodict
* requests

## Dodatni alati

* `mp4decrypt` (Bento4) → dodati u `PATH` ili `binaries/`
* `mkvmerge` (MKVToolNix) → dodati u `PATH` ili `binaries/`
* `aria2c` → opcionalno, za brže preuzimanje
* Widevine L3 CDM fajl (`device.wvd`)

---

# Instalacija biblioteka

Možete instalirati sve potrebne Python biblioteke jednom komandom:

```bash
pip install yt-dlp pywidevine xmltodict requests
```

---

# Pokretanje aplikacije

```bash
python main.py
```

---

# Screenshotovi

## Login

<img width="1182" height="812" alt="Login" src="https://github.com/user-attachments/assets/2ea11622-6b09-4842-b57e-e77361c00d4b" />

---

## Pregled sadržaja

<img width="1182" height="812" alt="Pregled" src="https://github.com/user-attachments/assets/df55f2fc-9d28-4941-ad99-9ba03c655758" />

---

## Preuzimanje

<img width="1182" height="812" alt="Preuzimanje" src="https://github.com/user-attachments/assets/7f5a0306-753f-467f-a304-1a4a40b02918" />

---

## Log sistem

<img width="1182" height="812" alt="Log" src="https://github.com/user-attachments/assets/81bf5ae4-bfb7-4380-8507-4e68c3332042" />

---

# Kako koristiti

1. Pokrenuti aplikaciju
2. Unijeti login podatke
3. Odabrati sadržaj
4. Pokrenuti download
5. Pratiti status kroz log prozor

---

# Napomena

Ovaj projekt je napravljen isključivo u edukativne svrhe.

Korisnik je odgovoran za način korištenja aplikacije i sadržaja koji preuzima.

---

# Autor

GUI by **Whowhen**

Backend/script credits: **CB**

---

# License

MIT License
