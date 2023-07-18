Beispiel PHP und Docker unter Windows
=====================================

Container starten
-----------------

* ``docker-compose up -d``

Symfony installieren
--------------------

* ``docker-compose-exec.bat composer install``

Schauen ob es geht
------------------

* ``docker-compose-exec.bat bin/console``
* Mit dem Browser auf http://localhost:8000/ gehen
