+-------------+
|  Cliente    |
| (Browser o  |
|  app móvil) |
+-------------+
      |
      | 1. Envía petición HTTP
      v
+-------------+
|  Servidor   |
| (Back-end)  |
+-------------+
      |
      | 2. Recibe y procesa la petición
      |    - Autenticación
      |    - Validación
      |    - Lógica de negocio
      |    - Acceso a la base de datos
      v
+-------------+
|  Base de    |
|  Datos      |
+-------------+
      |
      | 3. Recupera o guarda datos
      v
+-------------+
|  Servidor   |
| (Back-end)  |
+-------------+
      |
      | 4. Genera respuesta HTTP
      v
+-------------+
|  Cliente    |
+-------------+
      |
      | 5. Recibe y muestra la respuesta
