Objetivo:
Probar la funcionalidad recién implementada en la aplicación web local y asegurar que funcione correctamente antes de confirmar que está lista.

Instrucciones paso a paso:

Verificar si el servidor está activo

Ejecuta en consola:

curl http://192.168.1.119:9999


Si la respuesta indica que el servicio está activo, continúa con las pruebas.

Si no está inicializado, ejecuta desde la raíz del proyecto:

node index.js


Espera a que el servidor se levante correctamente en http://192.168.1.119:9999
.

Planificar los casos de prueba

Antes de ejecutar las pruebas, define los casos de uso específicos que vas a validar.

Para cada caso, detalla:

Qué funcionalidad se está probando.

Qué acción realiza el usuario.

Qué resultado se espera obtener.

(Ejemplo: “El usuario hace clic en ‘Enviar’, el formulario debería guardar los datos y mostrar el mensaje ‘Guardado con éxito’.”)

Ejecutar las pruebas en el navegador

Abre la URL:
👉 http://192.168.1.119:9999

Prueba los casos de uso definidos uno por uno.

Observa cuidadosamente el comportamiento de la interfaz y la consola del navegador para detectar errores o comportamientos inesperados.

Depurar y volver a probar

Si alguna funcionalidad no responde como se espera, realiza lo siguiente:

Identifica el error en consola o en el código.

Corrige el problema en el entorno de desarrollo.


Vuelve a ejecutar las pruebas hasta que todos los casos funcionen correctamente.

Criterio de finalización

La tarea se considera completada cuando:

Todas las funcionalidades probadas funcionan según lo esperado.

No hay errores visibles en consola o interfaz.

El servicio permanece estable en hhttp://192.168.1.119:9999