# Linux

W systemie linux najwygodniej będzie się nam pracowało z `Terminator'em`, od standardowej konsoli wyróżnia się możliwością tworzenia nowych zakładek czy ich dzielenia.

![Screenshot](http://2.bp.blogspot.com/-DYWH3IZubRI/TrmFBPxmyEI/AAAAAAAAAAA/nBGoP3U3ae4/s320/terminator-mad.png)

## Instalacja terminala
  W naszym terminalu wystarczy użyć
  ```bash
sudo apt-get install terminator
  ```
  I nasz terminal jest już gotowy do działania.


## Oh-my-zsh

Jest to framework, zawierający wiele udogodnień dla naszej konsoli

![Screen](https://cloud.githubusercontent.com/assets/2618447/6316862/70f58fb6-ba03-11e4-82c9-c083bf9a6574.png)

### Instalacja

W terminalu

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Resetujemy nasz terminal i wszystko powinno działać.

Jeśli jednak coś jest nie tak, musimy upewnić się czy nasz terminal używa opcji ``Run command as login shell``, którą możemy sprawdzić w preferencjach terminala

![Screen](https://image.ibb.co/hs8NKQ/Screenshot_from_2017_09_26_23_59_21.png)
