### ESSA APKA

Zwykłe readme jest za długie ale jakby coś nie działało to jest tutaj - https://pastebin.com/3MdUaGHg

#### 1 - Odpalanie Metro
Po pobraniu projektu wchodzisz w terminalu w roota projektu i odpalasz bundler Metro.

```bash
   npm start
```

Ten proces w terminalu bedzie chodził cały czas więc polecam odpalić w osobnym oknie cmd.

#### 2 - Emulator Android Studio
Jak już Metro jest odpalone to wchodzisz do Android Studio i otwierasz folder `./android` jako projekt. 
Jedyne co powinno widzieć Android Studio to pliki Gradle.
Próbujesz odpalić emulator i powinno działać.

---

#### Troubleshooting
U mnie osobiście emulator wypierdalał bo Gradle sie nie chciał zsyncować.

2 rzeczy zrobiłem, które mi pomogły.

1. Ustawienie nowej zmiennej środowiskowej `JAVA_HOME` o wartości `C:\Program Files\Android\Android Studio\jbr`. Jeżeli macie Android Studio pobrane gdzieś indziej to zmieniacie ścieżkę. On potrzebuje dostępu do Javy Androidowej i zbiera ją z `PATH`.
2. Pobranie najnowszej wersji Android Studio.