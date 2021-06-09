Środowisko -PyCharm(Język python)
Do bazy danych wchodzimy poprzez localhost/phpmyadmin
Baza danych stworzona za pomoca programu Xampp(MySQL lokalnie, jeżeli Apache nie działa trzeba kliknąć przycisk "Config/http.conf" i zmieniamy linijke "Listen 80" na 81)
Jeżeli po tym zabiegu nie działa localhost to trzeba zmienić w localhoscie port z 80 na 81
Baza danych posiada przykładowe dane już wcześniej wprowadzone
Trzeba stworzyć baze danych o nazwie aplikacja i zimportować do niej tabele, które znajaduja się w repozytorium

Żeby sprawdzić działanie bazy danych można użyć opcji rejestracji, logowania i oceniania użytkownika
Logowanie:
-Baza poprosi o podanie prawidłowego loginu i hasła(jeżeli się wszystko zgadza to przechodzimy do interfejsu, jeżeli nie to aplikacja się wyłączy)
Rejestracja:
-Baza poprosi o podanie loginu, hasła i emaila i po wciśnięciu przycisku zarejestruj cofnie nas do strony startowej, a nasze dane zostaną wpisane do bazy
Ocenianie:
W rubryce ocenianie w oknie "Konkurs" trzeba wpisac odpowiedni login użytkownika i ocenę(Baza danych dopisze ocenę i doda do poprzednich i policzy średnią)


Folder z plikami z repozytorium trzeba dorzucić w ten sam folder gdzie znajduje się plik z rozszerzeniem .py

Login      Hasło      email
wotjula wojtula123 xyz@wp.pl
admin   admin123   xyzc@wp.pl
ktos    ktosa      ktos@wp.pl