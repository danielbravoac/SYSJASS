# SYSJASS
 System JASS (SYSJASS) es un sistema de control de cobranza que permite el uso de 2 clientes para acceso al servidor; permite el registro de cobranza,  registro de clientes, registro de propiedades para la sectorización y reporte de cuadre de caja por fechas.

# 📟 Módulos en Ejecución
+ Registro de Empleados
+ Registro de Clientes
+ Registro de Predios
+ Registro de Servicios
+ Cobranza de Clientes (Impresión de Tickets)
+ Reporte de Cuadre de Caja

# 👨‍💻 Sobre el Código
El código se ha realizado gracias a la arquitectura cliente-servidor, modelo de diseño de software en el que las tareas se reparten entre los proveedores de recursos o servicios, llamados servidores, y los demandantes, llamados clientes.

+ Importante: El código se muestra como código espagueti, término peyorativo para los programas de computación que tienen una estructura de control de flujo compleja e incomprensible. Su nombre deriva del hecho que este tipo de código parece asemejarse a un plato de espaguetis, es decir, un montón de hilos intrincados y anudados.

# 📦 Sobre la Base de Datos
La base de datos relacional representada, se ha realizado con las especificaciones hechas por el cliente. La imagen muestra la base de datos en su formato físico:

# ❓ Como Descargarlo y Restaurarlo
Para la restauración de la **base de datos** utilice [SQL Server 2019](https://www.microsoft.com/es-es/sql-server/sql-server-2019) con una instancia local o con contraseña; realice consultando la [documentación](https://docs.microsoft.com/es-es/sql/relational-databases/backup-restore/restore-a-database-backup-using-ssms?view=sql-server-ver15) respectiva y para la **edición de código** use [Visual Studio 2019](https://visualstudio.microsoft.com/es/vs/), alterne la cadena de conexión conveniente en la clase ´Conexion.cs´
