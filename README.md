
---

# README — Article *Behavior between Fires in Brazil*

```markdown
# Measuring Cross-Correlations, Contagion and Long-Range Behavior between Fires in Brazil and Some Time Series Related to Its Economic Growth

**Vinicius Vieira Nogueira** e Sérgio Adriani David
Publicado em *Fire* (MDPI), 2022, 5(5), 148 · 24 de setembro de 2022
[doi:10.3390/fire5050148](https://doi.org/10.3390/fire5050148) · Acesso aberto

---

## Problema

As queimadas no Brasil alimentam um debate sobre seu impacto no crescimento
econômico do país. Ferramentas como cointegração e, principalmente, correlação
vinham sendo usadas para identificar possíveis mecanismos de transmissão ou
**contágio** entre séries temporais distintas — mas correlação simples não distingue
co-movimento genuíno de tendência compartilhada, nem capta a dinâmica ao longo do tempo.

## Contribuição

Aplicamos **Detrended Cross-Correlation Analysis (DCCA)** combinada com **janela
deslizante** (*rolling window*) para medir o acoplamento dinâmico entre queimadas e
variáveis-chave do crescimento econômico brasileiro:

- área agrícola plantada
- produção de etanol
- precipitação na região Centro-Oeste
- Produto Interno Bruto

O uso de janela deslizante é o que permite observar **como o acoplamento muda no
tempo**, e não apenas estimar um coeficiente único para todo o período.

## Dados e recorte

Séries mensais divididas em dois regimes institucionais distintos:

| Período | Marco |
|---|---|
| jan/2012 – ago/2016 | Antes do impeachment presidencial de 2016 |
| set/2016 em diante | Após o impeachment |

A separação é proposital: mudanças no ambiente político e regulatório alteram
incentivos econômicos e práticas ambientais, e testamos se o acoplamento
queimadas–economia responde a esse corte.

## Resultados

O artigo identifica correlação cruzada e comportamento de longo alcance entre focos
de incêndio e as séries econômicas analisadas, com **variação do acoplamento entre
os dois períodos** — evidência de que a relação não é estável e responde ao contexto
institucional e econômico. Os resultados também dialogam diretamente com a Hipótese
da Curva Ambiental de Kuznets discutida no relatório de Iniciação Científica
que originou o trabalho.

📄 **Abstract completo e resultados:** [mdpi.com/2571-6255/5/5/148](https://www.mdpi.com/2571-6255/5/5/148)

## Meu papel

Coautor: coleta e tratamento das séries econômicas e ambientais, implementação do
método DCCA com janela deslizante, análise dos resultados e redação do manuscrito,
em coautoria com o orientador Dr. Sérgio Adriani David.

## Estrutura sugerida do repositório

