# Ruby / RSpec Test Kata

Szablon projektu `Ruby` / `RSpec` wykorzystywanego na warsztatach Test Kata.

## Instalacja Ruby

#### OS X, Linux

Do zainstalowania odpowiedniej wersji `Ruby` na systemach `OS X` i `Linux`
najlepiej użyć narzędzia `rvm`:

    curl -#L https://get.rvm.io | bash -s stable

Na `OS X` niezbędne jest zainstalowanie Xcode wraz z Command Line Tools,
na `Ubuntu` niezbędne jest zainstalowanie przynajmniej pakietu
`build-essential`.

#### Windows

Do zainstalowania `Ruby` na systemach `Windows` można użyć
[http://rubyinstaller.org](http://rubyinstaller.org).

## Przy

Po zainstalowaniu `Ruby` w wersji 2.0.0-p195 niezbędne jest zainstalowanie
wszystkich zależności:

    gem install bundler
    bundle install

Poprawność instalacji można sprawdzić uruchamiając komendę:

    rspec