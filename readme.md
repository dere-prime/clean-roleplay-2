# Clean Roleplay 2

[![SA-MP](https://img.shields.io/badge/SA--MP-0.3.7-blue)](https://www.sa-mp.mp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Discord](https://img.shields.io/discord/123456789012345678?label=Discord&logo=discord&logoColor=white)](https://discord.gg/awjDYAFpgW)

**Clean Roleplay 2** es un gamemode optimizado para SA-MP basado en **Super Roleplay 2** (branch `bernard` del repositorio de **neetoons**).

## 📖 Descripción

Clean Roleplay 2 mantiene la esencia del roleplay clásico de Super Roleplay 2, pero realiza una limpieza profunda: eliminación de sistemas obsoletos, código redundante y corrección de bugs conocidos. El resultado es una base ligera, estable y altamente extensible, ideal como punto de partida para servidores personalizados sin funcionalidades innecesarias.

## ✨ Cambios Principales

### 🗑️ Sistemas Eliminados

| Sistema                              | Descripción                                      |
|--------------------------------------|--------------------------------------------------|
| Mejores trabajadores y paga extra    | Eliminado por completo                           |
| Autenticación de dos factores (2FA)  | Desactivado por defecto                           |
| Compra de muebles (IKEA)             | Sistema completo y todos sus archivos             |
| Sistema de strippers                 | Eliminado                                        |
| Comando `/eco`                       | Removido                                         |
| Allanamiento de propiedades          | Sistema completo eliminado                       |
| Transferencia de propiedades a bandas| Eliminado                                        |
| Alarmas y indicador de ruedas        | En el speedometer (`air_speedo`)                 |
| Tutoriales integrados para trabajos  | Eliminados                                       |
| Trabajos de repartidor y warehouse   | Eliminados                                       |
| Arrays, enums y código sin uso       | Limpieza general                                 |

### 🔧 Mejoras y Correcciones

- Reemplazo de `SendNotification` por mensajes directos en el chat
- Corrección del bug en `/revivir`: ya no asigna 50.0 de vida incorrectamente a jugadores VIP
- Limpieza exhaustiva y optimización general del rendimiento del código

## 🎯 Objetivo

Proporcionar una base minimalista y bien estructurada para proyectos roleplay en SA-MP, facilitando la personalización y la adición de nuevas funcionalidades sin cargar con bloat innecesario.

## ⚙️ Requisitos

- Editor de código (recomendado: [Visual Studio Code](https://code.visualstudio.com/))
- Servidor SA-MP 0.3.7 (archivos básicos: `samp-server.exe`, plugins e includes necesarios)
- No se requieren `announce` ni `samp-npc`

## ⚠️ Notas Importantes

- Probado únicamente en compilación exitosa
- El funcionamiento completo en juego no está garantizado al 100%
- Reporta bugs o problemas en nuestro servidor de Discord: https://discord.gg/awjDYAFpgW

## 📄 Licencia

Este proyecto se distribuye bajo la **[licencia MIT](https://opensource.org/licenses/MIT)**.  
Puedes modificar, distribuir y usar el código libremente, siempre dando crédito a los autores originales (Super Roleplay 2 de Adri1 y neetoons).

---

Made with ❤️ for the SA-MP community  
*Última actualización: 8 de enero de 2026*
