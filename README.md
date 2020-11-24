# Selenium

HTTP GET request tesztelés Apache Jmeter alkalmazással.

Ésszerű terhelés: 200 felhasználó (GET request) másodpercenként egy közepes méretű weboldal esetén magasnak számít, de nem kiemelkedő.

Ekkora forgalmat egy NGINX webszerver lazán ki kell tudjon szolgálni egyetlen processzormaggal is. Apache szerver már izzad, főleg ha több .htaccess file is található az elérési útvonalon belül.

Tesztelésre saját webszervert használtunk: 1 vCPU, 1 GB RAM, 25 GB SSD. NGINX webszerver PHP-FPM társaságában.

http://selenium.fabiangabor.com/
