[Linux]: Ontwikkel omgeving *(PHP)*
=================================

Config is een basis lijst dat ik volg voor het opzetten van een nieuwe, Linux ontwikkel omgeving. Het helpt me met efficient werken in Git, Ruby, GitHub, Jekyll en nog veel meer. Zodat ik weer snel kan schrijven aan computer code.

## Checklist.

### 1. Voorbereiden van de terminal.

- Download en installeer git: `sudo apt-get install git`.
- Download en installeer tasksel: `sudo apt-get install tasksel`.
- Download en installeer LAMP server: `doe het via tasksel`.
- Download en installeer DBMS server: `sudo apt-get install mysql-server`.

### 2. Communicatie

- Download en installeer irssi: `sudo apt-get install irssi`.

### 3. Veilige Git(Hub) toegang.

- [Genereer een SSH sleutel](https://help.github.com/articles/generating-ssh-keys/).
- [Genereer een toegangs token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) Voor de terminal voor je GitHub account wanneer 2FA actief is.

### 4. Installeer je editor *(Atom)*.

- Installeer Atom.
- Voeg Spacegray UI thema toe en het Ocean Dark kleuren schema toe.
- Configureer `Atom` terminal commando's van Atom.app, open het menu en selecteer *Install Shell Commands*.

### 5. Download & installeer pakket beheerders.

All de `.phar` bestanden moet geplaatst worden in `/usr/local/bin/`. <br />
en voer na het downloaden dit commando: `sudo chown -x filename.phar` uit. vervang de **filename** met de naam van het gedownloade .phar bestand.

- Download composer: `curl -sS https://getcomposer.org/installer | php`
- Download ApiGen: `wget http://apigen.org/apigen.phar`
