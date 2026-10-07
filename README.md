# 🛡️ Laboratorio de Ciberseguridad: Hardening Inicial

**Proyecto:** Pre-entrega 2 - Ciberseguridad (Coderhouse)  
**Alumno:** Mateo Bentos

---

## 📌 Descripción del Proyecto
Este repositorio contiene la evidencia de la configuración inicial y securización (hardening) de un entorno de laboratorio aislado utilizando máquinas virtuales (VirtualBox con Debian). El objetivo principal es establecer una base segura para realizar pruebas de ciberseguridad aplicando el Principio de Mínimo Privilegio y aislando la red.

## 📄 Contenido del Repositorio
* **`Reporte_Preentrega2_Bentos_Mateo.pdf`**: Documento principal que contiene el reporte detallado, las justificaciones teóricas de seguridad y las evidencias (capturas de pantalla) de cada paso realizado.

## 🛠️ Fases de Configuración (Evidenciadas en el PDF)
1. **Aislamiento de Red (NAT):** Configuración del adaptador de red para actuar como un firewall natural, protegiendo la red host de posibles infecciones durante las pruebas de laboratorio.
2. **Principio de Mínimo Privilegio:** Creación de un usuario estándar en Debian sin acceso root directo, conteniendo el impacto de posibles ejecuciones de malware.
3. **Gestión de Parches:** Actualización completa de la paquetería del sistema operativo para mitigar vulnerabilidades conocidas (CVEs).
4. **Disponibilidad e Integridad:** Creación de un punto de restauración seguro (Snapshot "Hardening Inicial") para revertir el sistema ante fallas críticas o infecciones irreversibles durante las prácticas.
