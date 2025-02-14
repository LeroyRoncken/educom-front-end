## Front End Track

Eerste opdrachten behorende bij het uitstroom profiel ["Front end"](https://e-learning.educom.nu/front-end/)


# Design Tokens

Stappen om design-tokens.json om te zetten naar _tokens.scss:

    - Voor de eerste keer, installeer de nodige tool json-to-scss, doe dit globaal, zodat die overal beschikbaar is. Als deze nog niet geïnstalleerd is, voer dan het volgende commando in in de terminal:
        npm install json-to-scss --global

    - In de terminal, selecteer de project root folder met cd (change directory) (de folder waar index.html staat):
        cd C:\xampp\htdocs\educom-front-end

    - Gebruik eventueel dir om te controleren of het de juiste folder is:
        dir

    - Gebruik het volgende commando om de JSON naar SCSS om te zetten, check de namen van de folders en files en pas ze zo nodig aan:
        json-to-scss resources\tokens\design-tokens.json resources\style\tokens\_tokens.scss
