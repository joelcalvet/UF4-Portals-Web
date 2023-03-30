# Instal·lació del Moodle en Ubuntu Server

![Selecció_311](https://user-images.githubusercontent.com/114162327/203845212-99a548da-9536-4af0-87fb-7e78557b341d.png)

L'adaptador del servidor té que estar en adaptador pont.

![Selecció_312](https://user-images.githubusercontent.com/114162327/203845336-be790b13-a9ac-414c-ac59-ef0864f834f4.png)

Per a connectar-se de la màquina real al servidor es té que executar ssh (nom de l'usuari del servidor)@(ip del servidor)

![Selecció_313](https://user-images.githubusercontent.com/114162327/203845547-f15a9dbe-1555-44bf-8d41-ede5ce68d7a3.png)

Instal·lo el moodle.

![Selecció_315](https://user-images.githubusercontent.com/114162327/203845761-18fb698c-c05a-45ab-8e4f-fc06a62f7952.png)

Faig un unzip de l'arxiu anteriorment descargat.

![Selecció_314](https://user-images.githubusercontent.com/114162327/203845668-b21f86e2-2bdf-4624-8a3b-c0edb6d7a473.png)

Instal·lo l'apache.

![Selecció_318](https://user-images.githubusercontent.com/114162327/203845947-b80e485d-c183-4d1a-94a9-d6ba69f7e113.png)

Instal·lo el Maria DB.

![Selecció_322](https://user-images.githubusercontent.com/114162327/203846298-57bb77dd-7adf-4a38-9a81-5669404847f6.png)

Instal·lo el PHP (la captura no està feta amb ssh perquè no m'havia recordat de fer captura de la emoció de que em funcioni)

![Selecció_316](https://user-images.githubusercontent.com/114162327/203845859-015cc9b7-4e1f-4c18-af50-0ce298eee570.png)

![Selecció_317](https://user-images.githubusercontent.com/114162327/203845900-df72e5e2-e605-4304-9ef4-a63f403b5eea.png)

Creo la carpeta moodledata.

![Selecció_320](https://user-images.githubusercontent.com/114162327/203846014-bf3ad4aa-bc15-4edc-acd5-c68dc98afd43.png)

Creo la base de dades del Moodle amb Maria DB.

![Selecció_321](https://user-images.githubusercontent.com/114162327/203846544-bd6c780b-c5fb-4698-8ce9-48c5067566ab.png)

Per a accedir al moodle es té que posar (ip del servidor)/moodle

Per a saber quina versió de php s'ha de descargar per a que el moodle funcioni correctament, es té que buscar a la pàgina oficial del Moodle, jo he descargat la 7.3.

![Selecció_364](https://user-images.githubusercontent.com/114162327/205093400-3cfcd178-6c8e-41b0-846e-403c7d0c0b7a.png)

Es te que instalar la extensió zip del php7.3

![Selecció_365](https://user-images.githubusercontent.com/114162327/205093586-4a9995c9-c288-4196-b8da-2219744b6541.png)

El directori de les dades és /home/moodledata

![Selecció_366](https://user-images.githubusercontent.com/114162327/205093712-35e40b26-48a4-44b1-ae41-703d0f9d16b2.png)

La base de dades que vaig instal·lar va ser MariaDB, per tant es té que seleccionar MariaDB.

![Selecció_368](https://user-images.githubusercontent.com/114162327/205094016-9ef025d4-d0f3-4b34-bac0-7d9305814e5e.png)

Introdueixo l'usuari i contrasenya de la base de dades.

![Selecció_369](https://user-images.githubusercontent.com/114162327/205094254-171f2250-bf5d-4f4a-a7b2-1d7a82c62a92.png)

Es té que instalar la extensió mbstring.

![Selecció_371](https://user-images.githubusercontent.com/114162327/205095018-d9b8d19e-8430-42d9-90ec-4d7d68093e35.png)

![Selecció_372](https://user-images.githubusercontent.com/114162327/205095047-9427717f-41e5-4471-a3ed-769e55de65e2.png)

![Selecció_373](https://user-images.githubusercontent.com/114162327/205095073-4c1b0ec6-a5c0-4c1e-8941-4738089dee59.png)

Aquestes extensions no són necessaries per a que funcioni, però fa que funcioni millor

![Selecció_374](https://user-images.githubusercontent.com/114162327/205095418-f591c628-6397-4ac1-8d39-99aa7f353d07.png)

![Selecció_375](https://user-images.githubusercontent.com/114162327/205095459-c6f7d363-0bac-4628-9370-c4995d336006.png)



