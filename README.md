Lucrare de laborator nr. 2

Nume:
Prima aplicație Docker.

Scopul:
Scopul lucrării de laborator:

Familiarizarea cu elementele de bază ale containerizării.
Pregătirea spațiului de lucru pentru următoarele lucrări de laborator.
Sarcina:
Instalarea Docker Desktop și verificarea acestuia.

Pașii efectuați:

Execuția efectuată:

Prima execuție docker build -t containers02 . - construiește imaginea.

Cât timp a durat crearea imaginii? - Building 20.8s

A doua execuție docker run --name=containers02 containers02 - execută imaginea creată.

Ce a fost afișat în consolă? -
csharp
Copy code
hello from 00b50b3da101
A treia execuție docker rm containers02 și docker run -ti --name containers02 containers02 bash - Am șters containerul cu numele containers02, după executarea repetată am accesat imaginea.

În fereastra deschisă am executat cd /var/www/html/ și ls -l.

Ce este afișat pe ecran? -

diff
Copy code
-rwxr-xr-x 1 root root 215 Feb 17 10:20 index.html
Concluzii:
Cu ajutorul acestei lucrări de laborator, m-am familiarizat cu elementele de bază ale containerizării și am pregătit spațiul de lucru pentru următoarele lucrări de laborator.

Bibliografie:
Link către resursă