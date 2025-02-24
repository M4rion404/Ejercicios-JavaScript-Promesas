# Ejercicios-JavaScript-Promesas
Aquí tienes una breve descripción de cada ejercicio y cómo se resuelven:

**Ejercicio 1: Simulación de Descarga de Archivo**
- **Descripción:** Crea una función `descargarArchivo(tamaño)` que devuelve una promesa. Si el tamaño es menor o igual a 50MB, se resuelve con "Descarga completada". Si es mayor, se rechaza con "El archivo es demasiado grande".
- **Resolución:** Se usa una simple comparación del tamaño del archivo y se resuelve o rechaza la promesa según corresponda.

**Ejercicio 2: Validación de Edad para una Compra**
- **Descripción:** Crea una función `verificarEdad(edad)` que devuelve una promesa. Si la edad es 18 o más, se resuelve con "Compra permitida", de lo contrario, se rechaza con "Debes ser mayor de edad para comprar este producto".
- **Resolución:** Se verifica si la edad es mayor o igual a 18 y se resuelve o rechaza en consecuencia.

**Ejercicio 3: Verificación de Stock en una Tienda**
- **Descripción:** Crea una función `verificarStock(producto, cantidad)` que devuelve una promesa. Si el producto existe en el inventario y hay suficiente stock, se resuelve con "Stock disponible". Si no, se rechaza con "Stock insuficiente".
- **Resolución:** Se consulta un objeto de inventario, verificando si el producto tiene suficiente cantidad en stock y se resuelve o rechaza según el resultado.

**Ejercicio 4: Simulación de un Pago en Línea**
- **Descripción:** Crea una función `procesarPago(monto)` que devuelve una promesa. Si el monto es mayor que 0, se resuelve con "Pago exitoso". Si es 0 o menor, se rechaza con "Error: Monto inválido".
- **Resolución:** Se comprueba si el monto es mayor que 0 y se resuelve o rechaza la promesa.

**Ejercicio 5: Autenticación de Usuario**
- **Descripción:** Crea una función `autenticarUsuario(usuario, contraseña)` que devuelve una promesa. Si las credenciales son correctas (usuario "admin" y contraseña "1234"), se resuelve con un objeto de éxito. Si son incorrectas, se rechaza con un objeto de error.
- **Resolución:** Se verifica si el usuario y la contraseña coinciden con los valores predefinidos y se resuelve o rechaza según corresponda.

**Ejercicio 6: Verificación de Saldo Bancario**
- **Descripción:** Crea una función `verificarSaldo(cuenta, monto)` que devuelve una promesa. Si el saldo es suficiente para la transacción, se resuelve con el saldo restante y un mensaje de éxito. Si no hay suficientes fondos, se rechaza con un mensaje de error.
- **Resolución:** Se comprueba si el saldo disponible es suficiente para cubrir el monto y se resuelve o rechaza la promesa en consecuencia.

**Ejercicio 7: Consulta de Clima desde un "Servicio"**
- **Descripción:** Crea una función `consultarClima(ciudad)` que devuelve una promesa. Si la ciudad está en la base de datos, se resuelve con la temperatura y condición del clima. Si no está, se rechaza con un mensaje de "Ciudad no encontrada".
- **Resolución:** Se busca la ciudad en la base de datos local, y se resuelve o rechaza la promesa dependiendo de si la ciudad existe o no.
