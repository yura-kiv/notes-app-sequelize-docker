# This is a note list application API.
Three images created using Docker:
1) Server (Node.JS + TypeScript + Sequelize) on 8080 PORT
2) Database (<b>PostgreSQL</b> used docker image) on 5432 PORT
3) pgAdmin on 5050 PORT
   
## All docker settings you can find at docker-compose file

Three containers can be created and run, each on a different port. These containers can communicate with each other, make new entries, edit and delete notes in DB.

The server connects to the database using Sequelize ORM. They interact with each other all the time.
You can also interact with the database using pgAdmin.

## Used technologies:
<ul>
  <li>Docker</li>
  <li>pgAdmin</li>
  <li>Node.JS</li>
  <li>TypeScript</li>
  <li>Sequelize ORM</li>
  <li>Express.JS</li>
  <li>yup</li>
  <li>nodemon</li>
  <li>uuid4</li>
</ul>

## To build images:
docker-compose build

## To run containers:
docker-compose up
