Na zakończenie intensywnego kursu "Python od podstaw - Kurs 291 godzin, Software Development Academy" stworzyliśmy projekt końcowy, którym jest Calculator-BMI. 
To był pierwszy projekt gdzie mieliśmy okazję pracować w grupie. Pracowaliśmy w 4- osobowym zespole. Na początku projektu końcowego wspólnie opracowaliśmy plan,
jak i etapy naszej pracy, a także podział zadań. Podczas 42 godzinnej pracy mieliśmy możliwość pracy z GitHubem. 
Nasz projekt jest to aplikacja webowa, która oblicza wskaźniki: BMI (Body Mass Index) oraz Kalkulator Kalorii na podstawie podanych przez użytkownika danych. 
Aplikacja została zaimplementowana przy użyciu frameworka Django.

==================================================================================================================================================================


Instalacja

1. Sklonuj repozytorium na swój lokalny komputer:

git clone https://github.com/TomaszCiesla/Calculator-BMI

2. Przejdź do katalogu projektu:

cd calculator-bmi

3. Utwórz i aktywuj wirtualne środowisko:

python -m venv venv
source venv/bin/activate

4.Zainstaluj wymagane zależności:

pip install -r requirements.txt

5. Wykonaj migracje bazy danych:

python manage.py migrate

6. Uruchom serwer deweloperski:

python manage.py runserver

7. Aplikacja będzie dostępna pod adresem http://localhost:8000/.

==================================================================================================================================================================

Użycie
1. Otwórz przeglądarkę internetową i przejdź do http://localhost:8000/.
2. Wprowadź swoją wagę (w kilogramach) i wzrost (w metrach) w odpowiednie pola.
3. Kliknij przycisk "Click here to check BMI".
4. Wprowadź swoją wagę (w kilogramach) i wzrost (w metrach), wiek i wybierz płeć oraz poziom aktywności fizycznej w odpowiednie pola Calories Calculator.
5. Kliknij przycisk "Clalculate Calories"
6. Aplikacja wyświetli Twoje BMI oraz interpretację wyniku, jak również informację dotyczącą spożywania kalorii.

==================================================================================================================================================================

Struktura projektu

.
├── calculator-bmi
│   ├── templates
│   │   └── my_site
│   │       └── base.html
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── .gitignore
├── manage.py
└── requirements.txt

calculator-bmi - główny katalog aplikacji.
templates - zawiera szablony HTML.
base.html - szablon strony głównej.
settings.py - plik konfiguracyjny Django.
urls.py - definiuje ścieżki URL.
wsgi.py - plik konfiguracyjny dla serwera WSGI.
manage.py - skrypt do zarządzania projektu.

==================================================================================================================================================================

Technologie
Python 3.11
Django 4.2.2

==================================================================================================================================================================

Autor:
Tomasz Dymek
E-mail: tomasdymek@gmail.com
GitHub: tomasdymek

Autor:
Sylwia Pokrzywa
sylwia.pokrzywa@gmail.com
GitHub: sylwiapokrzywa

Autor:
Tomasz Cieśla
E-mail: tomasz.ciesla81@gmail.com
GitHub: TomaszCiesla

Autor:
Agnieszka Lenart
E-mail: molines@op.pl
GitHub: AgnieszkaLenart24
