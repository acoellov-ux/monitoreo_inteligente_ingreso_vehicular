# 🚗 Monitoreo Inteligente de Ingreso Vehicular (ALPR)

## 📌 Descripción del Proyecto
El presente proyecto consiste en el desarrollo de una aplicación web interactiva diseñada para el control y verificación vehicular en entornos académicos. El sistema integra tecnologías web modernas con un servicio externo de **Reconocimiento Automático de Placas de Matrícula (ALPR)** mediante una arquitectura basada en peticiones **REST API**.

## 🎯 Objetivo Principal
Permitir la captura directa mediante cámara web o la carga de archivos de imagen para identificar de forma automática el número de placa de un vehículo, realizando una búsqueda en tiempo real dentro de una base de datos local para presentar la información detallada tanto del propietario como del automóvil.

## ⚙️ Funcionalidades Clave
* **Captura Multimodal:** Capacidad para capturar fotos en tiempo real desde la cámara del dispositivo o examinar imágenes locales desde el almacenamiento.
* **Procesamiento e Integración REST:** Envíos en formato multipart a servicios de inteligencia artificial en la nube para la extracción rápida de caracteres de la placa.
* **Validación y Mapeo de Datos:** Búsqueda y cotejo dinámico en la estructura de datos local con manejo de estados (vehículo registrado o no registrado).
* **Interfaz de Usuario Dinámica:** Renderizado responsivo que muestra las fotos de perfil, credenciales del estudiante (cédula, correo) y ficha técnica del vehículo (marca, modelo, año, color).

## 🛠️ Tecnologías Utilizadas
* **Frontend:** HTML5, CSS3, JavaScript (ES6+).
* **Consumo REST:** API Fetch & FormData Interface.
* **Institución:** Universidad Técnica Estatal de Quevedo (UTEQ).
