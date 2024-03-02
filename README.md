    Agregamos la dependencia, escribiendo en la terminal:

npm install — save-dev nodemon


 Probamos el funcionamiento, en la terminal, escribimos

nodemon .\index.js

Sin embargo, esto fallará, ya que no hemos instalado a nivel global nodemon, para arreglarlo, agregaremos un script a nuestro package.json

Ahora, cuando realicemos cambios en nuestra aplicación, veremos como automáticamente la consola muestra que se realizaron los cambios:

npm run start
