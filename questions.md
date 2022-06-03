# Preguntas
### 1. ¿Qué dependencias estan usando?
- Dependencias: es6-promise, object-assign, needle

- Dependencias de desarrollo: mocha, chai, sinon, sinon-chai, q

### 2. ¿Cuál es e archivo pricipal?
- package.json

### 3. ¿Están usando Common JS o ESM?
- Esta API esta usando **Common JS**, porque los modulos de  **CommoJS** son caracterizados por el `require()` para importar los modulos y `module.exports` para exportar los modulos. 

### 4. ¿Qúe framework de pruebas esta utilizando?
- mocha, chai, sinon y sinonCha

### 5. ¿Cómo estan diseñadas las pruebas?
- Estan desarrolladas de acuerdo a cada paso que se sigue en trello
1. Contar con la kay y el token
2. Añadir Board
3. Copiar Board
4. Añadir una card
5. Añadir card con parametros extra
6. Mostrar una card
7. Mostrar una card del board
8. Mostrar una card con la lista de parametros
9. Mostrar una card del board con parametros extra
10. Mostrar la lista de boards}
11. Agregar un Webhook
12. Borrar un Webhook
13. Actualizar una card list

Para cada función que se puede realizar en trello, se crea una prueba. 

### Reisar los commits del repo [ ]