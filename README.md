# final-project-sem-II-Programming-in-JAVA-
Program demonstruje przykład wielowątkowej aplikacji w języku Java, która 
wykorzystuje synchronizację do wymiany danych między wątkami. Oto krótki opis 
programu oraz instrukcje dotyczące jego użycia po uruchomieniu: 

Opis programu. 
Klasy Provider i Receiver: Te klasy służą odpowiednio do dostarczania i odbierania 
danych. Oba korzystają ze wspólnego obiektu o nazwie "Action" (klasa Action) do 
synchronizacji i wymiany danych między wątkami. 

Klasa Action: Ta klasa działa jako mediator i zapewnia zsynchronizowany dostęp do 
danych przekazywanych między wątkami Provider i Receiver. 

Główna klasa Main: W tej klasie tworzone są instancje klas Provider i Receiver, które 
korzystają z tego samego obiektu klasy Action. Następnie dla każdego z tych obiektów 
tworzony jest osobny wątek (Thread), a oba wątki są uruchamiane. 

Jak korzystać. 
Po uruchomieniu programu Main, proszę postępować zgodnie z instrukcjami 
widocznymi w konsoli. Pierwszym krokiem będzie wprowadzenie adresu IP serwera. 
Zalecam wprowadzenie adresu lokalnego 127.0.0.1. Proszę napisać jedną wiadomość, 
a następnie ponownie uruchomić program, podając inną nazwę użytkownika. Będzie 
można zobaczyć swoją wcześniejszą wiadomość i drugą.
