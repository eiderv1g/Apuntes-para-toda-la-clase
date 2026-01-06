[**Clase siguiente →**](clase9-10.md)

[**← Clase anterior**](clase5-6.md)
# ☁️ Fundamentos de Computación en la Nube  
**Clases 7–8**

---

## 1. Repaso de costes y servicios básicos

### Factores fundamentales de coste en AWS
1. **Cómputo** → uso de instancias (EC2)
2. **Almacenamiento** → volumen de datos (S3, EBS, etc.)
3. **Transferencia de datos** → salida de datos principalmente

### Servicios clave
- **Amazon EC2**: servicio de cómputo (máquinas virtuales)
- **Amazon S3**: almacenamiento de objetos escalable y duradero

---

## 2. Seguridad en la nube

La seguridad en AWS se basa en el **Modelo de Responsabilidad Compartida**.

---

## 3. Modelo de responsabilidad compartida de AWS

### Responsabilidad de AWS (seguridad *de* la nube)
AWS es responsable de:
- Seguridad física de los centros de datos
- Infraestructura global (hardware y software)
- Redes, virtualización y aislamiento de instancias
- Regiones, Availability Zones y ubicaciones de borde
- Protección del hardware y del host

---

### Responsabilidad del cliente (seguridad *en* la nube)
El cliente es responsable de:
- Datos del cliente
- Gestión de identidades y accesos (IAM)
- Configuración de aplicaciones
- Configuración del sistema operativo
- Reglas de firewall y grupos de seguridad
- Cifrado de datos
- Gestión de usuarios y permisos

📌 Cuanto más alto el servicio (SaaS), menor responsabilidad del cliente.

---

## 4. Pregunta tipo examen (ejemplo)

**¿Cuál es responsabilidad de AWS según el modelo compartido?**

✔ **Mantenimiento del hardware físico**

❌ Configuración de aplicaciones  
❌ Protección de acceso a la aplicación  
❌ Gestión de AMIs personalizadas  

---

## 5. AWS IAM (Identity and Access Management)

### ¿Qué es IAM?
Servicio que permite:
- Administrar el acceso a los recursos de AWS
- Definir quién puede hacer qué y sobre qué recurso

📌 IAM es gratuito y se gestiona a nivel de cuenta.

---

## 6. Componentes esenciales de IAM

### Usuario de IAM
- Persona o aplicación autenticada
- Credenciales permanentes

### Grupo de IAM
- Conjunto de usuarios
- Comparten los mismos permisos
- Un usuario puede pertenecer a varios grupos

### Política de IAM
- Documento JSON
- Define permisos explícitos (Allow / Deny)
- El **Deny explícito prevalece** sobre Allow

### Rol de IAM
- Identidad con permisos específicos
- No está asociada a una persona
- Proporciona **credenciales temporales**
- Puede ser asumida por:
  - Usuarios
  - Aplicaciones
  - Servicios (ej. EC2)

---

## 7. Autorización y permisos

- Las políticas determinan:
  - Qué acciones están permitidas
  - Sobre qué recursos
- Se pueden conceder permisos:
  - Totales
  - Solo lectura
- Se aplica el principio de **mínimo privilegio**

---

## 8. Ejemplo de uso de un rol de IAM

### Escenario
- Una aplicación en una instancia EC2 necesita acceder a un bucket S3

### Solución
1. Crear una política IAM con acceso al bucket S3
2. Asociar la política a un rol
3. Permitir que la instancia EC2 asuma el rol

📌 Evita usar credenciales fijas dentro del código.

---

## 9. Laboratorio de seguridad

Práctica orientada a:
- Crear usuarios IAM
- Definir grupos y políticas
- Aplicar permisos reales
- Comprender el impacto del modelo de seguridad

---

## 10. Ideas clave para el examen

- AWS usa un modelo de responsabilidad compartida
- AWS protege la infraestructura
- El cliente protege los datos y accesos
- IAM controla quién accede a los recursos
- Las políticas definen permisos
- El Deny explícito siempre tiene prioridad
- Los roles usan credenciales temporales
- Principio de mínimo privilegio

[**Clase siguiente →**](clase9-10.md)

[**← Clase anterior**](clase5-6.md)