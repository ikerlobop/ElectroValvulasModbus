
Este programa es una interfaz gráfica de usuario (GUI) desarrollada en Python utilizando la biblioteca tkinter. Su propósito es controlar las electroválvulas de un dispositivo Modbus TCP.

Al iniciar la aplicación, se establece una conexión con el dispositivo Modbus TCP utilizando la dirección IP y el puerto especificados. Luego, la aplicación muestra una serie de casillas de verificación junto con etiquetas que representan las direcciones de registro de las electroválvulas.

El programa escanea continuamente el estado de las electroválvulas y actualiza las casillas de verificación y las etiquetas de estado en tiempo real. Si una casilla está marcada, el estado de la electroválvula correspondiente se establece en True y la etiqueta de estado se muestra como "True" en un fondo verde. Si una casilla no está marcada, el estado de la electroválvula se establece en False y la etiqueta de estado se muestra como "False" en un fondo rojo.

Además, el programa proporciona un botón que permite al usuario cambiar el estado de las electroválvulas. Al hacer clic en este botón, se actualizan los estados de las electroválvulas según las casillas de verificación.

El código también incluye manejo de errores para garantizar una conexión y comunicación adecuadas con el dispositivo Modbus TCP, así como el uso de un hilo separado para el escaneo continuo del estado de las electroválvulas, lo que permite que la interfaz gráfica permanezca receptiva mientras se realizan las actualizaciones en tiempo real.
