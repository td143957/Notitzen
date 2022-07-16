# Notitzen
Alle Code Befehle und  Linke


Hackingsseite:
https://owasp.org/www-project-webgoat/
....................................................................................
HTML:
https://wiki.selfhtml.org/wiki/Wie_fange_ich_an%3F

Git
https://de.wikipedia.org/wiki/Git

Linux/Ubuntu
https://wiki.ubuntuusers.de/Einsteiger/

Docker ID:
ID :maladho94
pass:0Thierno733
tmdjialoh@gmail.com

Playliste Docker:
https://labs.play-with-docker.com/

Befehle 1 :Dockerfile
git clone https://github.com/thenativeweb/techlounge-docker
cd techlounge-docker/
ls -l
cd 01-grundkonzepte/
ls-l
clear
cat Dockerfile

Befehle 2: Image bauen
docker build -t apache2 .
clear
docker images

Befehle 3: Container starten

benutzer:docker login -u maladho94
Passwort:70219853-ce65-46a3-948a-da67c3c8ad7b





So wird die Name ein Docker Image angegeben und somit ein Container gestattet:
$docker run hello-word
 
So wird wird gezeigt ,welche images lokal vorhanden sind:

$docker images

Container interaktiv starten :(danach befindet man sich in der Linux Container)

$docker run -it ubumtu 

Container auflisten , die gerade laufen:

$ps

Befele testen:(ob ein curl instaliert ist)

$curl

$pt-get update

Curl instalieren:

$apt-get install curl 

Abfrage machen:
$y

Curl aufrufen :
$curl 
$curl https://thenativeweb.io
$exit
$docker run -it ubumtu 
$curl (im Gegensatz zu virtuel Machine ,wird  bei Container wird nach exit 
sofort deinstalieert)

Container auflisten , die gerade laufen:

$ps

Auch beendete Container auflisten:

$docker ps -a

Container neu starten:
Optionen zeigen:
$docker start --help
Befehl plus die erste Ziffer der Container-ID

$docker start container -i 996
$curl
$history

Container im Hintergrund starten:

Browswer starten: 
$start http://localhost:8080

$curl.exe http://localhost:8080

Logausgaben:(Ausgabe der apache prozess anzeigen lassen)

$docker logs dff
 
Zeitstempel anzeigen:
$docker logs -t dff 

Docker Container beenden:

$ docker kill container_id
$docker ps
$docker ps -a

Docker Container stopen:

$ docker stop container_id
$docker ps
$docker ps -a

Beendete Container starten:

$docker start c618
$docker ps

Container automatische löschen:
$docker ps -a
$docker run --rm -it ubuntu
Datei anliegen -> $touch test.txt
               -> $ls
               -> $ exit
$docker ps -a

Folge 4: Images bauen

Visual Studio mit 
$ Code . 
aufrufen 

Docker Image von Visual Studio auf hub.docker.com herunterladen:(Eigenes Image auf den Docker Hub)

$docker images
$docker tag hey maladho94/hey
$docker push maladho94/hey

Hostsystem aufräumen:
-> Erst Mal in Docker App
->Images
->Links auf Clean up
->in der Mitte auf Dangling 
->Remove
->Done
Alternativ:
->Links auf Clean up
->in der Mitte auf Unused 


Ordner über komandozeile erstellen :

-> Ein Ordner zurück cd ..
-> mkdir OrdnerName
-> cd OrdnerName
-> Mit code . ,kann man visual Studio in dem Ordner aufmachen

Änderungen in GIT hinzufügen:

->cd  OrdnerName
->git init 
->code .
->git status 
->
->
23.12.21
Dockerfile in Visual Studion erstellen lassen:


Git mit Visual Studio anwenden



So wird die Name ein Docker Image angegeben und somit ein Container gestattet:
$docker run hello-word
 
So wird wird gezeigt ,welche images lokal vorhanden sind:

$docker images

Container interaktiv starten :(danach befindet man sich in der Linux Container)

$docker run -it ubumtu 

Container auflisten , die gerade laufen:

$ps

Befele testen:(ob ein curl instaliert ist)

$curl

$pt-get update

Curl instalieren:

$apt-get install curl 

Abfrage machen:
$y

Curl aufrufen :
$curl 
$curl https://thenativeweb.io
$exit
$docker run -it ubumtu 
$curl (im Gegensatz zu virtuel Machine ,wird  bei Container wird nach exit 
sofort deinstalieert)

Container auflisten , die gerade laufen:

$ps

Auch beendete Container auflisten:

$docker ps -a

Container neu starten:
Optionen zeigen:
$docker start --help
Befehl plus die erste Ziffer der Container-ID

$docker start container -i 996
$curl
$history

Container im Hintergrund starten:

Browswer starten: 
$start http://localhost:8080

$curl.exe http://localhost:8080

Logausgaben:(Ausgabe der apache prozess anzeigen lassen)

$docker logs dff
 
Zeitstempel anzeigen:
$docker logs -t dff 

Docker Container beenden:

$ docker kill container_id
$docker ps
$docker ps -a

Docker Container stopen:

$ docker stop container_id
$docker ps
$docker ps -a

Beendete Container starten:

$docker start c618
$docker ps

Container automatische löschen:
$docker ps -a
$docker run --rm -it ubuntu
Datei anliegen -> $touch test.txt
               -> $ls
               -> $ exit
$docker ps -a

Folge 4: Images bauen

Visual Studio mit 
$ Code . 
aufrufen 

Docker Image von Visual Studio auf hub.docker.com herunterladen:(Eigenes Image auf den Docker Hub)

$docker images
$docker tag hey maladho94/hey
$docker push maladho94/hey

Hostsystem aufräumen:
-> Erst Mal in Docker App
->Images
->Links auf Clean up
->in der Mitte auf Dangling 
->Remove
->Done
Alternativ:
->Links auf Clean up
->in der Mitte auf Unused 


Ordner über komandozeile erstellen :

-> Ein Ordner zurück cd ..
-> mkdir OrdnerName
-> cd OrdnerName
-> Mit code . ,kann man visual Studio in dem Ordner aufmachen

Änderungen in GIT hinzufügen:

->cd  OrdnerName
->git init 
->code .
->git status 
->
->
23.12.21
Dockerfile in Visual Studion erstellen lassen:


Git mit Visual Studio anwenden




So wird die Name ein Docker Image angegeben und somit ein Container gestattet:
$docker run hello-word
 
So wird wird gezeigt ,welche images lokal vorhanden sind:

$docker images

Container interaktiv starten :(danach befindet man sich in der Linux Container)

$docker run -it ubumtu 

Container auflisten , die gerade laufen:

$ps

Befele testen:(ob ein curl instaliert ist)

$curl

$pt-get update

Curl instalieren:

$apt-get install curl 

Abfrage machen:
$y

Curl aufrufen :
$curl 
$curl https://thenativeweb.io
$exit
$docker run -it ubumtu 
$curl (im Gegensatz zu virtuel Machine ,wird  bei Container wird nach exit 
sofort deinstalieert)

Container auflisten , die gerade laufen:

$ps

Auch beendete Container auflisten:

$docker ps -a

Container neu starten:
Optionen zeigen:
$docker start --help
Befehl plus die erste Ziffer der Container-ID

$docker start container -i 996
$curl
$history

Container im Hintergrund starten:

Browswer starten: 
$start http://localhost:8080

$curl.exe http://localhost:8080

Logausgaben:(Ausgabe der apache prozess anzeigen lassen)

$docker logs dff
 
Zeitstempel anzeigen:
$docker logs -t dff 

Docker Container beenden:

$ docker kill container_id
$docker ps
$docker ps -a

Docker Container stopen:

$ docker stop container_id
$docker ps
$docker ps -a

Beendete Container starten:

$docker start c618
$docker ps

Container automatische löschen:
$docker ps -a
$docker run --rm -it ubuntu
Datei anliegen -> $touch test.txt
               -> $ls
               -> $ exit
$docker ps -a

Folge 4: Images bauen

Visual Studio mit 
$ Code . 
aufrufen 

Docker Image von Visual Studio auf hub.docker.com herunterladen:(Eigenes Image auf den Docker Hub)

$docker images
$docker tag hey maladho94/hey
$docker push maladho94/hey

Hostsystem aufräumen:
-> Erst Mal in Docker App
->Images
->Links auf Clean up
->in der Mitte auf Dangling 
->Remove
->Done
Alternativ:
->Links auf Clean up
->in der Mitte auf Unused 


Ordner über komandozeile erstellen :

-> Ein Ordner zurück cd ..
-> mkdir OrdnerName
-> cd OrdnerName
-> Mit code . ,kann man visual Studio in dem Ordner aufmachen

Änderungen in GIT hinzufügen:

->cd  OrdnerName
->git init 
->code .
->git status 
->
->
23.12.21
Dockerfile in Visual Studion erstellen lassen:


Git mit Visual Studio anwenden

22.12.21

So wird die Name ein Docker Image angegeben und somit ein Container gestattet:
$docker run hello-word
 
So wird wird gezeigt ,welche images lokal vorhanden sind:

$docker images

Container interaktiv starten :(danach befindet man sich in der Linux Container)

$docker run -it ubumtu 

Container auflisten , die gerade laufen:

$ps

Befele testen:(ob ein curl instaliert ist)

$curl

$pt-get update

Curl instalieren:

$apt-get install curl 

Abfrage machen:
$y

Curl aufrufen :
$curl 
$curl https://thenativeweb.io
$exit
$docker run -it ubumtu 
$curl (im Gegensatz zu virtuel Machine ,wird  bei Container wird nach exit 
sofort deinstalieert)

Container auflisten , die gerade laufen:

$ps

Auch beendete Container auflisten:

$docker ps -a

Container neu starten:
Optionen zeigen:
$docker start --help
Befehl plus die erste Ziffer der Container-ID

$docker start container -i 996
$curl
$history

Container im Hintergrund starten:

Browswer starten: 
$start http://localhost:8080

$curl.exe http://localhost:8080

Logausgaben:(Ausgabe der apache prozess anzeigen lassen)

$docker logs dff
 
Zeitstempel anzeigen:
$docker logs -t dff 

Docker Container beenden:

$ docker kill container_id
$docker ps
$docker ps -a

Docker Container stopen:

$ docker stop container_id
$docker ps
$docker ps -a

Beendete Container starten:

$docker start c618
$docker ps

Container automatische löschen:
$docker ps -a
$docker run --rm -it ubuntu
Datei anliegen -> $touch test.txt
               -> $ls
               -> $ exit
$docker ps -a

Folge 4: Images bauen

Visual Studio mit 
$ Code . 
aufrufen 

Docker Image von Visual Studio auf hub.docker.com herunterladen:(Eigenes Image auf den Docker Hub)

$docker images
$docker tag hey maladho94/hey
$docker push maladho94/hey

Hostsystem aufräumen:
-> Erst Mal in Docker App
->Images
->Links auf Clean up
->in der Mitte auf Dangling 
->Remove
->Done
Alternativ:
->Links auf Clean up
->in der Mitte auf Unused 


Ordner über komandozeile erstellen :

-> Ein Ordner zurück cd ..
-> mkdir OrdnerName
-> cd OrdnerName
-> Mit code . ,kann man visual Studio in dem Ordner aufmachen

Änderungen in GIT hinzufügen:

->cd  OrdnerName
->git init 
->code .
->git status 
->
->
..................................................................................................................................................
Suchmachine: 

->Suchbegriffe auf English übersetzen und suchen.(weil Mehr Auswahl )
->Mit Stichwörter suchen.DH(Keine Artikel,keine präpositionen,keine untersch zw. Größe und klein)
->
->Anonime suche mit Anonime-Tab machen,ohne sich auf Google anzumelden
..................................................................................................................................................
To Do:

-> learn English ( Beginner Levels - Lesson 13 )  ergänzen und Lesson 01 hören
-> Programmieren ( CSS display flex - Flex-Box Tutorial #17) ,18 ergänzen und Lesson 1,2 hören
-> Video über Aktivitätsdiagramme ( UML Tutorial #1 - Einleitung )

