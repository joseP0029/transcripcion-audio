**Análisis de riesgos y contramedidas**
| Riesgo                                                 | Impacto | Probabilidad | Contramedida                                                                                                                     |
| ------------------------------------------------------ | ------- | ------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| **Costos inesperados por uso de APIs**                 | Medio   | Medio        | Monitorear uso de tokens/API, establecer límites, usar planes gratuitos o servicios alternativos más económicos (como DeepSeek). |
| **Demora en la transcripción o análisis IA**           | Alto    | Bajo         | Procesar en segundo plano y notificar al usuario. Evaluar alternativas más rápidas si es necesario.                              |
| **Pérdida de datos del usuario**                       | Alto    | Bajo         | Usar almacenamiento confiable (MongoDB Atlas), realizar backups periódicos.                                                      |
| **Fallas en el despliegue o CI/CD**                    | Medio   | Bajo         | Configurar pipelines con logs detallados, realizar pruebas en entorno de staging.                                                |
| **Problemas con el reconocimiento del idioma español** | Medio   | Bajo         | Probar previamente los servicios de IA seleccionados y ajustar los modelos si es necesario.                                      |
| **Problemas de seguridad (acceso no autorizado)**      | Alto    | Medio        | Autenticación robusta, cifrado de datos sensibles y uso de HTTPS obligatorio.                                                    |
| **Dependencia de servicios externos**                  | Medio   | Medio        | Documentar alternativas (por ejemplo, usar OpenAI o DeepSeek indistintamente).                                                   |
