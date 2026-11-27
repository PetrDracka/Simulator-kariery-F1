## 1. Hosting a prostředí
* **Poskytovatel:** Školní server (prostor a přístupové údaje přiděluje škola).
* **Serverové prostředí:** Webhosting podporující skriptovací jazyk **PHP** a relační databázi **MySQL / MariaDB**, což plně pokrývá technologické požadavky aplikace.

## 2. Postup nasazení a publikace
1. **Příprava souborů:** Finální zdrojové kódy (HTML, CSS, PHP skripty) budou zkontrolovány a připraveny v repozitáři.
2. **Nahrání na server:** Pomocí FTP klienta (např. FileZilla) se obsah složky zkopíruje do kořenového adresáře webhostingu přiděleného školou.
3. **Konfigurace databáze:** Přes webové rozhraní (např. phpMyAdmin) se vytvoří potřebná databáze a naimportuje se SQL schéma s tabulkami (`tymy`, `jezdci`, `zavody`, `vysledky`).
4. **Testování:** Provede se ověření funkčnosti připojení k databázi přes PHP a otestuje se správné zobrazení stránek v prohlížeči.
