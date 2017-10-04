# MacOs

Pracując na systemie MacOs warto zainteresować się `iterm2`, który bardzo dobrze zastępuje domyślną konsolę.
Oferuje on nam:
  - Możliwość dzielenia paneli
  - Wyszukiwanie
  - Większą możliwość konfiguracji

![Screen](https://www.iterm2.com/img/logo2x.jpg)


# oh-my-zsh

Również jak w przypadku systemu linux, polecam instalacje `oh-my-zsh`

>Oh-my-zsh, który będzie zarządzał nam
>konfiguracją oraz ułatwi instalacje pluginów. Dodatkowo posiada wiele zainstalowanych udogodnień jak funkcje i aliasy Git'a.


Instujemy go w bardzo podobny sposób, przez użycie jednej komendy

```bash
curl -L https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh | sh
```

Następnie po zainstalowaniu, musimy zmienić domyślną powłokę konsoli i użyjemy w tym celu polecenia

```bash
chsh -s /usr/local/bin/zsh
```
