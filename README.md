# wordpress_site

Tutorial for setting up docker-compose.yaml file for phpmyadmin, mysql, wordpress

https://www.youtube.com/watch?v=pYhLEV-sRpY


This is the second tutorial - wordpress / react

https://www.youtube.com/watch?v=fFNXWinbgro

## Notes...

In Postman you can check the api with this endpoint
`http://www.localhost:8000/wp-json`

you have to make a small change in wordpress before Postman will work.
go to settings>permalinks and change it from `plain` to `post-name`

You can have a look at posts by using this endpoint - by default you should have 1.
http://www.localhost:8000/wp-json/wp/v2/posts

To get `localhost:8000` running you need to run the ` $ command docker-compose up -d`
