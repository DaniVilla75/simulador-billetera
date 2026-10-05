# 🔐 Simulador de Billetera Virtual

Aplicación educativa para nivel secundario que simula el proceso de onboarding
de una billetera virtual argentina (CVU, alias, validación RENAPER, OTP, selfie,
listas UIF/BCRA, PIN con hash, vinculación de dispositivo).

## 🌐 Usar online

Ingresá a: **https://TU-USUARIO.github.io/simulador-billetera/**

## 📋 Datos de prueba

| Campo | Valor |
|---|---|
| Email | cualquier@email.com |
| Teléfono | 11 1234-5678 |
| OTP | Mirar el panel derecho |
| DNI | 12345678 (Juan Pérez) |
| DNI | 87654321 (María Gómez) |
| PIN | algo que no sea 123456 |

## 🏗️ Arquitectura

- **Frontend:** HTML/CSS/JS estático (GitHub Pages).
- **Backend:** Google Apps Script (Web App).
- **Base de datos:** Google Sheets.
- **Almacenamiento de selfies:** Google Drive.

## 🧑‍🏫 Para el docente

Ver la carpeta [backend/](backend/) para el código del servidor.

Cada vez que un alumno termina el flujo, se agrega una fila a la planilla
`Simulador_Billetera_BD` en tu Drive y se guarda la selfie en la carpeta
`Simulador_Billetera/selfies/`.

## 📚 Ampliaciones futuras

- Transferencias entre usuarios
- Pago de servicios
- Historial de movimientos
- Inversiones (plazo fijo, dólar MEP)