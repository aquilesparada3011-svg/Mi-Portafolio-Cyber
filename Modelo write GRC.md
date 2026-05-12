# Write-up: [Nombre de la Máquina/Reto] 
**Fecha:** {{date}} |**Plataforma:** TryHackMe | **Dificultad:** [Fácil/Media] 
## 🛠️ Fase Técnica (Resumen) 
- **Vulnerabilidad encontrada:** [Ej: SQL Injection / SUID Binary] 
- **Explotación:** [Breve descripción de cómo entraste] 
--- 
## ⚖️ Análisis de GRC y Marco Legal 
> [!IMPORTANT] 
> **Impacto Normativo e Incumplimiento** 
> Según los hallazgos técnicos, esta vulnerabilidad vulnera los siguientes marcos: 
### 1. RGPD (Protección de Datos) 
- **Infracción:** Falta de medidas técnicas apropiadas para garantizar la seguridad de los datos (**Artículo 32**). 
- **Consecuencia:** Al comprometerse la *Confidencialidad*, se debería notificar a la autoridad de control en un máximo de **72 horas**. 
### 2. ISO/IEC 27001 (Estándar Internacional) 
- **Control A.12.6.1:** Gestión de vulnerabilidades técnicas. La existencia de este fallo demuestra que no hay un proceso de parcheo o escaneo de vulnerabilidades efectivo. 
- **Mejora sugerida:** Implementar un ciclo de vida de desarrollo de software seguro (S-SDLC). 
### 3. Directiva NIS2 (Ciberseguridad en la UE) 
- **Relevancia:** Si esta empresa fuera un "Sector Crítico", la falta de control de acceso podría suponer sanciones severas por no gestionar los riesgos de la cadena de suministro y la infraestructura. 
--- 
## 📈 Análisis de Riesgo (Matriz) 
- **Probabilidad:** Alta (Exploit público disponible). 
- **Impacto:** Crítico (Acceso total a la base de datos de clientes). 
- **Nivel de Riesgo:** **Extremo**. 
## 💡 Recomendaciones para la Gerencia 
1. Sanitización de inputs en el código fuente. 
2. Implementación de un WAF (Web Application Firewall). 
3. Auditoría legal de los términos de servicio y privacidad tras la brecha.