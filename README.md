\# Caderno Temático

## Contexto e Objetivos

O tema escolhido para este caderno é Site Reliability Engineering (SRE). Atualmente atuo como analista de Comand Center/Analista de Observabilidade lidando com monitoramento de sistemas. Meu principal objetivo com esse estudo é dar o próximo passo na minha carreira rumo a Engenharia de Confiabilidade (SRE). Quero aprender os princípios de como desenhar, automatizar e manter aplicações altamente escaláveis e resilientes.
## Curadoria de Fontes

Para a construção deste material, foram selecionadas referências que cobrem desde os conceitos fundamentais até as práticas de observabilidade no dia a dia. As fontes utilizadas no NotebookLM foram:

- [Site Reliability Engineering (SRE), O Que é e Como Surgiu? | DevOps](https://www.youtube.com/watch?v=RrKhK81z1Vw)
- [Course Introduction | Site Reliability Engineering Foundation](https://www.youtube.com/watch?v=H7HsWHEi6DM)
- [Google SRE - SRE workbook table of content](https://sre.google/workbook/table-of-contents/?utm_source=chatgpt.com)
- [Introdução à Observabilidade | OpenTelemetry](https://opentelemetry.io/pt/docs/concepts/observability-primer/)
- [Melhores Práticas de SRE | DevOps](https://www.youtube.com/watch?v=5P58B3wv9RE)

## Engenharia de Prompts e Cicatrizes
Durante a exploração do NotebookLM, percebi que perguntas muito genéricas traziam respostas muito longas e difíceis de transformar em um guia. Precisei refinar os prompts para obter resultados mais práticos.

**Teste 1: Tentando entender os pilares do SRE**
- **Prompt inicial:** "Me explique tudo sobre SRE."
- **A Cicatriz (O que deu errado):** A IA me retornou uma "muralha de texto" enorme e cansativa, com mais de 5 tópicos longos misturando origens do Google, fórmulas matemáticas de erro e listas de habilidades. Estava correto, mas não servia como um resumo rápido para estudo.
- **A Solução:** Percebi que precisava ser mais específico para criar um guia prático.

**Teste 2: Refinando para criar o Guia**
- **Prompt Refinado:** "Atue como um Engenheiro SRE Sênior. Liste os 4 principais pilares do SRE (como SLI, SLO, SLA e Error Budgets) e explique cada um deles em apenas um parágrafo com uma analogia simples."
- **Resultado:** A resposta foi perfeita. A IA trouxe analogias cotidianas (como comparar o SLI a um velocímetro de carro) que facilitam o aprendizado e são ideais para o Miniguia.

## Miniguia de Estudo

### Resumos
**O que é SRE (Site Reliability Engineering)?**
O SRE é uma disciplina criada pelo Google que aplica práticas de engenharia de software para resolver problemas de infraestrutura e operações de TI. A ideia central é tratar a operação de sistemas como um problema de software, com o objetivo de manter aplicações altamente disponíveis, escaláveis e confiáveis. 

A regra de ouro do SRE é que a equipe deve gastar no máximo 50% do seu tempo apagando incêndios (trabalho manual operacional). Os outros 50% devem ser dedicados a criar automações e melhorias para que o sistema rode de forma autônoma.

### Glossário

- **SLI (Service Level Indicator):** É a métrica quantitativa real que mede o comportamento do serviço em tempo real. 
  - *Analogia:* É o velocímetro de um carro, que indica a velocidade exata naquele instante.
- **SLO (Service Level Objective):** É a meta numérica interna que a equipe estabelece para o SLI. 
  - *Analogia:* É a placa de limite de velocidade da rodovia que o motorista deve respeitar.
- **SLA (Service Level Agreement):** É o contrato formal comercial com o cliente final, prevendo penalidades se não for cumprido.
  - *Analogia:* É a apólice de seguro ou garantia da viagem.
- **Error Budget (Orçamento de Erro):** A margem de falha tolerada pelo sistema, permitindo riscos calculados para novas funcionalidades.
  - *Analogia:* É a cota de pontos da carteira de motorista para pequenos deslizes.
  
### Prompts Reutilizáveis
- "Atue como um Engenheiro SRE Sênior e explique [conceito] usando uma analogia do dia a dia."
- "Quais são as diferenças práticas entre [termo A] e [termo B] no dia a dia de um Analista de SRE?"
