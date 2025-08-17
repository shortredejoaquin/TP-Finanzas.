# Informe Ejecutivo Financiero --- BYMA (Bolsas y Mercados Argentinos S.A.)

**Horizonte analizado:** últimos 5 años\
**Audiencia:** Directorio, Gerencia, Potenciales Inversores, Comité de
Préstamos

------------------------------------------------------------------------

## 1. Introducción:

Este informe sintetiza hallazgos cuantitativos y cualitativos sobre BYMA
a partir de tres cuadernos de trabajo provistos (Partes 1--3) que
incluyen: i) análisis técnico de precio y volumen (5 años), ii)
backtesting de señales simples (cruces de medias, RSI, MACD) y iii) una
valoración fundamental por DCF, evaluación de riesgos y escenarios macro
para Argentina. El objetivo es apoyar decisiones de asignación de
capital, perfil de riesgo y comunicación con stakeholders financieros.

------------------------------------------------------------------------

## 2. Resumen de Resultados Clave

-   **Desempeño de mercado (5 años):** tendencia **alcista moderada**
    con alta volatilidad relativa; señales técnicas entregan utilidad
    táctica pero son sensibles a "whipsaws" en periodos de shock local.
-   **Entorno macro (AR):** inflación alta pero con sesgo
    **descendente**, riesgo país \~**1.500 pb**, brecha cambiaria
    \~**25%**, reservas BCRA \~**USD 22bn**; variables aún volátiles
    condicionan múltiplos y costo de capital.
-   **Valoración DCF (supuestos base):** ingresos actuales \~**USD
    85m**, margen FCF \~**14,7%**, WACC **12%**, crecimiento 1--3 años
    **8%**, 4--5 años **5%**, perpetuidad **3%** → **precio teórico**
    \~**USD 4,0/acc**.\
    Sensibilidad razonable entre **USD 3,1--5,8/acc** (WACC 10--14%, g∞
    2--4%).
-   **Comparación con precio de referencia (estimado en los
    notebooks):** **USD 10,50/acc** → el DCF sugiere **downside
    material** bajo supuestos conservadores.
-   **Tesis operativa:** negocio "asset-light" con **alto apalancamiento
    operativo** a volúmenes; drivers clave: actividad de trading,
    listados, data & servicios post-trade, disciplina de costos y
    actualización tecnológica.
-   **Riesgos críticos:** regulación local/cambiaria, caída de volúmenes
    en equity doméstico, dependencia del ciclo macro argentino,
    ciber/operacional.

------------------------------------------------------------------------

## 3. Análisis de Datos:

### 3.1 Mercado y Técnica (últimos 5 años)

-   **Tendencia primaria:** alcista moderada; SMA-50 por encima de
    SMA-200 en tramos extensos, pero con **falsas rupturas** en shocks
    locales.
-   **RSI/MACD:** útiles para **gestión táctica**, no como señal única;
    mejores resultados cuando se combinan con filtros de tendencia
    (SMA-200) y stop-loss disciplinado.
-   **Conclusión ejecutiva:** Mantener un **enfoque por régimen**
    (tendencial vs. lateral) y tamaños de posición adaptativos a
    volatilidad.

### 3.2 Macro y Escenarios (Argentina)

-   **Supuestos trabajados en los cuadernos:**
    -   Inflación anual \~**140%** (tendencia: **descendente**).
    -   **Riesgo país \~1.500 pb** (estable/alto).
    -   **Brecha** \~**25%** (volátil).
    -   **Reservas BCRA \~USD 22bn** (estable).
    -   **Déficit fiscal \~3,2% PIB** (mejorando).
-   **Escenarios (probabilísticos):** Optimista **25%** / Base **50%** /
    Pesimista **25%**. Impacto principal: costo de capital y múltiplos
    de mercado.

### 3.3 Valoración Fundamental (DCF)

-   **Inputs clave (extraídos de los notebooks Parte 3):**\
    Ingresos actuales **USD 85m**, FCF actual **USD 12,5m**, **42m** de
    acciones; margen FCF **14,7%**; WACC **12%**; crecimiento 1--3 años
    **8%**, 4--5 años **5%**, g∞ **3%**.
-   **Resultado base:** **\~USD 4,0/acc**.\
    **Sensibilidad (precio/acc):**
    -   WACC **10%**: g∞ 2--4% → **USD 4,66--5,83**\
    -   WACC **12%**: g∞ 2--4% → **USD 3,71--4,36**\
    -   WACC **14%**: g∞ 2--4% → **USD 3,07--3,48**
-   **Lectura:** bajo un WACC acorde al riesgo argentino, el valor
    intrínseco estimado queda **por debajo** de un precio de mercado de
    **USD 10,50** (referencia utilizada en los cuadernos), implicando
    que **gran parte del upside ya descuenta normalización
    macro/volumétrica**.

### 3.4 Riesgos y Mitigantes

-   **Regulatorio/cambiario:** top risk. *Mitigante:* diálogo sectorial,
    diversificación de fuentes de ingresos (data, post-trade, listings
    internacionales).
-   **Volumen doméstico:** sensibilidad alta a ciclo y confianza.
    *Mitigante:* ampliar base de productos/mercados, incentivos a
    liquidez, conectividad.
-   **Tecnología/operacional:** continuidad y ciber. *Mitigante:* CAPEX
    focalizado, redundancia, certificaciones y pruebas de resiliencia.
-   **Macro/financiamiento sistémico:** costo capital elevado.
    *Mitigante:* caja y generación de FCF para sostener inversiones
    clave y payout prudente.

------------------------------------------------------------------------

## 4. Conclusiones y Recomendaciones:

### Para Directorio y Gerencia

1.  **Diversificación de ingresos:** acelerar **data & analytics**,
    *post-trade value-add* y **listados/segmentos** (p.ej., CEDEARs/ETFs
    locales) para suavizar la ciclicidad de volúmenes.
2.  **Pricing y elasticidad:** revisar **estructura de tarifas**
    (trading, clearing, custodia) con pruebas A/B por segmento,
    protegiendo market share de liquidez.
3.  **Tecnología como ventaja competitiva:** priorizar **latencia,
    resiliencia y ciberseguridad**; roadmap con hitos trimestrales y
    KPIs de uptime/latencia.
4.  **Asignación de capital:** dado el **WACC alto**, privilegiar
    proyectos con **payback corto** y ROI superior al costo de capital;
    revisar política de dividendos vs. reinversión.
5.  **Gestión por régimen de mercado:** protocolos de
    **escalamiento/desescalamiento** de campañas comerciales según
    volatilidad/volumen.

### Para Inversores

-   **Stance:** **Neutral con sesgo cauto**. El DCF bajo supuestos
    conservadores no respalda múltiplos implícitos altos; el **punto de
    entrada** luce más atractivo en la **banda USD 4--5** si no mejora
    el costo de capital o el *run-rate* de FCF.
-   **Catalizadores positivos:** mejora creíble de macro (WACC ↓),
    recuperación sostenida de volúmenes, nuevos productos/segmentos y
    monetización de datos/infra.
-   **Señales de alerta:** recrudecimiento regulatorio/cambiario, caída
    de liquidez, incidentes operativos.

### Para Comité de Préstamos

-   **Tesis de repago:** negocio con **flujo operativo recurrente** y
    baja intensidad de capital; exposición principal es **riesgo
    macro/regulatorio** más que operativo puro.\
-   **Cláusulas sugeridas:** *covenants* de cobertura de intereses/FCF,
    límites de endeudamiento neto, y **reporte trimestral** de KPIs de
    volumen, uptime, y métricas de ciber/continuidad.

------------------------------------------------------------------------

## Anexos

**A. Metodología (resumen):**\
- **Datos de mercado (5 años):** descarga/limpieza con `yfinance`;
indicadores: SMA(50/200), RSI(14), MACD; *backtesting* básico de cruces
y filtros de tendencia.\
- **Valoración DCF:** ingresos base **USD 85m**, margen FCF **14,7%**,
WACC **12%**, crecimiento 1--3 años **8%**, 4--5 años **5%**, g∞ **3%**,
42m de acciones; horizonte 5 años + valor terminal.\
- **Escenarios macro:** Optimista 25% / Base 50% / Pesimista 25% con
impactos en WACC, volumen y múltiplos.

**B. Sensibilidad DCF (precio/acción, USD):**\
- **WACC 10%:** g∞ 2% → **4,66** \| 3% → **5,16** \| 4% → **5,83**\
- **WACC 12%:** g∞ 2% → **3,71** \| 3% → **4,00** \| 4% → **4,36**\
- **WACC 14%:** g∞ 2% → **3,07** \| 3% → **3,26** \| 4% → **3,48**

**C. Principales riesgos (detalle y mitigación):**\
- Cambiario/controles, macro/tasas reales altas, volumen doméstico,
ciber/operacional. Mitigaciones propuestas en §3.4.

------------------------------------------------------------------------

### Nota final

Las cifras y supuestos de valoración y contexto macro provienen de los
**notebooks proporcionados**. Cambios en WACC, crecimiento, mix de
ingresos o regulación pueden alterar significativamente las
conclusiones. Recomiendo **actualizar esta valoración trimestralmente**
y complementar con *peer benchmarking* regional.
