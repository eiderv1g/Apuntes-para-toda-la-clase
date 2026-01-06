[**Clase siguiente →**](clase11-12.md)

[**← Clase anterior**](clase7-8.md)

# ☁️ Fundamentos de Computación en la Nube  
**Clases 9–10**

---

## 1. Repaso de seguridad e IAM

### ¿Qué es una política de IAM?
- Documento que define **permisos**
- Especifica:
  - Qué acciones están permitidas o denegadas
  - Sobre qué recursos
- Están escritas en **formato JSON**

### ¿Quién es responsable de la seguridad?
Según el **modelo de responsabilidad compartida**:
- **AWS**: seguridad de la infraestructura
- **Cliente**: seguridad de la aplicación y de los datos

---

## 2. Redes y entrega de contenido

### Conceptos básicos de redes
- Una red conecta dispositivos para intercambiar datos
- Elementos básicos:
  - Subredes
  - Enrutadores
  - Direccionamiento IP

---

## 3. Direcciones IP

### Dirección IP
Identificador único de un dispositivo en una red.

### IPv4 vs IPv6
- **IPv4**
  - 32 bits
  - Ejemplo: `192.0.2.0`
- **IPv6**
  - 128 bits
  - Ejemplo: `2600:1f18:22ba:8c00:ba86:a05e:a5ba:00ff`

IPv6 permite un número muchísimo mayor de direcciones.

---

## 4. CIDR (Classless Inter-Domain Routing)

Formato: 192.168.1.0/24



- `/24` indica cuántos bits son fijos para la red
- Permite definir rangos flexibles de direcciones IP
- Se usa ampliamente en AWS para redes y subredes

---

## 5. Amazon VPC (Virtual Private Cloud)

### ¿Qué es Amazon VPC?
Servicio que permite crear una **red virtual aislada** dentro de AWS.

Permite:
- Definir rangos de IP
- Crear subredes
- Configurar tablas de enrutamiento
- Gestionar puertas de enlace
- Aplicar múltiples capas de seguridad

---

## 6. VPC y subredes

### VPC
- Aislada lógicamente de otras VPC
- Asociada a una **única región**
- Puede abarcar varias Availability Zones

### Subredes
- División del rango de IP de la VPC
- Pertenecen a **una sola Availability Zone**
- Pueden ser:
  - Públicas
  - Privadas

---

## 7. Direccionamiento IP en VPC

- Al crear una VPC se asigna un bloque **CIDR IPv4 privado**
- El rango no se puede cambiar tras la creación
- Tamaños permitidos:
  - Máximo: `/16` (65.536 direcciones)
  - Mínimo: `/28` (16 direcciones)
- Las subredes **no pueden solaparse**
- IPv6 también está soportado

---

## 8. Direcciones IP públicas en AWS

### IPv4 pública
- Asignación automática o manual
- Se puede configurar a nivel de subred

### IP elástica (Elastic IP)
- Asociada a una cuenta de AWS
- Se puede reasignar entre recursos
- Puede tener costes adicionales si no se usa correctamente

---

## 9. Tablas de enrutamiento

- Contienen reglas (rutas) para dirigir el tráfico
- Cada ruta define:
  - Destino
  - Objetivo
- Todas las tablas incluyen una **ruta local** por defecto
- Cada subred debe estar asociada a **una tabla de enrutamiento**

---

## 10. Puerta de enlace de Internet (Internet Gateway)

- Permite que los recursos de una VPC se comuniquen con Internet
- Se asocia a la VPC
- Requiere:
  - Subred pública
  - Ruta hacia la Internet Gateway en la tabla de enrutamiento

Ejemplo:
- EC2 en subred pública → acceso a Internet
- Base de datos en subred privada → sin acceso directo

---

## 11. Ideas clave para el examen

- Las políticas de IAM están en formato JSON
- El cliente es responsable de la seguridad de sus datos
- IPv4 usa 32 bits, IPv6 usa 128 bits
- CIDR define rangos de direcciones IP
- VPC es una red virtual aislada
- Las subredes pertenecen a una sola AZ
- Las IP elásticas se pueden reasignar
- La Internet Gateway permite acceso a Internet


[**Clase siguiente →**](clase11-12.md)

[**← Clase anterior**](clase7-8.md)