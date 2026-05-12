# [NOMBRE DE LA SALA]: Análisis de Incidente y Resolución 
**Fecha:** 12 de Mayo, 2026 
**Dificultad:** [Fácil / Media / Difícil] 
**Herramientas utilizadas:** `Wireshark`, `Splunk`, `Linux Terminal` 

--- 
## 1. Resumen Ejecutivo (El "Qué y Por qué") 
*En esta sección explicas brevemente de qué trata la sala. No copies el texto de THM, usa tus palabras.* 
> **Objetivo:** Investigar un acceso no autorizado detectado en un servidor Windows y proponer medidas de mitigación. 
## 2. Fase de Investigación (Metodología) 
*Aquí es donde pones la "acción". Divide por tareas.* 
### Tarea A: Análisis de Logs / Red 
Explicas qué buscaste: *"Utilicé el comando `grep` para filtrar fallos de inicio de sesión..."* 
> [!INFO] Captura de evidencia 
> ![Pega aquí tu imagen con una flecha resaltando el error] 
### Tarea B: Resolución de Desafíos 
*"Para obtener la flag de la tarea 3, tuve que decodificar un mensaje en Base64 usando CyberChef..."* 
## 3. Conclusiones y Lecciones Aprendidas 
*Esto es lo que más miran los reclutadores.* * **Lo que aprendí:** Cómo identificar patrones de fuerza bruta en logs de tráfico. * **Desafío superado:** Al principio no encontraba el archivo, pero usé `find` y logré localizarlo. 
## 4. Recomendaciones (Blue Team Mindset) 
🛡️ *Propón 2 o 3 soluciones para que este ataque no vuelva a ocurrir:* 1. Implementar autenticación de dos factores (2FA). 2. Configurar alertas en el SIEM para más de 5 intentos fallidos de login.