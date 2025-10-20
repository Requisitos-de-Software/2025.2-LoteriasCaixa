## **Tabela de  contribuições**

| Aluno | Descrição | Links|
|-------|-----------|------|
| [Heyttor Augusto](https://github.com/H3ytt0r62) | Criação dos # CNRF01 e #CNRF02  | [# CNRF01](#cnrf01--o-software-deve-ter-telas-simples-com-poucos-textos), [# CNRF02](#cnrf02---a-transição-de-telas-durante-o-fluxo-de-aposta-deve-ser-fluida-e-sem-travamentos-perceptíveis  ) |
| [João Pedro](https://github.com/Jadequilin) | Criação dos #CNRF03 e #CNRF04 | [#CNRF03](#cnfr03---acessibilidade-para-idosos-e-pcds), [#CNRF04](#cnfr04---performance-em-dispositivos-antigos ) |
| [Nayra Nery](https://github.com/NayraNery127) | Criação dos #CNRF05 e #CNRF06 | [#CNRF05](#cnrf05---feedback-visual-imediato-ao-adicionar-aposta), [#CNRF06](#cnrf06---expiração-automática-de-sessão-por-inatividade) |



# CNRF01 -O software deve ter telas simples com poucos textos
Autor:  [Heyttor Augusto](https://github.com/H3ytt0r62)

| **Campo**              |**Detalhamento**                                                                 |
|-------------------------|----------------------------------------------------------------------------------|
| **Nr Requisito**        | CNFR01                                                                          |
| **Classificação**       | Experiencia do usuario                                                                       |
| **Descrição**           | O sistema deve ter telas simples com poucos textos |
| **Justificativa**       | Garante  dinamismo, acessibilidade para pessoas com pouca experiencia com tecnologia e facilita o entendimento |
| **Origem**              | [#RNF01](../../Elicitação/Requisitos%20Elicitados.md)                                                                  |
| **Critério de Ajuste**  | -                          |
| **Dependências**       |-                                                             |
| **Prioridade**          | 6                                                                           |
| **Conflitos**           | —                                                                                |
| **História**            | Criado em 19/10/2025                                                            |



# CNRF02 - 	A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis
Autor:  [Heyttor Augusto](https://github.com/H3ytt0r62)

| **Campo**              |**Detalhamento**                                                                 |
|-------------------------|----------------------------------------------------------------------------------|
| **Nr Requisito**        | CNFR02                                                                       |
| **Classificação**       | Desempenho                                                                      |
| **Descrição**            	A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis|
| **Justificativa**       | Garante  dinamismo e fluidez durante o uso |
| **Origem**              | [#RNF08](../../Elicitação/Requisitos%20Elicitados.md)                                                                  |
| **Critério de Ajuste**  | -                          |
| **Dependências**       | [#RNF04 O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G](../../Elicitação/Requisitos%20Elicitados.md)                                                         |
| **Prioridade**          | 7                                                                  |
| **Conflitos**           | —                                                                                |
| **História**            | Criado em 19/10/2025                                                            |

# CNFR03 - Acessibilidade para Idosos e PCDs
Autor: [João Pedro](https://github.com/Jadequilin)

## Cartão de Especificação

| **Campo**              | **Detalhamento** |
|-------------------------|------------------|
| **Nr Requisito**        | NFR01 |
| **Classificação**       | Usabilidade/Acessibilidade |
| **Descrição**           | O sistema deve ser acessível para idosos e pessoas com deficiência visual, com texto aumentável, alto contraste e compatibilidade com leitores de tela. |
| **Justificativa**       | Inclusão digital e conformidade com leis de acessibilidade; atendimento a usuários com baixa visão ou limitações motoras. |
| **Origem**              | [RF12](../../Elicitação/Requisitos%20Elicitados.md) |
| **Critério de Ajuste**  | - Texto aumentável em 200%<br>- Contraste mínimo 7:1<br>- Compatível com VoiceOver/TalkBack<br>- Navegação por voz funcional |
| **Dependências**        | [RNF11](../../Elicitação/Requisitos%20Elicitados.md) |
| **Prioridade**          | 6 |
| **Conflitos**           | [RNF01](../../Elicitação/Requisitos%20Elicitados.md) - Telas simples podem limitar opções de acessibilidade |
| **História**            | Criado em 19/10/2025 |

# CNFR04 - Performance em Dispositivos Antigos
Autor: [João Pedro](https://github.com/Jadequilin)

| **Campo**              | **Detalhamento** |
|-------------------------|------------------|
| **Nr Requisito**        | NFR02 |
| **Classificação**       | Desempenho |
| **Descrição**           | O sistema deve funcionar adequadamente em dispositivos Android/iOS com mais de 3 anos, mesmo com hardware limitado e conexões instáveis. |
| **Justificativa**       | Grande parcela de usuários possui dispositivos antigos; performance ruim leva ao abandono do aplicativo. |
| **Origem**              | [RNF11](../../Elicitação/Requisitos%20Elicitados.md), [RNF12](../../Elicitação/Requisitos%20Elicitados.md) |
| **Critério de Ajuste**  | - Funcionamento em Android 8+ e iOS 12+<br>- Uso de RAM ≤150MB<br>- Carregamento ≤5s em 3G<br>- Estável com 3% de perda de pacotes |
| **Dependências**        | [RNF04](../../Elicitação/Requisitos%20Elicitados.md), [RNF08](../../Elicitação/Requisitos%20Elicitados.md) |
| **Prioridade**          | 7 |
| **Conflitos**           | [RNF06](../../Elicitação/Requisitos%20Elicitados.md) - Interface rica pode impactar performance |
| **História**            | Criado em 19/10/2025 |

# CNRF05 - Feedback Visual Imediato ao Adicionar Aposta
Autor: [Nayra Nery](https://github.com/NayraNery127)

| **Campo**              | **Detalhamento** |
|-------------------------|------------------|
| **Nr Requisito**        | NFR05 |
| **Classificação**       | Usabilidade |
| **Descrição**           | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho, por meio de uma animação, mensagem ou alteração no ícone do carrinho. |
| **Justificativa**       | Garante que o usuário perceba claramente que sua ação foi realizada com sucesso, evitando confusão e múltiplos cliques. Melhora a experiência e a confiança na interação com o sistema. |
| **Origem**              | [RNF09](../../Elicitação/Requisitos%20Elicitados.md) |
| **Critério de Ajuste**  | - Exibir confirmação visual em até 1 segundo após adicionar a aposta<br>- Feedback deve permanecer visível por pelo menos 2 segundos<br>- Mensagem ou ícone deve ser compreensível e não intrusivo |
| **Dependências**        | [RNF03](../../Elicitação/Requisitos%20Elicitados.md), [RNF08](../../Elicitação/Requisitos%20Elicitados.md) |
| **Prioridade**          | 6 |
| **Conflitos**           | [RNF06](../../Elicitação/Requisitos%20Elicitados.md) - Feedback sonoro pode ser redundante ou distrativo |
| **História**            | Criado em 20/10/2025 |

# CNRF06 - Expiração Automática de Sessão por Inatividade
Autor: [Nayra Nery](https://github.com/NayraNery127)

| **Campo**              | **Detalhamento** |
|-------------------------|------------------|
| **Nr Requisito**        | NFR06 |
| **Classificação**       | Segurança |
| **Descrição**           | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade, exigindo novo login para continuar o uso do aplicativo. |
| **Justificativa**       | Protege informações pessoais e financeiras do usuário em caso de esquecimento do aplicativo aberto, evitando acessos indevidos. |
| **Origem**              | [RNF10](../../Elicitação/Requisitos%20Elicitados.md) |
| **Critério de Ajuste**  | - Encerrar sessão após 15±1 minutos sem interação<br>- Exibir mensagem de aviso antes da expiração<br>- Redirecionar automaticamente para a tela de login |
| **Dependências**        | [RNF05](../../Elicitação/Requisitos%20Elicitados.md) |
| **Prioridade**          | 8 |
| **Conflitos**           | [RNF03](../../Elicitação/Requisitos%20Elicitados.md) - Persistência de dados temporários pode impedir o encerramento completo da sessão |
| **História**            | Criado em 20/10/2025 |


| Versão | Data       | Autor               | Descrição                                    | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 19/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62)   | Criação da NFR e adição de alguns| [Samuel Felipe](https://github.com/TerminaKng05) |
| ``1.1`` | 19/10/2025 | [João Pedro](https://github.com/Jadequilin) | Criação das CNRF's 3 e 4 | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| ``1.2`` | 19/10/2025 | [Nayra Nery](https://github.com/NayraNery127) | Criação das CNRF's 5 e 6 | [Samuel Felipe](https://github.com/TerminaKng05) |
