# Demonstrace přenosu hodnot mezi skripty A a B

Tento projekt ukazuje několik způsobů, jak předat hodnotu ze skriptu `a.php` do skriptu `b.php`.

## Použité metody
1. **GET**
   - Hodnota je přenesena jako parametr v URL (`b.php?value=...`).
   - Vhodné pro jednoduché a veřejné přenosy.

2. **POST**
   - Hodnota je přenesena jako součást těla požadavku HTTP.
   - Bezpečnější, protože hodnota není viditelná v URL.

3. **Path Info**
   - Hodnota je přenesena jako součást cesty URL (`b.php/{hodnota}`).
   - Využívá atribut `PATH_INFO` serveru.

## Jak spustit
1. Umístěte soubory na webový server podporující PHP.
2. Otevřete `a.php` v prohlížeči.
3. Vyzkoušejte různé metody odeslání hodnoty na `b.php`.
