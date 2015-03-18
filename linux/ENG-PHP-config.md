[Linux]: Development Environment *(PHP)*
=================================

Config is a basic checklist I follow to set up a new Linux development environment. s
It gets me up to speed with Git, Ruby, GitHub, Jekyll, and more so I can more quickly get back to coding.

## Checklist

### 1. Prep the terminal.

- Download and install git:         `sudo apt-get install git`.
- Download and install tasksel:     `sudo apt-get install tasksel`.
- Download and install LAMP server: `do it via tasksel`
- Download and install DBMS System:  `sudo apt-get install mysql-server`

### 2. Communication.

- Download and install irssi: `sudo apt-get install irssi`

### 3. Secure Git(Hub) access.
- [Generate a SSH key](https://help.github.com/articles/generating-ssh-keys/).
- [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub  account when 2FA is. enabled

### 4. Setup editor *(Atom)*.

- Install Atom itself
- Add Spacegray UI theme and Ocean Dark color scheme.
- Enable `Atom` terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*.

### 5. Download & install package managers.

All the `.phar` files are placed and located in the `/usr/local/bin/`. <br />
And make sure if u do `sudo chown +x filename.phar`, replace **filename** with the name of the downloaded phar file.

- Download composer:  `curl -sS https://getcomposer.org/installer | php`
- Download ApiGen:    `wget http://apigen.org/apigen.phar`
