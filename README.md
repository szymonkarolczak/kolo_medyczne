# kolo_medyczne
Aplikacja Koło Medyczne - Laravel


------------------------------------

# Strukura widoków Blade

Laravel
    |
    Resources
        |
        Views
            |
            welcome.blade.php -> Strona główna projektu
            |
            Admin
                |
                app.blade.php -> Plik definiujący widoki admin
                dashboard.blade.php -> Strona główna panelu admina
                menu.blade.php -> Menu panelu admina
            |
            Auth
                |
                login.blade.php -> Strona logowania
                register.blade.php  -> Strona rejestracji
                verify.blade.php -> Strona weryfikacji hasła
                |
                Passwords
                    |
                    confirm.blade.php -> Potwierdzenie hasła
                    email.blade.php -> Restart hasła e-mail
                    reset.blade.php -> Restart hasła    
            |
            Layouts
                |
                app.blade.php -> Plik główny projektu


# CSS / JavaScript / Images

Laravel
    |
    Public
        |
        CSS
            |
            style.css
        |
        JS
            |
            script.js
        |
        Img

# Kontrolery 

Laravel
    |
    App
        |
        Http
            |
            Controllers
                    |
                    HomeController.php
                    LoginController.php
                    RegisterController.php
                    PassRecoveryController.php
                    2wayAuthController.php
                    

---------------------
#   GIT 

Przed rozpoczęciem pracy wykonujemy komendę "git pull" do pobrania aktualnej wesji projektu

Commity wykonujemy z flagą -m / Opis zaczynamy zawsze z duzej litery / Opisy po angielsku / Do 50 znaków

Po skończonej pracy wrzucamy commity na repozytorium GitHub komendą "git push"

#   END GIT
---------------------

---------------------
# Podgląd i operacje na PHP ARTISAN

Podgląd:
        1. Prawy przcisk myszy na folderze "laravel" i odpalasz terminal 
        2. W terminalu wklep "php artisan serve"
        3. Wybierz sobie przeglądarkę

# END
--------------------

