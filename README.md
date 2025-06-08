# Entregable 1: Telecomunicaciones_lineas_de_telefonia
🧩 Caso propuesto: Gestión de Líneas Telefónicas en una Empresa de Telecomunicaciones
Una empresa llamada TeleNova S.A. brinda servicios de telecomunicaciones, principalmente líneas telefónicas móviles y fijas. La empresa desea implementar una base de datos para llevar un mejor control de:

Los clientes

Sus contratos de líneas telefónicas

Los planes tarifarios

El historial de pagos y consumos mensuales

Y los dispositivos móviles asociados (cuando aplica)

El sistema debe permitir almacenar y relacionar la siguiente información:

🧾 Requisitos del sistema (lo que debe manejar la base de datos):
Clientes

ID de cliente

Nombres y apellidos

DNI / RUC

Dirección

Email y teléfono de contacto

Tipo de cliente (natural o empresa)

Planes tarifarios

ID del plan

Nombre del plan

Tipo de plan (Prepago / Postpago)

Minutos incluidos

Datos móviles incluidos

Precio mensual

Líneas telefónicas

Número de línea (número de teléfono)

Tipo (móvil o fija)

Estado (activa, suspendida, dada de baja)

Fecha de activación

ID de cliente asociado

ID del plan contratado

Dispositivos (opcional)

ID del dispositivo

Marca y modelo

IMEI

Estado (asignado, devuelto, dañado)

Número de línea asociada (si aplica)

Historial de consumo y pagos

ID de factura

Número de línea

Periodo (mes y año)

Total a pagar

Total pagado

Fecha de pago

Detalle de consumo (minutos, datos, SMS)

🧠 Objetivos del ejercicio:
Diseñar un modelo entidad-relación (E-R) que represente el sistema.

Normalizar las tablas para evitar redundancias.

Crear las tablas con sus llaves primarias y foráneas.

Realizar consultas SQL como:

Listar los clientes con líneas activas.

Mostrar el consumo de datos de una línea específica.

Obtener el total recaudado por plan en un mes.

Identificar líneas sin pagos registrados en el último mes.

# Diagrama Entidad Relacion

![image](https://github.com/user-attachments/assets/5981145d-1f03-4058-b552-e39531f3cab0)

# Diseño logico

![image](https://github.com/user-attachments/assets/b901f3d5-d1dd-44f6-af32-e19ddc2a71e4)


