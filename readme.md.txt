Este es un chatbot que a traves de un chat en una web, agenda citas en Calendar

Requisitos previos:
- Tener una cuenta de n8n
- Sacar la API KEY de OPEN AI

IMPORTANTE
En chatbot_conversador.html hay que reemplazar la url del webhook
En el workflow n8n:
- En los nodos de Calendar hay que ingresar las credenciales propias y elegir el calendario
- En el nodo OpenAI hay que ingresar la OpenAI key

COMO ENCUENTRO EL WEBHOOK?
- Abrir projecto en n8n
- Ir al primer nodo "When chat message received" y hacer doble click. Se abrne las opciones del nodo
- El la ventana, pestaña Parameters, opcion Chat URL copiar la URL y reemplazarla en chatbot.html 

COMO CREO LA CLAVE API DE OPENAI:
Tutorial: https://www.youtube.com/watch?v=L951IDfW-L8
