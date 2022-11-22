Selles repositooriumis on 5 erineva skripti:
- apache2.yml : Kirjutatud on skript, mis installib antud serverile Apache2 serveri ja redigeerib index.html faili "public_html".
- mkdir.yml : Kirjutatud on skript, mis loob root kausta kataloogi, mille sisse laetakse mysql repositooriumi pakett ning installitakse
- mysql-user.yml : Kirjutatud on skript, mis loob root kausta login faili .my.cnf, kus on mysql login andmed, ning antakse ka õigused kõikide privileegidega mysql kasutajale root.
- phppaigaldus.yml : Kirjutatud on skript, mis installib antud serverile PhpMyAdmin sevrer ning vahetatakse PMA kausta omanik ning muudetakse õigusi selle kataloogil.
- wordpress.yml : Kirjutatud on skript, mis installib WordPress tar paketi ja pakib selle lahti antud kataloogi. Kausta omanik vahetati ära ja kopeeriti config fail ning samuti vahetati ka andmebaasi parool, user ja database.
