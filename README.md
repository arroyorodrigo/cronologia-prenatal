# Cronología prenatal y perinatal

Los hitos del desarrollo prenatal, los factores de riesgo y las acciones de
cuidado sobre una misma escala de semanas de gestación, para ver qué coincide
con qué.

Material educativo. No reemplaza la evaluación ni la indicación del equipo de
salud que atiende cada embarazo.

## Qué contiene

- `index.html` — la página. Un solo archivo, sin dependencias ni build.
- `cronologia-prenatal.pdf` — versión imprimible en A3 apaisado, 7 páginas,
  con un anexo que reúne las descripciones completas.

## Cómo leer el gráfico

Las semanas se cuentan desde el primer día de la última menstruación. Los
rangos son aproximados: el desarrollo normal varía entre embarazos.

| Señal | Significa |
|---|---|
| Barra azul, verde azulado o ámbar | Hito del desarrollo, coloreado según el trimestre en que ocurre |
| Barra rayada roja | Factor de riesgo |
| Barra con contorno verde | Acción de cuidado |
| Barra tenue | Contexto o continuación del mismo proceso |

Los hitos posnatales van en una franja aparte porque se miden en minutos y
horas, no en semanas.

## Cómo trabajar con el archivo

Abre `index.html` en el navegador. Para regenerar el PDF:

```
python3 -m http.server 8000
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" \
  --headless=new --no-pdf-header-footer \
  --print-to-pdf=cronologia-prenatal.pdf http://localhost:8000/index.html
```

El tamaño y la orientación salen de la regla `@page` del propio HTML.

## Fuentes de consulta

- NICHD, [About Pregnancy](https://www.nichd.nih.gov/health/topics/pregnancy/conditioninfo)
- NICHD, [Labor and Delivery](https://www.nichd.nih.gov/health/topics/factsheets/labor-delivery)
- NCBI Bookshelf, [Critical Periods of Development](https://www.ncbi.nlm.nih.gov/books/NBK582659/)
- CDC, [Planning for Pregnancy](https://www.cdc.gov/pregnancy/about/index.html) y [Alcohol and Pregnancy](https://www.cdc.gov/fasd/about/index.html)
- OMS, [Recommendations on Antenatal Care for a Positive Pregnancy Experience](https://www.who.int/publications/i/item/9789241549912)

## Autoría

Rodrigo Arroyo. La página incluye el descargo completo de autoría y uso de
inteligencia artificial.
