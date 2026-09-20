# Fichamento — Arquitetura da informação

ROSENFELD, Louis; MORVILLE, Peter; ARANGO, Jorge. **Information architecture**: for the
web and beyond. 4. ed. Sebastopol: O'Reilly, 2015. 486 p.

> Síntese própria, para uso no projeto. O PDF está nesta pasta (fora do controle de
> versão). Citar sempre com página; citação direta só curta e entre aspas, com a marca
> "tradução nossa" quando traduzida.

---

## Por que este livro está no projeto

A pergunta da pesquisa trata de **quanto do trabalho de decidir permanece com o usuário**
em cada serviço digital de viagem. A arquitetura da informação é o campo que descreve
essa distribuição de trabalho em termos verificáveis: como a oferta é agrupada, nomeada,
percorrida e recuperada. Sem ela, a comparação entre Google Travel, Decolar, CVC e
Terramundi ficaria no terreno da impressão.

É a fonte principal da seção **2.4 Arquitetura da informação e curadoria** do referencial,
e a base do **objetivo específico 1** (mapear a AI de cada serviço) e do **objetivo
específico 3** (linguagem de interface).

---

## Os quatro sistemas

Os autores decompõem a AI em quatro sistemas, que na análise devem ser observados
separadamente, nesta ordem:

| Sistema | Capítulo | O que descreve |
|---|---|---|
| Organização | 6 (p. 97-131) | Como o conteúdo é agrupado: esquemas e estruturas |
| Rotulação | 7 (p. 133-173) | Como o ambiente nomeia o que oferece |
| Navegação | 8 (p. 175-208) | Como a pessoa se move e sabe onde está |
| Busca | 9 (p. 211-267) | O que é indexado, como se filtra e como o resultado aparece |

### Organização (cap. 6)

- **Esquemas exatos** (p. 105-107): alfabético, cronológico, geográfico. Categorias
  mutuamente exclusivas. Servem a quem já sabe o nome do que procura.
- **Esquemas ambíguos** (p. 107-116): por tópico, por tarefa, por público, por metáfora,
  ou híbridos. Exigem julgamento de quem projeta — é aqui que a decisão de design aparece.
- **Estruturas** (p. 116-127): hierarquia, modelo de banco de dados (que permite filtros e
  facetas) e hipertexto.

**Uso no projeto:** organizar por tarefa ("planeje sua viagem") transfere menos decisão do
que organizar por catálogo ("voos, hotéis, carros"). A estrutura escolhida já é uma
posição sobre quem decide.

### Rotulação (cap. 7)

Rótulos aparecem como links contextuais, títulos, opções de navegação e termos de índice
(p. 140-153). O capítulo trata da consistência e das fontes para construí-los, incluindo
os termos que os próprios usuários digitam na busca (p. 153-173).

**Uso no projeto:** é o material do objetivo específico 3. O rótulo revela de quem é a
linguagem e o que o serviço promete fazer pelo usuário.

### Navegação (cap. 8)

Embutida — global, local e contextual (p. 183-193) — e suplementar: mapa do site, índice,
guia, assistente (p. 193-202). A noção de *placemaking* (p. 179) resume as três perguntas
silenciosas do usuário: onde estou, o que há aqui, para onde posso ir.

### Busca (cap. 9)

O que indexar (p. 218), como o algoritmo ordena (p. 227) e como o resultado é apresentado
(p. 233-252).

**Uso no projeto:** a ordenação padrão de um resultado é decisão editorial disfarçada de
neutralidade. Vale registrar, em cada serviço, o que aparece primeiro e por quê.

### Vocabulários controlados e facetas (cap. 10)

Metadados, vocabulários controlados, tesauros e **classificação facetada** (p. 303-308).

**Uso no projeto:** o número de facetas oferecidas indica quanta comparação o serviço
espera que o usuário faça por conta própria.

---

## Outros pontos aproveitáveis

**Lugar, não página (cap. 4, p. 53-75).** Ambientes digitais são tratados como lugares
feitos de informação (p. 56). Sustenta a leitura de um serviço como espaço projetado.

**AI invisível (cap. 5, p. 88).** Boa parte da arquitetura não aparece na tela: o usuário
percebe só o resultado, ou a ausência dele. Justifica analisar a estrutura, e não apenas
a estética.

**Modos de busca (cap. 3, p. 39-52).** Os autores criticam o modelo "simples demais",
segundo o qual o usuário sempre sabe o que quer (p. 40-46), e descrevem busca por item
conhecido, exploratória e exaustiva. Dialoga direto com o planejamento de viagem, em que
o usuário muitas vezes não sabe nem o destino.

**Contexto, conteúdo, usuários (cap. 11, p. 313-353).** O framework de pesquisa dos
autores serve de esqueleto para a **Metodologia (UN 04)**: contexto é o mercado brasileiro
de viagens, conteúdo é a oferta exibida por cada serviço, e usuários entram por observação,
sem recrutamento.

**Documentação (cap. 13, p. 389-438).** Mapas de site, wireframes, inventário de conteúdo.
São formatos possíveis para as figuras do artigo final.

---

## Como citar

- Indireta: (ROSENFELD; MORVILLE; ARANGO, 2015)
- Direta curta: "trecho" (ROSENFELD; MORVILLE; ARANGO, 2015, p. XX, tradução nossa)
- Referência: já consta na seção 3 do projeto.

---

## Método de análise derivado

A grade de análise dos quatro serviços — ficha por serviço, contagens de carga cognitiva e
quadro comparativo — está na skill `arquitetura-da-informacao`, em
`~/.claude/skills/arquitetura-da-informacao/`.
