NIVELL 3

Prova dels Projectes Maven i Gradle amb Postman

Aquest exercici consisteix a provar els projectes creats en els nivells anteriors mitjançant Postman. A continuació, es detallen els passos per configurar els entorns necessaris i provar els projectes.
Configuració d'Entorns a Postman
Entorns a Crear:

    Projecte Maven
    Projecte Gradle

Variables dels Entorns:

Ambdós entorns tindran dues variables:

    Servidor:
        Valor: http://localhost (per ambdós entorns)
    Port:
        Valor per al Projecte Maven: 9000
        Valor per al Projecte Gradle: 9001

Proves a Realitzar

Executa els projectes Maven i Gradle des d’Eclipse. Assegura’t que els dos projectes estan en execució abans de realitzar les proves amb Postman.
URLs per Provar:

Pots provar l’URL:

    http://localhost:xxxx/HelloWorld/elmeunom
    O qualsevol altra URL que els dos projectes admeten.

Substitueix xxxx pel valor de la variable Port en cada entorn respectiu.
Entrega:

Has de lliurar els següents arxius:

    Entorns Exportats (2 arxius JSON):
        Un per al Projecte Maven.
        Un per al Projecte Gradle.

    Captures de Pantalla (2 imatges):
        Una captura per a cada entorn, on es mostri l’execució de les peticions des de Postman utilitzant l’entorn i les variables definides.

Com Provar

    Executa els Projectes:
        Executa els projectes Maven i Gradle creats en els nivells anteriors des d’Eclipse.

    Prova les Peticions:
        Realitza les peticions a les URLs configurades utilitzant els entorns i variables creades en Postman.
        Verifica el retorn obtingut en cada projecte.

    Captura de Pantalla:
        Fes una captura de pantalla per a cada entorn que mostri l'execució correcte de les peticions.
