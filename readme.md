# PortSwigger Lab – Blind SQL Injection (Error-Based)

Automatización en Python de un laboratorio educativo de **PortSwigger Web Security Academy**.
El script explota una **Blind SQL Injection de tipo error-based**, utilizando errores
condicionales del servidor para inferir información sensible.

## 🎯 Objetivo del laboratorio
Extraer la contraseña del usuario `administrator` sin respuestas directas del servidor,
basándose únicamente en errores HTTP provocados de forma controlada.

## 🧠 Técnica utilizada
- Blind SQL Injection (error-based)
- Inferencia lógica a través de errores HTTP 500
- Extracción carácter por carácter
- Automatización del proceso con Python

## 🛠️ Implementación
- Inyección SQL a través de cookies (`TrackingId`)
- Uso de condiciones SQL (`CASE WHEN`) para forzar errores
- Detección de condiciones verdaderas mediante códigos de respuesta HTTP
- Código modular y documentado

## 🧪 Entorno
- Laboratorio educativo controlado
- Aplicación vulnerable proporcionada por PortSwigger
- No se utilizan sistemas reales

## ⚠️ Disclaimer
Este repositorio tiene fines **exclusivamente educativos y demostrativos**.
No debe utilizarse contra sistemas reales sin autorización expresa.
