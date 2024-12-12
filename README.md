# Calculadora Remota con XML-RPC

¡Bienvenido a la calculadora remota! Esta es una aplicación sencilla que te permite realizar operaciones aritméticas básicas a través de un servidor remoto usando el protocolo XML-RPC.

## Características

- **Servidor**: Este componente se encarga de procesar las solicitudes de operaciones y devolver los resultados al cliente.
- **Cliente**: El cliente es quien envía las solicitudes de operación y muestra los resultados obtenidos del servidor.

## Operaciones Disponibles

Puedes realizar las siguientes operaciones con la calculadora:

- **Suma**
- **Resta**
- **Multiplicación**
- **División**

## Instrucciones de Uso

Para usar la calculadora remota, sigue estos simples pasos:

1. **Inicia el servidor**: Ejecuta primero el servidor en tu máquina para que esté listo para recibir solicitudes.
2. **Inicia el cliente**: Luego, ejecuta el cliente, que es la interfaz que usarás para interactuar con el servidor.
3. **Selecciona la operación**: En el cliente, se te presentará un menú con las opciones disponibles. Elige el número correspondiente a la operación que deseas realizar.
4. **Ingresa los números**: Introduce los números sobre los que deseas realizar la operación seleccionada.
5. **Obtén el resultado**: El servidor procesará tu solicitud y te enviará el resultado de la operación.

¡Y listo! Así de fácil es usar esta calculadora remota.

## Instalación

Para instalar y ejecutar la calculadora remota, sigue estos pasos:

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tu_usuario/calculadora_remota.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd calculadora_remota
    ```

3. Ejecuta el servidor:
    ```bash
    python server.py
    ```

4. En otra terminal, ejecuta el cliente:
    ```bash
    python client.py
    ```

## Contribuciones

Si quieres contribuir a este proyecto, ¡siéntete libre de hacer un fork y enviar tus mejoras! Abre un **issue** para reportar errores o proponer nuevas características.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
