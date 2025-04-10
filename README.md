# Webmin
![image](https://github.com/user-attachments/assets/2223b815-4832-407a-b7d7-ec5af2fbaf1f) 

Índex
.- Crear i modificar usuaris
.- Programar tasques
.- Instal·lació de software
.- Serveis
.- Quotes de disc
.- Còpies de seguretat
.- Compartició

Fer tot des de webmin
Has de crear dos usuaris bakalao_X i techno_X on (X és el vostre cognom).

![image](https://github.com/user-attachments/assets/c598ecb2-10be-4617-ad01-85e82bc8471f)

Els usuaris et passaran el hash de la seva contrasenya, no la contrasenya real. (podeu fer servir openssl).

![image](https://github.com/user-attachments/assets/87741a11-ec1b-4ba6-ae29-82366d137789)

Cada usuari tindrà un directori a home igual al seu nom d'usuari.

![image](https://github.com/user-attachments/assets/122ad2be-0ef4-4e64-8e1b-a58bc4a206ec)
![image](https://github.com/user-attachments/assets/427f2343-1d49-4a17-8010-fe87c7d2e4e1)

Utilitzaran bash com a shell.

![image](https://github.com/user-attachments/assets/3a5320a5-8402-4997-ada7-d5fae5b8b2c1)
![image](https://github.com/user-attachments/assets/f3717746-8c4e-4e11-af5c-9ae2722c3a95)

Els usuaris estaran dins del grup que tingui el seu mateix nom i dins del grup usuaris_empresa.

![image](https://github.com/user-attachments/assets/100bbdf4-4be5-44dd-af53-d038e84c212b)
![image](https://github.com/user-attachments/assets/32e80484-4db0-47b5-a25e-7c74f8e315b8)
![image](https://github.com/user-attachments/assets/eebf6d6a-f577-4e3b-8529-4508c54a9cab)
![image](https://github.com/user-attachments/assets/5ce885e0-9b1e-420b-beb0-353365f7276f)

L'usuari techno no podrà fer login després del dia 31-03-2025.

![image](https://github.com/user-attachments/assets/557ad252-5d1d-4900-944f-6e87de70a0d5)
![image](https://github.com/user-attachments/assets/06acbb39-4921-4d46-8a05-77336416513c)

Comproveu que els usuaris poden iniciar sessió.

![image](https://github.com/user-attachments/assets/4e7e2f2a-48c3-4565-850b-984b1bd4dcc7)

Canvia la data del sistema (utilitzant webmin) i comprova que techno no pot iniciar sessió si estem a dia 01-04-2025.

![image](https://github.com/user-attachments/assets/10160959-362e-4dae-a67f-3e85b69b5c76)


Programar tasques
Programa una tasca que neteja els paquets de Linux que ja no s'utilitzen una vegada al mes.

![image](https://github.com/user-attachments/assets/a3b79ad3-c3da-4c05-ba7b-9ec21356ced9)

Programa una tasca diaria que apaga l'ordinador a les 14:00.

![image](https://github.com/user-attachments/assets/89a8b8ae-4b97-4818-a74f-652a178c98af)
![image](https://github.com/user-attachments/assets/18cb9151-1cd5-4675-b0f6-ef5521ff94ad)


Comprova que funcionen (canvia dia i hora del sistema mitjançant webmin).

![image](https://github.com/user-attachments/assets/fdb39da8-30ad-4797-be93-53c218dfca53)
![image](https://github.com/user-attachments/assets/b3075303-6e5e-4189-addd-93123ceab90e)
![image](https://github.com/user-attachments/assets/c9dc296b-4b37-41e1-875a-80f923ee35bf)
![image](https://github.com/user-attachments/assets/16b421aa-5665-4e36-a674-d1161c087825)


3.- Instal·lació de software
Utilitza webmin per mostrar quins paquets de software es podrien actualitzar.

![image](https://github.com/user-attachments/assets/e2baf859-20ee-4ec5-b5a7-379626f14252)

Des de webmin actualitza un paquet.

![image](https://github.com/user-attachments/assets/e9a520b8-2a6f-4dd5-beb0-62bde9f2b29a)

Utilitza webmin per instal·lar un joc de apt.

![image](https://github.com/user-attachments/assets/0e96e558-504c-44fe-a099-4fdb8993ab91)
![image](https://github.com/user-attachments/assets/9d41942d-200c-4f93-afde-335ebaae8126)

Utilitza webmin per instal·lar gimp de apt.

![image](https://github.com/user-attachments/assets/343f9d66-3eee-4f78-a9b0-f83e984ca3fe)

Utilitza webmin per desinatl·lar el joc que heu instal·lat abans.

![image](https://github.com/user-attachments/assets/1c4bdb6f-49bd-4ed8-bef7-cc5fa246462f)

4.- Serveis
Utilitza webmin per mostrar els serveis que s'inicien amb el sistema.

![image](https://github.com/user-attachments/assets/0c507700-d9b6-4b4c-94e6-339810c5945f)

Utilitza webmin per mostrar els serveis que estan actius.

![image](https://github.com/user-attachments/assets/b2ec3f91-4287-418f-a9a4-34f528c36853)

Utilitza webmin per mostrar l'estat del servidor Apache.

![image](https://github.com/user-attachments/assets/3aa4a3d8-886c-46df-b50c-8ad09f85b81a)

Utilitza webmin per aturar Apache.
Selecionem apache i li donem a stop

![image](https://github.com/user-attachments/assets/d0264869-397c-40e8-be02-b3c18e537a88)

Utilitza webmin per mostrar l'estat del servidor Apache apagat.

![image](https://github.com/user-attachments/assets/d23f8005-6572-41e8-beba-8114675e6e82)

Utilitza webmin per reiniciar Apache.
Selecionem apache i li donem a restart

![image](https://github.com/user-attachments/assets/4b7005f6-e067-4654-babb-dd0427203c71)

Utilitza webmin per mostrar l'estat del servidor Apache reiniciat.

![image](https://github.com/user-attachments/assets/dbd050c3-78e8-485f-bad6-2445fc7d97e0)

5.- Quotes de disc
Activa les quotes de disc pels usuaris amb la comanda:
sudo apt install quota quotatool

![image](https://github.com/user-attachments/assets/a7d69bc8-7a40-4f34-ab39-a3aedd49d08f)

Utilitza webmin perquè l'usuari bakalao_X no pugui tenir més de 2 MB d'informació al disc.
bakaloa_bouakka

![image](https://github.com/user-attachments/assets/bccb9b97-6e25-4334-b630-bbc9e51ba68b)
![image](https://github.com/user-attachments/assets/6ac3f16e-4a87-438b-a731-dd7e31aef46f)

Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/914869ee-cb3a-4229-9c50-2d0db5c38366)

Utilitza webmin perquè l'usuari techno no pugui tenir més de 10 fitxers al disc.

![image](https://github.com/user-attachments/assets/6e0e0c76-a156-44b3-b035-5acbc8370bb9)

Comprova que el límit de la quota funciona.

![image](https://github.com/user-attachments/assets/d1774a2d-8987-4930-9aeb-87d03495d78c)

6.- Còpies de seguretat
Utilitzant el mòdul de Webmin Filesystem Backup fes una còpia de seguretat del directori /home al directori /backups (l'haureu de crear si no existeix).

![image](https://github.com/user-attachments/assets/7262ed29-7736-46ca-aeca-540181e74326)
![image](https://github.com/user-attachments/assets/3cd214ee-46fd-47fb-8f7c-200cdf48a221)
![image](https://github.com/user-attachments/assets/606bfc11-f193-4f06-92b5-901b275e259e)
![image](https://github.com/user-attachments/assets/370c2bcb-f75e-4595-9fbf-3f5a28420bb6)

Modifica alguns fitxers de /home.

![image](https://github.com/user-attachments/assets/fb56b2dd-dd87-4e34-b57f-6c96a58b3a68)

Recupera la còpia de seguretat.
Le damos a restaurar

![image](https://github.com/user-attachments/assets/bbe77817-36c0-4ccb-b93d-31017bc7dadd)
![image](https://github.com/user-attachments/assets/17cb2ebb-7922-472f-973c-a97dd89b4d95)
![image](https://github.com/user-attachments/assets/8132db5c-3759-4973-9263-9d5866b79864)

Comprova que els fitxers de /home són els correctes.

![image](https://github.com/user-attachments/assets/d17bd9a8-7579-4ee8-9a2e-61acffca3d58)

Programa una còpia de seguretat de /home/bakalao_X per els divendres a les 21:00.

![image](https://github.com/user-attachments/assets/3f9f26b0-ac04-4de9-963a-8295d5a6fcae)
![image](https://github.com/user-attachments/assets/7dab2983-c5a4-4c13-931f-cabd6b3f85bc)
![image](https://github.com/user-attachments/assets/188e4403-a562-4a18-9769-440c8937e070)
![image](https://github.com/user-attachments/assets/c482f9b6-6b24-4126-b959-767511bbf977)

Esborra la còpia de seguretat programada anteriorment.
Li donem a Delete Selected Backups
![image](https://github.com/user-attachments/assets/2823d174-8e14-416f-b9b7-bbda3f9ec0a6)


7.- Compartició

Per fer lo seguent hem de canviar els usuaris a usuaris de samba 

![image](https://github.com/user-attachments/assets/138d1a9b-db94-437b-921f-24f19ba9508d)
![image](https://github.com/user-attachments/assets/3c58b036-68e7-483f-b45e-f31fe6dd6609)

Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "area_public_X" per a usuaris sense autenticar en forma de lectura i escriptura.

Li donem a Security and Access Control:
![image](https://github.com/user-attachments/assets/44514dab-9269-486e-9f06-a55d41e20d29)

Li donem a Security and Access Control:

![image](https://github.com/user-attachments/assets/d43ed41b-fd8b-4006-820a-e58b249f778d)
![image](https://github.com/user-attachments/assets/06b6af52-f350-46b3-9c3f-91753e3343d6)


Crea un recurs a webmin que, utilitzant samba, comparteixi una carpeta anomenada "pontaeri_privat_X" per a usuaris _X i techno només de lectura.

![image](https://github.com/user-attachments/assets/8970eb6b-305f-48ed-bda4-482120da57ff)

Li donem a Security and Access Control:

![image](https://github.com/user-attachments/assets/54c49887-3d46-42f6-bab9-b92e56034893)
![image](https://github.com/user-attachments/assets/a01e4021-8ef2-453d-bbff-6876edefc9ff)
![image](https://github.com/user-attachments/assets/8f7760bc-2a19-49cd-9d58-245b1e9c566f)

Comprovar des de Windows que aquests recursos funcionen.


