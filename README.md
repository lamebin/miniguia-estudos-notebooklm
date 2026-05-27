# miniguia-estudos-notebooklm
# Accenture + DIO: Project I
## O Guia Financeiro das Mulheres para Mulheres (https://notebooklm.google.com/notebook/63b5b0b7-45c9-43b3-ba38-e0038dd575b3)


## Contexto e Objetivos

A educação financeira ainda é um tema majoritariamente comunicado por homens e para homens. Nos últimos anos, no entanto, um grupo crescente de mulheres brasileiras passou a ocupar esse espaço com uma linguagem mais acessível, empática e direcionada à realidade feminina, das contas do mês à construção de patrimônio.

Este caderno temático reúne o conhecimento produzido por três dessas referências: Nathalia Arcuri (Me Poupe!), Nath Finanças e Ana Laura Magalhães, e utiliza o NotebookLM para organizar, sintetizar e extrair aprendizados práticos desse material. Como elas têm públicos distintos, a ideia é contemplar mulheres de distintos cenários financeiros, incentivando, em qualquer etapa da vida, a alfabetização financeira.


### Objetivos de Estudo

- Praticar RAG e engenharia de prompts para testar o NotebookLM
- Compreender os fundamentos de organização financeira pessoal sob uma perspectiva feminina
- Mapear estratégias de início em investimentos acessíveis para iniciantes
- Ser capaz de traçar planos de ação para mulheres com diferentes realidades econômicas


## Curadoria de Fontes

As fontes foram selecionadas com foco em conteúdo aberto, em português, produzido pelas três principais referências do caderno.

| # | Fonte | Tipo | Autora |

| 1 | [Canal Me Poupe!](https://www.youtube.com/@MePoupe) | Vídeo YouTube | Nathalia Arcuri |
| 2 | [Canal Nath Finanças](https://www.youtube.com/@NathFinancas) | Vídeo YouTube | Nath Finanças |
| 3 | [Instagram da Ana Laura Magalhães](https://www.instagram.com/analauramagalhaes/) | Artigo/Post | Ana Laura Magalhães |
| 4 | [Site Nath Finanças](https://nathfinancas.com.br) | Artigo web | Nath Finanças |
| 5 | [Instagram da Olivia Carneiro](https://www.instagram.com/olivia.sensata/) | Artigo/Post | Olivia Sensata

> **Nota sobre a curadoria:** Uma das principais dificuldades encontradas neste projeto foi justamente a **escassez de material em formato texto/PDF** produzido por mulheres sobre finanças. A maioria do conteúdo dessas criadoras está concentrado em vídeos e redes sociais, o que exige maior esforço de transcrição e adaptação para uso no NotebookLM. Cada autora também tem um direcionamento distinto de público: Nathalia Arcuri foca em acessibilidade para todos os perfis; Nath Finanças direciona seu conteúdo a pessoas de baixa renda e empreendedoras; Ana Laura Magalhães tem um viés mais analítico e macroeconômico.


## Engenharia de Prompts e Cicatrizes

Abaixo estão documentados os prompts testados no NotebookLM, as variações utilizadas, os resultados obtidos e as dificuldades encontradas.


### Prompt 1 - Diagnóstico Financeiro Pessoal

**Objetivo:** Gerar um roteiro de autoavaliação financeira baseado nas fontes.

> Com base nas fontes disponíveis, crie um checklist de diagnóstico financeiro pessoal para uma mulher que está começando a organizar suas finanças. Inclua perguntas sobre gastos, dívidas, reserva de emergência e metas.

**Variação testada:**

> Quais são os primeiros passos que Nath Finanças e Nathalia Arcuri recomendam para quem quer começar a organizar o dinheiro do zero?

 **Resposta obtida no NotebookLM:**

> Para começar a organizar sua vida financeira, preparei este checklist de diagnóstico com base nos ensinamentos das especialistas Nath Finanças, Nathalia Arcuri, Ana Laura Magalhães e Olivia Carneiro. Imagine que este é um raio-x da sua situação atual:
>
> - **Identificação do Fluxo:** Você sabe exatamente qual é o seu ganho líquido e para onde vai cada centavo, incluindo pequenos gastos como cafezinhos ou corridas de aplicativo?
> - **Faxina Financeira:** Você já revisou suas contas fixas e eliminou a "sujeira grossa", como taxas bancárias desnecessárias ou assinaturas que você não utiliza?
> - **Carimbo do Dinheiro:** Seus gastos e economias possuem uma finalidade específica ou você guarda dinheiro apenas "por guardar"?
> - **Mapeamento de Metas (SMART):** Você tem objetivos claros, específicos, mensuráveis, atingíveis, relevantes e com prazo definido?
> - **Consciência de Risco:** Você já entende a diferença entre poupar (não gastar) e investir (fazer o dinheiro trabalhar para você)?
>
> A IA ainda fez perguntas de follow-up para personalizar o plano: se há dívidas, se existe reserva de emergência e se alguma ferramenta de controle já é utilizada, por instrução da criadora do modelo.

**Observações / Troubleshooting:**
- A resposta foi bem estruturada e citou as quatro autoras presentes nas fontes, incluindo **Olivia Carneiro**, o que demonstra que o NotebookLM identificou corretamente todas as referências do caderno.
- O checklist trouxe nomenclaturas próprias das autoras (ex: "Faxina Financeira", "Carimbo do Dinheiro"), o que indica boa absorção do estilo e vocabulário das fontes.
- A IA adotou postura interativa, fazendo perguntas de follow-up - comportamento útil para uso pessoal, mas que pode precisar de ajuste de prompt caso o objetivo seja gerar um documento estático.
  

### Prompt 2 - Primeiros Passos em Investimentos

**Objetivo:** Sintetizar orientações práticas sobre como começar a investir.
> Explique, com base nas fontes, como uma pessoa sem experiência pode começar a investir com pouco dinheiro no Brasil em 2025. Mencione os tipos de investimento mais indicados para iniciantes e por quê.

**Variação testada:**
> Quais investimentos de renda fixa são mencionados nas fontes como seguros para quem está começando? Compare as recomendações das diferentes autoras.

 **Resposta obtida no NotebookLM:**

> Os investimentos de renda fixa mais seguros para iniciantes mencionados nas fontes são: **Tesouro Direto** (especialmente o Tesouro Selic), **CDBs** que pagam no mínimo 100% do CDI, e as **letras de crédito LCI e LCA**. A IA usou a analogia de "emprestar dinheiro para o governo ou banco e receber juros em troca", ou seja, uma linguagem acessível típica das autoras das fontes.
>
> Mecanismos de segurança identificados nas fontes:
> - **Tesouro Selic**: garantido pelo governo federal, ideal para reserva de emergência por ter liquidez diária
> - **CDBs, LCIs e LCAs**: protegidos pelo FGC em até R$ 250 mil por CPF por instituição
> - **Tesouro IPCA+**: recomendado para objetivos de longo prazo como aposentadoria, por proteger contra a inflação
>
> A poupança foi explicitamente desaconselhada por ter "uma das piores rentabilidades do mercado". A IA encerrou novamente com perguntas de follow-up sobre dívidas, reserva de emergência e ferramentas de controle.

**Observações / Troubleshooting:**
- A resposta foi tecnicamente precisa e bem embasada nas fontes, sem alucinações identificadas.
- Não houve diferenciação espontânea entre as abordagens das autoras; o NotebookLM sintetizou o conteúdo de forma unificada. Para um comparativo, é necessário um prompt mais direcionado (como o Prompt 3).
- O padrão de encerrar com perguntas de follow-up se repetiu, indicando que o caderno foi configurado com tom de "assistente financeiro interativo" — característica das instruções personalizadas do notebook, não uma limitação da IA.
  

### Prompt 3 - Comparativo de Abordagens

**Objetivo:** Mapear as diferenças de público e linguagem entre as três referências.

> Compare as abordagens de Nathalia Arcuri, Nath Finanças e Ana Laura Magalhães  sobre educação financeira. Quais são os públicos-alvo de cada uma?  Quais conceitos cada uma prioriza?

 **Resposta obtida no NotebookLM:**

> As especialistas possuem métodos distintos para democratizar as finanças:
> - **Nathalia Arcuri**: foco em entretenimento financeiro e reprogramação mental, voltado a tirar pessoas do endividamento
> - **Nath Finanças**: finanças reais para baixa renda, provando que é possível se organizar mesmo com salário-mínimo
> - **Ana Laura Magalhães**: estratégia e desmistificação do mercado, ensinando a entender o cenário econômico para investir com critério
>
> Quanto ao público-alvo: Arcuri fala com o público geral endividado ou sem propósito financeiro; Nath Finanças direciona-se à população periférica e de menor renda (inclusão financeira real); Ana Laura atrai quem busca análises estratégicas e visão global para construção de patrimônio.
>
> A síntese da IA foi precisa: "Cada uma delas preenche uma lacuna importante, desde o desendividamento em massa até a otimização de retornos financeiros."

**Observações / Troubleshooting:**
- Este foi o prompt com resposta mais rica e diferenciada, pois o NotebookLM conseguiu mapear com clareza os nichos e as abordagens de cada autora.
- A **principal dificuldade** identificada na curadoria foi a assimetria de fontes: há muito mais material de Nathalia Arcuri e Nath Finanças em formato aberto do que de Ana Laura Magalhães, o que pode ter influenciado o nível de detalhe na descrição de cada autora.
- Mesmo com fontes em vídeo (transcrições), o NotebookLM conseguiu extrair diferenças de posicionamento e público, o que valida o uso de conteúdo audiovisual como fonte no caderno.
  

### Prompt 4 - Geração de Glossário

**Objetivo:** Criar um glossário com os termos financeiros presentes nas fontes.
> Liste e defina os 15 principais termos financeiros que aparecem nas fontes, explicando cada um de forma simples, como se fosse para alguém que nunca estudou finanças.

 **Resposta obtida no NotebookLM:**

> A IA gerou os 15 termos com linguagem extremamente acessível, usando analogias do cotidiano:
>
> 1. **Selic** — a taxa "mãe" da economia; quando sobe, empréstimos ficam caros mas investimentos rendem mais
> 2. **Inflação (IPCA)** — o aumento de preços que faz o dinheiro comprar menos ao longo do tempo
> 3. **Juros Compostos** — efeito "bola de neve" que faz o dinheiro crescer sobre si mesmo
> 4. **Reserva de Emergência** — "colchão" de segurança para imprevistos como desemprego ou reparos
> 5. **CDB** — empréstimo ao banco com retorno em juros; mais seguro e rentável que a poupança
> 6. **Tesouro Direto** — empréstimo ao governo; considerado o investimento mais seguro do Brasil
> 7. **CDI** — taxa de referência dos bancos; "100% do CDI" significa acompanhar o ritmo do mercado
> 8. **Renda Fixa** — investimentos com regras de rendimento conhecidas antecipadamente
> 9. **Renda Variável** — investimentos que oscilam, como a Bolsa; sem garantia de retorno
> 10. **Ações** — "pedaços" de uma empresa; ao comprar, você se torna sócia do negócio
> 11. **Dividendos** — parte do lucro que empresas distribuem a quem possui suas ações
> 12. **FIIs (Fundos Imobiliários)** — investimento em imóveis grandes com recebimento de "aluguéis" mensais
> 13. **FGC** — "seguro" que protege até R$ 250 mil por CPF caso o banco quebre
> 14. **Liquidez** — facilidade de resgatar o dinheiro; "liquidez diária" = saque no mesmo dia
> 15. **Metas SMART** — técnica de objetivos específicos, mensuráveis e com prazo definido

**Observações / Troubleshooting:**
- O glossário gerado foi mais rico do que o pré-elaborado no miniguia, com analogias mais vívidas (ex: "bola de neve" para juros compostos, "colchão" para reserva de emergência) — reflexo direto da linguagem das autoras nas fontes.
- Todos os 15 termos foram gerados sem necessidade de reformulação do prompt, indicando boa cobertura temática das fontes.
- O glossário pode ser usado diretamente como material de revisão ou como base para flashcards.



### Prompt 5 - Plano de Estudos Personalizado

**Objetivo:** Criar um miniguia de revisão reutilizável.
> Com base em todo o conteúdo das fontes, crie um plano de estudos de 4 semanas sobre educação financeira feminina. Para cada semana, indique o tema central, os principais aprendizados e uma ação prática que posso executar.

 **Resposta obtida no NotebookLM:**

> O plano foi estruturado para transformar a relação com o dinheiro em 4 semanas, do diagnóstico básico aos primeiros investimentos — com atenção a desafios específicos do universo feminino como a longevidade feminina e a "taxa rosa" (produtos mais caros por serem voltados a mulheres).
>
> **Semana 1 - Diagnóstico e Metas SMART**
> Realizar um "raio-x" financeiro completo: identificar quanto entra e sai, e definir objetivos específicos, mensuráveis, atingíveis, relevantes e com prazo (ex: quitar uma dívida em 6 meses).
>
> **Semana 2 - Faxina Financeira e Regra 70/30**
> Eliminar gastos inúteis e aplicar a fórmula de gastar 70% com o presente e poupar 30% para o futuro, com atenção à "taxa rosa".
>
> **Semana 3 - Construção da Segurança**
> Focar na criação da reserva de emergência em ativos de liquidez diária (Tesouro Selic ou CDBs 100% CDI), com proteção contra imprevistos como desemprego.
>
> **Semana 4 - Estratégia de Longo Prazo**
> Aprender o poder dos juros compostos ("efeito bola de neve") e planejar a independência financeira sem depender de governo ou terceiros no futuro.

**Observações / Troubleshooting:**
- Este foi o prompt mais sofisticado em termos de resultado: a IA incorporou conceitos específicos do contexto feminino (longevidade e taxa rosa) que não estavam no prompt, demonstrando que o NotebookLM cruzou informações das fontes de forma autônoma e contextualizada.
- A resposta veio com introdução narrativa antes do plano estruturado, o que enriquece a leitura mas exigiria ajuste de prompt caso o objetivo fosse gerar apenas a tabela semanal sem texto introdutório.
- O padrão de perguntas de follow-up se manteve em todos os 5 prompts testados, confirmando que é uma característica da configuração do caderno, e não um comportamento aleatório da IA.

## Tecnologias e Ferramentas Utilizadas

- [NotebookLM](https://notebooklm.google.com/) — organização e análise das fontes com IA
- [GitHub](https://github.com/) — versionamento e portfólio
- [DIO](https://www.dio.me/) — plataforma de aprendizagem

## Autora

**Rafaela** - Senior Product Manager | Estudante de Data Science  
[LinkedIn](https://www.linkedin.com/in/rafaelagraebin)
#### Projeto desenvolvido para o Desafio de Projeto I - DIO, maio de 2026.
