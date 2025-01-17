# Análisis de Carteras de Inversión con ApiOpenAI

Este proyecto tiene como objetivo realizar un análisis exhaustivo de carteras de inversión utilizando datos históricos de precios de acciones y criptomonedas. El análisis se centra en calcular indicadores financieros clave que ayudan a evaluar la rentabilidad y el riesgo de diferentes carteras.

## Descripción del Proyecto

Este repositorio está diseñado para permitir a los usuarios analizar la rentabilidad y el riesgo de diversas carteras formadas por acciones y criptomonedas. A través de este proceso, se proporcionan recomendaciones sobre cuál sería la mejor cartera para invertir, utilizando una combinación de cálculos estadísticos y análisis automatizados.

## Procedimiento

1. **Obtención de Datos**:
   - Los datos históricos de precios de acciones y criptomonedas se descargan utilizando la biblioteca `yfinance`. Esta biblioteca facilita el acceso a datos financieros y permite obtener información actualizada sobre el mercado.

2. **Cálculo de Indicadores Financieros**:
   - Se calculan varios indicadores financieros, como:
     
- **Rentabilidad Anualizada**: Muestra el retorno promedio anual de una inversión, proyectado a partir de los rendimientos diarios.
- **Volatilidad Anualizada**: Mide el riesgo de la inversión a través de la fluctuación de los retornos. Una mayor volatilidad implica mayor riesgo.
- **Ratio de Sharpe**: Indica el retorno ajustado al riesgo, comparando el rendimiento obtenido con la volatilidad asumida.
- **Retorno Acumulado**: Refleja el crecimiento total de la inversión desde su inicio hasta el presente.
- **Máximo Drawdown**: Calcula la mayor caída desde el punto más alto hasta el más bajo, evaluando la pérdida máxima.

3. **Análisis Comparativo de Carteras**:
   - Se crean varias carteras de inversión y se calculan sus respectivos indicadores financieros. Esto permite realizar un análisis comparativo para identificar cuál cartera presenta un mejor rendimiento y menor riesgo.

4. **Integración de API de OpenAI**:
   - Los indicadores financieros calculados se envían a la API de OpenAI para un análisis automatizado. La API proporciona un análisis adicional sobre las carteras, sugiriendo cuál podría ser la más adecuada para invertir según los indicadores financieros.

5. **Visualización de Resultados**:
   - Se generan gráficos que muestran la evolución de los precios ajustados de las acciones y la rentabilidad de las carteras a lo largo del tiempo. Esto ayuda a los usuarios a visualizar el rendimiento de sus inversiones.

## Objetivos del Proyecto

- **Evaluar el Rendimiento de Carteras**: Ofrecer un análisis claro y conciso sobre la rentabilidad y el riesgo de diferentes carteras de inversión.
- **Recomendaciones Basadas en IA**: Proporcionar recomendaciones fundamentadas sobre la mejor cartera para invertir, utilizando la inteligencia artificial.
- **Educación Financiera**: Fomentar la comprensión de conceptos financieros clave y su aplicación práctica en inversiones.

## Participantes

- [Oscar Paul Sanchez Riveros](https://www.linkedin.com/in/oscar-sanchez-riveros/)


## Enlaces Útiles

- [API de OpenAI](https://openai.com/api/) - Documentación de la API utilizada para el análisis automatizado.
- [yfinance](https://pypi.org/project/yfinance/) - Documentación sobre la biblioteca para descargar datos financieros.








