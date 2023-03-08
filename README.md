Esercizio: Laravel Primi Passi

Nome Repo: laravel-primi-passi

Descrizione:

Primi passi con questo fantastico framework che è Laravel!

Per prima cosa, creiare un nuovo progetto Laravel 9, utilizzando questo comando:
- composer create-project laravel/laravel:^9.2 . -> se è stata già creata la cartella vuota
- composer create-project laravel/laravel:^9.2 laravel-primi-passi  -> se NON è stata già creata la cartella vuota

Se NON è stata creata la cartella vuota:

Al termine dell'installazione, entriare nella cartella del progetto eseguire il seguente comando
- cd laravel-primi-passi

Poi avviare l'artisan serve con uno di questi due comandi:
- php artisan serve
- php -S localhost:8000 -t public

A questo punto, iniziare a prendere confidenza con le rotte e le views:
- Cancellare la view welcome.blade.php e creare una nostra homepage
- Fare sì che la rotta / visualizzi home.blade.php
- Inizialmente stampare solo un Hello World, poi si può aggiungere quello che vogliamo.

BONUS:

Creare più di una pagina e visualizzare un header menu con i link di tutte le pagine, utilizzando la funzione: route()