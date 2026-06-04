taskflow

main.js primero casi siempre
mirar main.js y despues las views

npm install
npm run dev
si no corre reviso la terminal antes de tocar codigo

views:
login
dashboard
tasks
profile
admin
task-form

buscar ids:
email
password
btnLogin
taskInput
addTaskBtn

input -> click -> guardar -> mostrar
FLUJO

localstorage
guardar user
guardar tasks
si recargo y desaparece todo revisar eso

render = volver a mostrar
si agrego tarea y no sale probablemente es render o no se esta llamando

queryselector busca cosas del html

si un boton no hace nada revisar:
- id
- event listener
- si el elemento existe

tailwind casi todo esta en class
por eso a veces parece que no hay css

bootstrap ya trae cosas hechas:
container
row
col
card
btn
navbar

si hay api:
buscar fetch
buscar services

si hay json:
revisar si hay db.json

router:
buscar carpeta router

si el proyecto esta raro:
readme
main.js
views
despues codigo

taskflow:
login -> captura email -> guardar user
dashboard -> mostrar user
tasks -> input -> array -> localstorage -> render

vite:
package.json
npm install
npm run dev

si hay error raro reviso consola
muchas veces es un id mal escrito o ruta

href cambia pagina
window.location tambien

class es diseño
id es javascript

si agrego algo y no pasa nada:
revisar id
queryselector
eventlistener
