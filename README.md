# Dólar en Argentina: histórico diario (dataset abierto)

Cotizaciones diarias del dólar en Argentina desde 2011, en un CSV simple y listo para usar en Excel, Python, R o cualquier planilla. Lo publica y actualiza automáticamente **[Dólar Claro](https://dolarclaro.com)** todos los días hábiles después del cierre (≈18:45 hora de Argentina).

- Archivo: [`historico.csv`](historico.csv)
- Descarga directa: https://raw.githubusercontent.com/jonathancalb/dolar-argentina-historico/main/historico.csv
- Gráficos e histórico interactivo: https://dolarclaro.com/historico/

## Columnas

| Columna | Descripción |
|---|---|
| `fecha` | Fecha (AAAA-MM-DD) |
| `oficial` | Dólar oficial minorista, venta (ARS por USD) |
| `blue` | Dólar blue (informal), venta |
| `mep` | Dólar MEP (bolsa), venta |
| `ccl` | Dólar contado con liquidación, venta |
| `mayorista` | Dólar mayorista (BCRA / A3500), venta |
| `cripto` | Dólar cripto (USDT/USDC), venta |
| `tarjeta` | Dólar tarjeta (oficial + impuestos), venta |

Las celdas vacías indican que no hay dato para esa fecha (por ejemplo, el MEP y el CCL antes de que existieran registros públicos).

## Fuentes

Datos recopilados de fuentes públicas: [DolarApi](https://dolarapi.com), [ArgentinaDatos](https://argentinadatos.com) y el [BCRA](https://www.bcra.gob.ar). Metodología y política editorial: https://dolarclaro.com/fuentes/

## Licencia

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es). Podés usarlo, compartirlo y adaptarlo, incluso con fines comerciales, **citando la fuente con un link**:

> Fuente: [Dólar Claro](https://dolarclaro.com)

Los datos se ofrecen tal cual, con fines informativos, sin garantía.
