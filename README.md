¡Hola! Te doy la bienvenida a mi portafolio de proyectos de análisis de datos.

[Ver mi perfil de LinkedIn](https://www.linkedin.com/in/nando-zamora/) | [Escríbeme](mailto:zpnando@gmail.com)

# Acerca de mí

Ingeniero Industrial con maestría en Administración, certificado en análisis de datos y apasionado por descubrir las historias que cuentan los datos.

Transformo datos en insights y narrativas accionables que facilitan la toma de decisiones estratégicas y conectan la analítica con los objetivos del negocio. Cuento con experiencia en SQL, Python, Excel, Tableau y Power BI, destacando por pensamiento crítico, resolución de problemas y comunicación asertiva.

### Herramientas técnicas

Python (pandas, NumPy), SQL (PostgreSQL, MySQL), Power BI, Tableau, Estadística, A/B Testing, ETL, DAX, AppScript

### Habilidades blandas

Análisis de datos, Resolución de problemas, Comunicación efectiva, Trabajo en equipo, Orientación a resultados, Organización, Proactividad, Atención al detalle, Optimización de Procesos

## Proyectos destacados

## Análisis de rentabilidad y retención — App de delivery

Evaluación del desempeño de una plataforma de delivery para apoyar decisiones de negocio basadas en datos, combinando pedidos, catálogo, marketing y comportamiento de usuario, cerrando con un experimento A/B y un dashboard ejecutivo en Tableau.

#### Herramientas

Python (pandas, NumPy), SQL, pruebas de hipótesis estadísticas (Z-test), Tableau

### Preguntas clave

1. ¿Es rentable el negocio y qué tan sano es el margen?
2. ¿En qué etapa del embudo se pierden más usuarios?
3. ¿Regresan los usuarios después de registrarse?
4. ¿La nueva UI del checkout mejora la conversión?

### Metodología

- **Calidad de datos:** limpieza y validación de pedidos, catálogo y eventos.
- **Rentabilidad:** cálculo de KPIs (revenue, costos, margen) y desempeño por producto/canal.
- **Funnel de conversión:** construcción del embudo completo con SQL.
- **Retención:** análisis de cohortes de usuarios tras el registro.
- **Experimento A/B:** prueba Z de proporciones sobre un cambio de UI en el checkout.
- **Dashboard:** tablero ejecutivo interactivo en Tableau.

### Conclusiones y recomendaciones

- El negocio es rentable, con un margen cercano al 30% (~$2.9M USD de profit sobre $9.6M de revenue).
- El mayor cuello de botella del funnel está en el paso de pago, con caída a 86.7% de conversión; la conversión total del embudo es de 80%.
- El cambio de UI en el checkout no generó una mejora estadísticamente significativa (p = 0.42).
- Se recomienda auditar la captura de datos, reasignar presupuesto de marketing hacia canales más eficientes, investigar causas funcionales de la caída en el checkout y activar campañas de retención tempranas.

### Visualizaciones destacadas

1. **KPIs de rentabilidad, top productos y gasto de marketing:**
![KPIs de rentabilidad](https://raw.githubusercontent.com/nando-zamora/analysis_deliveries/main/grafica_kpis_negocio.png)

2. **Dashboard ejecutivo en Tableau:**


![Dashboard en Tableau](https://raw.githubusercontent.com/nando-zamora/analysis_deliveries/main/tableau_deliveries.png)

🔗 [Ver dashboard interactivo en Tableau Public](https://public.tableau.com/app/profile/hernando.zamora/viz/Entrega2_17873387898950/Dashboard1?publish=yes)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/nando-zamora/analysis_deliveries).**

## Dashboard de liquidez hotelera — ventas vs. cobros

Automatización de un proceso que antes se hacía manualmente en Excel: extracción de datos en tiempo real desde el PMS de un hotel mediante Google Apps Script hacia Google Sheets, conectado a Tableau, para dar visibilidad a los stakeholders sobre la liquidez del hotel respecto a las ventas y anticipar el flujo de caja futuro.

#### Herramientas

Google Apps Script, Google Sheets, Tableau

### Preguntas clave

1. ¿Cuánto se ha vendido por mes, y en qué mes hará check-in cada reserva?
2. ¿Qué proporción de esas ventas ya se ha cobrado y cuánto sigue pendiente por liquidar?
3. ¿Cómo se puede anticipar el flujo de caja futuro del hotel a partir de las reservas ya vendidas?

### Metodología

- **Extracción automatizada:** script en Google Apps Script que mina datos en tiempo real desde el PMS del hotel hacia Google Sheets.
- **Modelado de datos:** cálculo de campos clave — total de habitación con impuestos, extras, monto ya pagado y monto por liquidar.
- **Visualización:** conexión a Tableau y construcción de una matriz cruzada (mes de venta × mes de check-in) que muestra el estado de cobro de cada cohorte de reservas.

### Conclusiones y recomendaciones

- El dashboard reemplazó un proceso manual en Excel, reduciendo tiempo de actualización y margen de error.
- Al cruzar mes de venta con mes de check-in, los stakeholders pueden anticipar qué meses futuros tienen mayor volumen de ventas ya comprometidas y cuánto de ese monto aún no se ha cobrado.
- Esto permite una mejor planeación de flujo de caja, al identificar con anticipación períodos donde la liquidez esperada podría ser menor a lo proyectado.

### Visualizaciones destacadas

1. **Matriz de ventas y liquidez (mes de venta vs. mes de check-in):**
![Dashboard de liquidez](https://raw.githubusercontent.com/nando-zamora/liquidity-dashboard/main/dashboard_liquidez.png)

🔗 [Ver dashboard interactivo en Tableau Public](https://public.tableau.com/app/profile/hernando.zamora5276/viz/Liquidez_17891531474460/Dashboard1?publish=yes)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/nando-zamora/liquidity-dashboard).**
