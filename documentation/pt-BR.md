<!-- ELUCENIA technical documentation · cts-6 · pt-BR · no clinical/professional/rights approval -->

# CTS-6 (síndrome do túnel do carpo)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/cts-6)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Dormência predominante ou exclusiva no território do nervo mediano

`dorm`

### Dormência noturna

`noturna`

### Atrofia e/ou fraqueza da musculatura tenar

`atrofia`

### Teste de Phalen positivo

`phalen`

### Perda da discriminação de dois pontos (\> 6 mm)

`dpp`

### Sinal de Tinel positivo sobre o túnel do carpo

`tinel`

## Edição do método

CTS 6/Graham 2006:6 critérios ponderados para túnelcarpo; exame clínico

## Fórmula documentada

Soma dos itens presentes: dormência no território do mediano 3,5; dormência noturna 4; atrofia/fraqueza tenar 5; Phalen positivo 5; perda da discriminação de dois pontos 4,5; Tinel positivo 4. Total de 0 a 26.

## Limites e população

O desenvolvimento Graham 2006 usou consenso de especialistas e histórias de casos combinando critérios clínicos; a validação descrita no resumo comparou probabilidades do modelo com julgamentos de outro painel. Esse desenho não estabelece, por si só, desempenho contra exame eletrofisiológico em cada população clínica. A pontuação de seis itens, seu corte e a faixa etária devem ser conferidos no método integral.

## Referências

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Probabilidade baixa de síndrome do túnel do carpo (abaixo de cerca de 25%)

Considere diagnósticos alternativos (radiculopatia cervical, polineuropatia).


### 2

Probabilidade intermediária (entre cerca de 25% e 80%)

A eletroneuromiografia tem mais valor nesta faixa.


### 3

Probabilidade intermediária (entre cerca de 25% e 80%)

A eletroneuromiografia tem mais valor nesta faixa.


### 4

Alta probabilidade de síndrome do túnel do carpo (cerca de 80% ou mais)

Nesta faixa, a eletroneuromiografia raramente muda o diagnóstico clínico.

