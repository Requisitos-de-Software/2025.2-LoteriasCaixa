# Resultados alcançados

## Introdução

Este trabalho, realizado na disciplina de Requisitos de Software (2025.2), teve como propósito identificar, registrar e validar as necessidades das partes interessadas para o desenvolvimento do sistema Loterias Caixa. Ao longo do semestre aplicamos práticas de engenharia de requisitos — desde a elicitação até a verificação dos artefatos — com o objetivo de assegurar que o produto final atendesse às expectativas dos usuários e entregasse valor em cada fase. A seguir, apresentamos de forma mais detalhada os resultados obtidos pelo grupo.

## Resultados Alcançados

### 1. Planejamento

No início do projeto, a equipe realizou uma fase de planejamento essencial para alinhar seus membros, definir o escopo, escolher metodologias, criar um cronograma e selecionar as ferramentas de trabalho. Foram criados 6 cronogramas detalhados (um para cada etapa do projeto), definidas 11 ferramentas de trabalho, elaborado o heatmap de disponibilidade da equipe, e documentada a metodologia de trabalho. Essa etapa inicial foi fundamental para estabelecer uma base sólida e documentar as necessidades do projeto — todo esse conjunto de decisões está registrado em [Planejamento](../Planejamento/).

### 2. Elicitação de Requisitos

Para criar requisitos iniciais, aplicamos 4 técnicas de elicitação que resultaram em um total de 68 requisitos identificados:

- [Análise de Documentos](../Elicitação/Técnicas/Análise%20de%20Documentos.md) — 16 requisitos (4 funcionais e 12 não funcionais)
- [Entrevista](../Elicitação/Técnicas/Entrevista.md) — 25 requisitos (16 funcionais e 9 não funcionais)
- [Observação](../Elicitação/Técnicas/Observação.md) — 27 requisitos (18 funcionais e 9 não funcionais)
- [Glossário](../Elicitação/Técnicas/Glossário.md) — 12 termos do domínio definidos

Conseguimos, a partir delas, uma compreensão básica de como elencar requisitos com e sem a participação de usuários. Com essas atividades identificamos requisitos funcionais e não funcionais tanto com participação direta de usuários quanto a partir de fontes documentais.

### 3. Priorização de Requisitos

Em seguida, priorizamos os requisitos com diferentes abordagens, escolhendo a técnica adequada conforme o contexto:

- [$100](../Elicitação/Priorização/$100.md) — 15 requisitos priorizados com distribuição de orçamento fictício
- [MoSCoW](../Elicitação/Priorização/MoSCoW.md) — 42 requisitos classificados (23 Must, 6 Should, 4 Could, 1 Won't)
- [Three Level Scale](../Elicitação/Priorização/Three%20Level%20Scale.md) — 13 requisitos priorizados (7 alta prioridade, 5 média, 1 baixa)
- [Value, Cost and Risk](../Elicitação/Priorização/Value%2C%20Cost%20and%20Risk.md) — 50 requisitos avaliados com análise estratégica de valor, custo e risco

### 4. Modelagem

Para aprofundar a compreensão sobre os usuários, as funcionalidades do sistema e os requisitos, foram aplicados conceitos práticos de Modelagem:

- [Casos de Uso](../modelagem/Casos%20de%20uso.md) — 9 casos de uso principais do sistema
- [Cenários](../modelagem/Cenários.md) — 15 cenários detalhados de interação
- [Histórias de Usuário](../modelagem/Ágil/História%20de%20usuário.md) — 42 histórias de usuário elaboradas
- [Especificação Suplementar](../modelagem/Especificação%20Suplementar.md) — requisitos não funcionais organizados pelo modelo FURPS+ (6 categorias: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade e Design/Implementação)
- [Léxicos](../modelagem/Léxicos.md) — 31 léxicos do domínio usando LAL (Léxico Ampliado da Linguagem)
- [NFR Framework](../modelagem/Ágil/NFR.md) — 14 softgoals organizados em SIGs (Softgoal Interdependency Graphs)
- [Backlog](../modelagem/Ágil/Backlog.md) — backlog completo com 2 temas, 9 épicos e 39 histórias de usuário distribuídas

Essas técnicas permitiram que a equipe adotasse a perspectiva do usuário, orientando o desenvolvimento para atender às suas expectativas e, ao mesmo tempo, serviram como base para a documentação adequada dos requisitos.

### 5. Rastreabilidade

Ao longo do desenvolvimento, a rastreabilidade foi aplicada para conectar os diversos requisitos levantados. Na fase final, implementamos rastreabilidade para relacionar requisitos e entregáveis:

- [Matriz Geral](../Pós-rastreabilidade/matriz_geral.md) — rastreamento completo de 40 requisitos funcionais e 30 requisitos não funcionais, totalizando 70 requisitos mapeados com suas origens e artefatos derivados
- [Backward from](../Pós-rastreabilidade/Backward%20from.md) — rastreabilidade regressiva mostrando a origem de cada requisito (40 RF e 30 RNF)
- [Forward from](../Pós-rastreabilidade/Forward%20from.md) — rastreabilidade progressiva conectando requisitos aos artefatos criados (casos de uso, histórias de usuário, cenários, léxicos, NFR Framework e especificação suplementar)
- [Modelo de Toranzo](../Pós-rastreabilidade/modelo_toranzo.md) — classificação dos elos de rastreabilidade segundo meta-modelo de Toranzo

Esses artefatos consolidaram as ligações entre requisitos e seus artefatos derivados, facilitando o acompanhamento de mudanças ao longo do projeto.

### 6. Verificação e Validação

Por fim, adotamos verificações sistemáticas dos artefatos — incluindo inspeções no estilo Fagan — para identificar fragilidades e promover correções, contribuindo para a qualidade final dos entregáveis:

- **Verificação:** Foram realizadas inspeções em 6 etapas diferentes do projeto (Etapas 1 a 6), com checklists específicos para cada artefato produzido, incluindo verificações do próprio grupo (Grupo 7) e do Grupo 1
- **Validação:** Foram conduzidas validações com usuários reais para diversos artefatos, incluindo backlog, histórias de usuário, cenários, casos de uso e especificação suplementar, garantindo que os requisitos atendessem às necessidades reais dos usuários

Todas as inspeções, checklists aplicadas e validações com usuários estão documentadas em [Verificação](../Verificação/) e [Validação](../Validação/).
 
## Versionamento
 
 | Data       | Versão | Descrição                                 | Autor                                      | Revisor                                     |
 | :--------: | :----: | :---------------------------------------- | :----------------------------------------: | :----------------------------------------: |
 | 19/11/2025 | ``1.0``  | Criação e desenvolvimento da página.| [João Pedro](https://github.com/Jadequilin), [Luan Vinícius](https://github.com/luannvi)   |  [Rivadalvio Joaquim](https://github.com/RivaFilho)  |
  | 22/11/2025 |  ``1.1``    | Formatação e adição de quantidades. | [João Pedro](https://github.com/Jadequilin), [Luan Vinícius](https://github.com/luannvi)   |  [Rivadalvio Joaquim](https://github.com/RivaFilho)  |
