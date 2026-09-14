# Proyecto-Final-Coderhouse
Dashboard de Inteligencia de Negocios en Excel para monitoreo de ventas, márgenes y proyecciones. Incluye modelo de datos, automatización, KPIs interactivos y reporte de insights validado con IA. Proyecto Final del curso de Análisis de Datos de Coderhouse.


📊 Dashboard Final de Inteligencia de Negocios - Coderhouse (Entrega 9)
📌 Descripción del Proyecto
Este repositorio contiene el Sistema de Inteligencia de Negocios y Capa de Visualización Ejecutivo desarrollado como trabajo final integrador del programa de Análisis de Datos en Excel de Coderhouse.

El proyecto consolida todo el flujo de trabajo analítico, desde el procesamiento de datos (ETL) y modelado relacional, hasta la automatización financiera, métricas DAX/KPIs y diseño de interfaz gerencial interactiva (UI/Storytelling).

🛠️ Arquitectura Técnica y Módulos Desarrollados
El modelo relacional y visual se compone de los siguientes elementos técnicos:

Estructura de Datos & ETL (Power Query / M): Normalización de la base de transacciones (Hechos_Transacciones) vinculada a catálogos de Clientes y Productos con integridad referencial.

Cálculos e Integración: Implementación de búsquedas dinámicas avanzadas (BUSCARX, ÍNDICE y COINCIDIR), automatización temporal con DIA.LAB y refactorización de lógica compleja mediante LET.

Motor Analítico: Tablas dinámicas multidimensionales y medidas con sintaxis estricta de extracción dinámica (IMPORTARDATOSDINAMICOS).

Análisis de Hipótesis y Escenarios: Configuración de escenarios optimista, base y pesimista mediante el Administrador de Escenarios.

Capa de Visualización Gerencial (Dashboard Final):

Layout profesional con rejilla limpia y paleta de color sobria (regla 60-30-10).

Tarjetas de KPIs (Scorecards): Monitoreo de Ventas Totales, Ticket Promedio y % Cumplimiento de Meta con Formato Condicional dinámico.

Interactividad: Panel de 3 segmentadores de datos (Slicers) conectando Región, Categoría y Fecha a todas las visualizaciones del reporte.

Gráficos Avanzados: Gráfico dinámico de cascada (Waterfall) para descomposición del margen y análisis de costos logísticos/operativos.

💡 Auditoría Cognitiva y Prompts de IA (Abogado del Diablo)
El reporte incorpora una capa narrativa desarrollada mediante auditoría de IA para eliminar sesgos de interpretación:

Identificación de Sesgos: Validación de la concentración del 70% de ventas en la categoría Electrónica frente a los costos logísticos que reducen el margen neto.

Documentación de Prompts: Estructura de interacción Evidencia → Significado → Impacto → Acción disponible en la pestaña Reporte_Insights y en el PDF anexo.

📁 Estructura del Repositorio
Entrega9_DashboardFinal_PrietoVargasJhonCamilo.xlsx: Libro principal con la pestaña Dashboard Final e infraestructura analítica.

Prompts_IA_PrietoVargasJhonCamilo.pdf: Documento de auditoría cognitiva e interacción con IA.

Autor: Jhon Camilo Prieto Vargas

Curso: Análisis de Datos con Excel - Coderhouse
