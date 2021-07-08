# RegistroConsumoElectrico
Aplicación para registrar y controlar el consumo electrico

La aplicación está desplegada de forma automática en **Heroku**, la aplicación se llama [RegistroConsumoElectrico](https://registroconsumoelectrico.herokuapp.com/).

## Usando maven

Las principales acciones que haremos con maven serán:

* **Limpiar proyecto**: ``mvn clean package``
* **Empaquetar proyecto**: ``mvn clean package``
* **Generar imagen docker**: ``mvn spring-boot:build-image`` (**No configurado!**)
* **Arranca la aplicación**: ``mvn spring-boot:start``
* **Detiene la aplicación**: ``mvn spring-boot:stop``

## Sobre heroku

https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku