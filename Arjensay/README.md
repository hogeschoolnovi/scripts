# Vereisten

Om arjensay te kunnen gebruiken heb je 'cowsay' nodig. Op debian-based systemen kun je dit installeren met het commando:

```
sudo apt update && sudo apt install cowsay
```

Op arch-based systemen kun je dit installeren met het commando:

```
sudo pacman -Sy && sudo pacman -S cowsay
```

# Installatie

Stap 1:
Kopieer het 'arjen.cow' bestandje naar de map /usr/share/cows/.

Stap 2:
Maak het bash scriptje genaamd 'arjen' uitvoerbaar en zet het in de map /bin/

Stap 3:
Probeer het scriptje uit! Pipe de output van een commando naar het nieuwe 'arjen'-commando of gebruik de environment variable om arjen iets te laten zeggen.
