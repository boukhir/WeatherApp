# Weather App - Test technique pour un stage chez Decalog
## Utilisation
Pour utiliser ce site localement, votre interpréteur PHP doit avoir accès aux dll openssl et intl.
Pour cela il suffit de décommenter les extensions *php_openssl.dll* et *php_intl.dll* de votre fichier *php.ini*.

## Sources imposées
- One Call API 3.0 pour obtenir des données météorologiques d'un point géographique : https://openweathermap.org/api/one-call-3
- Le thème Flatly de Bootswatch pour le style principal du site : https://bootswatch.com/flatly/

## Sources externes
Pour mener à bien ce projet j'ai utilisé les différentes sources d'usage libre préséntées ci-dessous :
- Geocoding API pour obtenir les coordonnées GPS (latitude et longitude) d'une ville donnée : https://openweathermap.org/api/geocoding-api
- La librairie Weather Icons de Erik Flowers pour les icônes météo non animées : https://erikflowers.github.io/weather-icons/
- Les icônes météo animées (SVG) de James Thomson : https://codepen.io/getreworked/pen/GpBpmg
- Les exemples d'utilisation de la fonction PHP *Locale::getDisplayRegion* du manuel PHP : https://www.php.net/manual/en/locale.getdisplayregion.php
