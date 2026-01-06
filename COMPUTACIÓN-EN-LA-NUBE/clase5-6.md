[**Clase siguiente →**](clase7-8.md)

[**← Clase anterior**](clase3-4.md)

# ☁️ Fundamentos de Computación en la Nube  
**Clases 5–6**

---

## 1. Repaso general

En estas clases se profundiza en:
- Infraestructura global de AWS
- Regiones y Availability Zones
- Servicios principales de AWS
- Certificaciones y recursos de aprendizaje
- Facturación y economía en la nube

---

## 2. Regiones y Availability Zones en AWS

### Región (Region)
- Área geográfica independiente
- Contiene múltiples centros de datos
- Ejemplos: `eu-west-1 (Irlanda)`, `us-east-1 (N. Virginia)`

### Availability Zone (AZ)
- Centro de datos aislado dentro de una región
- Diseñadas para alta disponibilidad
- Conectadas entre sí con baja latencia

### Diferencias clave
- **Región:** separación geográfica
- **AZ:** aislamiento físico dentro de una región

### Criterios para elegir una región
- Latencia (proximidad a usuarios)
- Coste de los servicios
- Regulación y cumplimiento legal
- Disponibilidad de servicios
- Estrategia de resiliencia y recuperación

---

## 3. AWS vs TI tradicional

AWS ofrece equivalencias a la infraestructura clásica:

| TI Tradicional        | AWS |
|----------------------|-----|
| Firewalls / ACL      | Security Groups / NACL |
| Administradores      | IAM |
| Enrutadores / Switch | VPC / Load Balancer |
| Servidores físicos   | EC2 |
| SAN / NAS / DAS      | EBS / EFS / S3 |
| Bases de datos       | RDS / DynamoDB |

👉 AWS traslada la infraestructura tradicional a servicios gestionados.

---

## 4. Ejemplo de arquitectura sencilla en AWS

Componentes típicos:
- **Amazon VPC** → red privada virtual
- **Amazon EC2** → cómputo
- **Amazon DynamoDB** → base de datos NoSQL
- **Amazon S3** → almacenamiento de objetos
- Usuarios acceden a través de internet

---

## 5. AWS Academy

### ¿Qué es AWS Academy?
- Programa educativo oficial de Amazon
- Orientado a estudiantes e instituciones
- Preparación para certificaciones AWS

### Beneficios
- Laboratorios prácticos
- Contenido oficial
- Experiencia real con AWS

---

## 6. Certificaciones AWS

### Rutas de certificación
- **Foundational**
  - AWS Cloud Practitioner
- **Associate**
  - Solutions Architect
  - Developer
  - SysOps Administrator
- **Professional**
- **Specialty**

📌 Este curso prepara especialmente para **AWS Cloud Practitioner**.

---

## 7. Documentación oficial de AWS

- Fuente principal de aprendizaje técnico
- Siempre actualizada
- Referencia obligatoria en entorno profesional

👉 https://docs.aws.amazon.com

---

## 8. Servicios de AWS tratados en el curso

### Servicios de cómputo
- Amazon EC2
- AWS Lambda
- Elastic Beanstalk
- ECS / EKS / Fargate

### Almacenamiento
- Amazon S3
- S3 Glacier
- EBS
- EFS

### Bases de datos
- Amazon RDS
- DynamoDB
- Redshift
- Aurora

### Redes y entrega de contenido
- Amazon VPC
- Route 53
- CloudFront
- Elastic Load Balancing

### Seguridad y gestión
- IAM
- CloudWatch
- CloudTrail
- AWS Config
- Organizations

---

## 9. Facturación y economía en la nube

### Tres factores principales de coste en AWS

#### 💻 Cómputo
- Se cobra por segundo u hora
- Depende del tipo de instancia

#### 💾 Almacenamiento
- Se cobra por GB
- Depende del tipo de servicio

#### 🌐 Transferencia de datos
- Entrada: normalmente gratuita
- Salida: normalmente de pago

---

## 10. Instancias reservadas (Reserved Instances)

Permiten reducir costes hasta un **75%**.

Tipos:
- **AURI** – Pago total anticipado (máximo descuento)
- **PURI** – Pago parcial anticipado
- **NURI** – Sin pago anticipado (menor descuento)

---

## 11. Nivel gratuito de AWS (Free Tier)

- Gratuito durante **12 meses**
- Ideal para aprender y practicar
- Incluye servicios básicos con límites

Pasos:
1. Crear cuenta
2. Aprender con tutoriales
3. Empezar a construir en AWS

👉 https://aws.amazon.com/free/

---

## 12. Calculadora de precios de AWS

Permite:
- Estimar costes mensuales
- Comparar arquitecturas
- Identificar oportunidades de ahorro
- Definir presupuestos

👉 AWS Pricing Calculator

---

## 13. Ideas clave para el examen

- Una región contiene varias AZ
- Las AZ permiten alta disponibilidad
- AWS ofrece equivalencias a la TI tradicional
- El coste se basa en uso real
- Las instancias reservadas reducen costes
- AWS Free Tier es clave para aprender

[**Clase siguiente →**](clase7-8.md)

[**← Clase anterior**](clase3-4.md)