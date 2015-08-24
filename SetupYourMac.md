Instruktioner för att förbereda din mac för programmering
## 1 Installera Homebrew ##

Homebrew är en pakethanterare, det vill säga ett program som används för att hämta, kompilera, och installera program.

1. Starta terminalen
2. Hämta och installera homebrew: `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
3. Skriv in ditt lösenord för datorn (inget kommer synas på skärmen) och tryck på enter

### 1.1 Installera X-Code Command Line Tools ###

Om ett fönster dyker upp och ber dig installera Xcode Command Line Tools, klicka på `Install`.

Om det inte dyker upp, skriv `xcode-select --install`

När Xcode Command Line Tools installerats klart, markera kommandopromptsfönstret och tryck på `enter`.

### 1.2 brew doctor ###

När installationen är klar, kör `brew doctor`.

Det kan dyka upp ett par varningar. Följande varningar är normala:

	* Outdated version of /usr/bin/install_name_tool
	* Git could not be found in your path
	* No developer tools installed

Oavsett om fu fått några varningar eller inte, ska du fortsätta med följande steg.

### 1.3 Installera git ###

Git är ett versionshanteringssystem som används av bl.a. homebrew.

Skriv `brew install git` 

Git kan ge en varning, ignorera den, vi fixar den lite senare.

## 2 Byt shell till zsh ##

I terminalen kan man köra olika "shells". Som standard i OS X kör man bash. Vi kommer byta till zsh; ett shell med mer funktionalitet.

### 2.2 Installera oh-my-zsh ###

oh-my-zsh är ett paket med bra inställningar för zsh. 

1. klistra in `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
2. Skriv in ditt lösenord för datorn (inget kommer synas på skärmen) och tryck på `enter`.
3. Döda terminalen: `cmd Q`.
4. Starta terminalen igen.
5. Klistra in `echo export PATH='/usr/local/bin:$PATH' >> ~/.zshrc`
6. Döda terminalen (`cmd Q`) igen.
7. Starta terminalen igen.
8. Njut av zsh.


## 5 Installera PyCharm ##

PyCharm är en utvecklingsmiljö gjord för att skriva python-program i.
Surfa till `https://www.jetbrains.com/pycharm/download/` och ladda ner och installera PyCharm Professional Edition
Ni kommer att få licensnycklar

### 5.1 Konfigurera PyCharm ###

## TODO




