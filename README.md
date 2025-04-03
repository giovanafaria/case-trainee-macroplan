# Case Trainee de Dados – Macroplan

Este case tem como objetivo realizar uma análise exploratória de indicadores macroeconômicos brasileiros, com foco em entender as relações entre inflação, desemprego, taxa de juros e crescimento econômico.

---

## Objetivos

- Integrar diferentes fontes de dados públicos.
- Aplicar técnicas de ETL (Extração, Transformação e Carga).
- Criar visualizações e insights que ajudem a interpretar o cenário macroeconômico através dos indicadores.

---

## Indicadores Utilizados

- **PIB corrente** e **PIB per capita**
- **Taxa Selic**
- **IPCA** (inflação oficial)
- **INPC** (inflação para baixa renda)
- **Taxa de Desemprego** (Desocupação)
- **População**
- Indicadores derivados: variações percentuais, defasagens, médias móveis

---

## Metodologia (ETL)

- **Extração:** (Extract)
- **Transformação:** (Transform)
- **Carga:** (Load)

---

## Visualizações Criadas

1. Correlação entre indicadores
2. Evolução temporal de Selic, IPCA, PIB (%) e desemprego
3. PIB per capita x Desemprego (com Selic e IPCA como dimensões)
4. IPCA e Selic (médias móveis)
5. IPCA x INPC
6. INPC x Desemprego (com Selic como dimensão)
7. Outros gráficos exploratórios (defasagens, histogramas etc)

---

## Conclusões

- A inflação afeta pessoas com menos salário mínimo de renda de forma mais intensa (INPC > IPCA);
- A política monetária (Selic) responde ao IPCA com atraso;
- O crescimento do PIB nem sempre se converte em redução do desemprego.

---