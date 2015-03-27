# family-team

Aquesta aplicació neix de la necessitat de tenir una eina d'organització familiar per tal de gestionar totes les tasques domèstiques de la via quotidina.

Requeriments no funcionals:

Entorn de programació:   NodeJs (capa servidor)
Framework:               Express + Jade (renderitzat de pantalles)
Base de dades :          No sql, MongoDB
API aplicació:           API Restfull + JSON
UI:                      Twiter Bootstrap
Control d'accés:         OAuth2

Requeriments funcionals:

CRUD usuaris:

     Crear usuari + perfil(sign up)
     Modificar perfil usuari
     Consultar perfil usuari
     Eliminar usuari
     
Organització d'usuaris:  Els usuaris s'agrupen en families.

CRUD families: 
     
     Crear:  Un usuari crea una familia i hi afegeix la resta d'usuaris de la familia.
     
     Modificar:   Només l'usuari que ha creat la familia pot administrar usuaris de la familia.
     
     Consultar:   Consultar families existents. 
     
     Eliminar:    Només l'usuari que ha creat una familia, la  pot eliminar.
     
                                   
CRUD llistes:

     Crear:  Tots els usuaris poden crear llistes de la seva familia.
     
     Modificar:   Tots els usuaris poden modificar totes les llistes de la seva familia.
     
     Consultar:   Tots els usuaris poden consultar totes les llistes de la seva familia. 
     
     Eliminar:    Només l'usuari que ha creat la llista, la  pot eliminar.


Login:   Google Sign In  (utilització mòdul 'everyauth' integrat amb 'express')
         exemple everyauth:  https://www.npmjs.com/package/everyauth-express3
                             http://stackoverflow.com/questions/14704803/express-3-0-everyauth-https
    
Logout:  
     
     
Compartir llistes entre usuaris:  Tots els usuaris que pertanyen a una familia, comparteixen totes les llistes.

Enviament notificació push:    si es modifica un item d'una llista, enviar notificació push als usuaris de la llista.

 
                    
