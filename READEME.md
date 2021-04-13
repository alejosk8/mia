
# Comandos
### reiniciar todo el servicio
- docker-compose restart
### iniciar el servicio
- docker-compose up -d
### parar el servicio
- docker-compose down

## Operaciones por contenedor
- docker restart odoo
- docker restart db

## Modificación de parametros de odoo esta en el archivo odoo.conf dentro docker/odoo.conf

## Nuevos Modulso
- Añadir las carpetas a addons

### Corrección de base de datos al instalar odoo
sudo docker exec -it mia_odoo /usr/bin/odoo -d odoo -i base --http-port 8733



## Conexión con base de datos de odoo
- docker exec -it <nombreContenedorBD> bash
- su - postgres
- psql -U odoo -d <nombreBaseDatos>
(en caso que pida password es odoo)









