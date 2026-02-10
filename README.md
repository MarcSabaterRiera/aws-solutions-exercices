# Escenarios Profesionales – AWS Solutions Architect Associate

---

## Escenario 1 – Plataforma Web Escalable para E‑commerce

**Contexto**
Empresa de retail que lanza una tienda online con picos de tráfico estacionales (campañas, rebajas). La plataforma debe mantenerse disponible ante aumentos súbitos de usuarios.

**Requisitos funcionales**

* Aplicación web pública (frontend y backend)
* Catálogo de productos
* Carrito de compra
* API REST

**Requisitos no funcionales**

* Alta disponibilidad (≥99,9%)
* Escalabilidad automática
* Baja latencia
* Seguridad básica
* Optimización de costes

**Restricciones**

* Arquitectura multi‑AZ
* Servicios de nivel Associate

---

## Escenario 2 – Backend Serverless para Aplicación Móvil

**Contexto**
Startup que desarrolla una aplicación móvil de gestión de tareas. El backend debe escalar automáticamente y minimizar la carga operativa.

**Requisitos funcionales**

* API REST para clientes móviles
* Autenticación de usuarios
* Persistencia de datos

**Requisitos no funcionales**

* Escalabilidad automática
* Alta disponibilidad
* Pago por uso

**Restricciones**

* Time‑to‑market rápido
* Coste mínimo en fases iniciales

---

## Escenario 3 – Migración de Aplicación On‑Premise a AWS

**Contexto**
Empresa con aplicación legacy desplegada en servidores físicos que desea migrar a AWS con mínimo impacto en el negocio.

**Requisitos funcionales**

* Mantener funcionalidad actual
* Acceso web a la aplicación

**Requisitos no funcionales**

* Alta disponibilidad
* Backups automáticos
* Observabilidad básica

**Restricciones**

* Mínimos cambios de código
* El motor de base de datos no puede cambiar
* Presupuesto limitado

---

## Escenario 4 – Sistema de Procesamiento Asíncrono de Archivos

**Contexto**
Empresa que recibe miles de archivos diarios que deben procesarse de forma desacoplada y tolerante a picos de carga.

**Requisitos funcionales**

* Ingesta de archivos
* Procesamiento automático
* Almacenamiento de resultados

**Requisitos no funcionales**

* Procesamiento asíncrono
* Reintentos automáticos
* Registro de errores

**Restricciones**

* No perder archivos
* Arquitectura desacoplada

---

## Escenario 5 – Plataforma de Logs y Monitorización Centralizada

**Contexto**
Empresa con varias aplicaciones que necesita centralizar métricas y logs para mejorar la observabilidad.

**Requisitos funcionales**

* Recolección centralizada de logs
* Visualización de métricas
* Alarmas operativas

**Requisitos no funcionales**

* Retención configurable
* Bajo coste

**Restricciones**

* Uso exclusivo de servicios AWS

---

## Escenario 6 – Distribución Global de Contenido Estático

**Contexto**
Empresa de marketing que distribuye vídeos y material multimedia a usuarios globales.

**Requisitos funcionales**

* Acceso público a contenido estático
* Actualización ocasional del contenido

**Requisitos no funcionales**

* Baja latencia global
* Alta disponibilidad
* Protección frente a ataques comunes

**Restricciones**

* No existe backend dinámico

---

## Escenario 7 – Plataforma de Analítica Básica de Datos

**Contexto**
Empresa que desea analizar datos históricos de negocio sin impactar sistemas productivos.

**Requisitos funcionales**

* Almacenamiento de datos históricos
* Consultas analíticas ad‑hoc

**Requisitos no funcionales**

* Bajo coste de almacenamiento
* Separación OLTP / OLAP

**Restricciones**

* Procesamiento por lotes
* No requiere tiempo real

---

## Escenario 8 – Sistema de Backup y Recuperación ante Desastres

**Contexto**
Empresa que necesita proteger datos críticos frente a fallos, borrados accidentales o incidentes operativos.

**Requisitos funcionales**

* Backups automáticos
* Recuperación bajo demanda

**Requisitos no funcionales**

* Retención configurable
* Alta durabilidad

**Restricciones**

* DR pasivo (no activo‑activo)
* Coste controlado

---

## Escenario 9 – Arquitectura Multi‑Cuenta por Entornos

**Contexto**
Empresa de desarrollo que gestiona múltiples entornos (dev, test, prod) y necesita aislamiento y gobernanza.

**Requisitos funcionales**

* Separación de entornos
* Control de accesos

**Requisitos no funcionales**

* Visibilidad de costes
* Trazabilidad de acciones

**Restricciones**

* Equipo reducido
* Sin herramientas externas

---

## Escenario 10 – Integración de Sistemas Mediante Mensajería

**Contexto**
Dos aplicaciones independientes deben comunicarse sin dependencia directa y con tolerancia a fallos.

**Requisitos funcionales**

* Envío y consumo de mensajes
* Procesamiento independiente

**Requisitos no funcionales**

* Comunicación asíncrona
* Reintentos automáticos

**Restricciones**

* Mensajes no críticos en tiempo real
* Arquitectura desacoplada
