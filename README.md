Howarts Rails

Esta es una aplicación web desarrollada en Ruby on Rails que muestra información sobre los personajes de Harry Potter, incluyendo su nombre, locación y casa a la que pertenecen.

Requisitos:

- Ruby (versión X.X.X)
- Ruby on Rails (versión X.X.X)
- PostgreSQL (versión X.X.X)

Instalación:

1. Clona este repositorio en tu máquina local:
   git clone https://github.com/tu-usuario/howarts_rails.git

2. Ve al directorio del proyecto:
   cd howarts_rails

3. Instala las dependencias:
   bundle install

4. Configura la base de datos:
   - Asegúrate de tener PostgreSQL instalado y configurado correctamente.
   - Abre el archivo `config/database.yml` y ajusta la configuración de la base de datos según tus necesidades.

5. Crea la base de datos:
   bin/rails db:create

6. Ejecuta las migraciones:
   bin/rails db:migrate

7. Carga datos ficticios:
   bin/rails db:seed

Uso:

1. Inicia el servidor local:
   bin/rails server

2. Abre un navegador web y visita `http://localhost:3000`.

3. Verás una lista de personajes de Harry Potter junto con su locación y casa.

¡Disfruta explorando los personajes de Harry Potter en esta aplicación web! Si tienes alguna pregunta o problema, no dudes en contactarnos.
