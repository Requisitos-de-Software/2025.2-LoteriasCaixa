# Especificação Suplementar

##  Introdução

Este documento apresenta a **Especificação Suplementar** do sistema **Loterias Caixa** seguindo o modelo **FURPS+**, abordando **requisitos não funcionais** e **requisitos funcionais complementares** que não foram adequadamente representados nos casos de uso.

##  O modelo FURPS+

O **FURPS+** é um modelo de classificação de requisitos proposto por Grady Booch que organiza os requisitos de software em diferentes dimensões, facilitando a análise e especificação abrangente do sistema. Conforme apresentado por Serrano e Serrano (2010), cada letra representa uma categoria de requisitos:

- **F - Functionality (Funcionalidade)**: Refere-se aos requisitos funcionais propriamente ditos, ou seja, as capacidades e funcionalidades que o sistema deve oferecer aos usuários. Exemplos: capacidade de realizar apostas, consultar resultados, etc.

- **U - Usability (Usabilidade)**: Aborda a facilidade de uso do sistema, experiência do usuário, aprendizado, interface intuitiva e acessibilidade. Envolve questões como navegação clara, design visual agradável e acessibilidade para pessoas com deficiência.

- **R - Reliability (Confiabilidade)**: Relaciona-se à capacidade do sistema de operar sem falhas, recuperação de erros, disponibilidade, tolerância a falhas e segurança. Inclui questões de autenticação, proteção de dados e recuperação de falhas.

- **P - Performance (Desempenho)**: Diz respeito às condições técnicas de funcionamento, incluindo tempo de resposta, velocidade de processamento, throughput, carga do sistema e eficiência. Define limites de tempo e velocidade aceitáveis.

- **S - Supportability (Suportabilidade)**: Refere-se à manutenibilidade, adaptabilidade, internacionalização, compatibilidade com diferentes plataformas e facilidade de suporte técnico. Inclui questões de portabilidade e compatibilidade.

- **+ (Mais)**: O "+" representa requisitos adicionais que não se encaixam nas categorias anteriores, como requisitos de design, implementação, licenciamento e legislação.

Utilizando este modelo, é possível garantir que todos os aspectos importantes do sistema sejam considerados durante a especificação, não apenas os requisitos funcionais tradicionais.

##  Metodologia

A especificação foi elaborada utilizando o **modelo FURPS+** conforme proposto por Serrano e Serrano (2010), incluindo requisitos elicitados através de múltiplas técnicas: entrevistas com usuários, observação direta do sistema, e análise de documentação oficial. Os requisitos foram categorizados em suas respectivas dimensões do FURPS+ para garantir uma cobertura completa e organizada de todos os aspectos não funcionais do aplicativo.

##  Modelo Usado

### Tabela 1 - Categorias do Modelo FURPS+ para Especificação Suplementar

| Categoria | Abreviação | Descrição |
|-----------|-----------|-----------|
| **Funcionalidade** | **F** | Características funcionais e capacidades do sistema, requisitos que o sistema deve realizar |
| **Usabilidade** | **U** | Facilidade de uso, aprendizado, acessibilidade e experiência do usuário com a interface |
| **Confiabilidade** | **R** | Disponibilidade, tolerância a falhas, recuperação, segurança e proteção de dados |
| **Desempenho** | **P** | Tempo de resposta, velocidade, throughput, carga e eficiência operacional |
| **Suportabilidade** | **S** | Manutenibilidade, adaptabilidade, internacionalização e compatibilidade multiplataforma |
| **Design e Implementação** | **+** | Restrições de design, padrões de interface, linguagens, ferramentas e arquitetura |

*<p style="text-align: center;">Autoria: Própria do Grupo</p>*

## Vídeo da validação 

Link da Gravação Especificação suplementar [Nayra Nery](https://github.com/NayraNery127):
[Gravação Especificação Suplementar.](https://www.youtube.com/watch?v=G98rq24DcHw)

##  Tabela de Contribuição

### Tabela 2 - Contribuição na Especificação Suplementar 

| Aluno | Seções Desenvolvidas |
|-------|---------------------|
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | Especificação suplementar inicial e Implementação |
| [João Pedro](https://github.com/Jadequilin) | Organização especificação inicial e Funcionalidade | 
| [Luan Vinícius](https://github.com/luannvi) | Classificação dos requisitos de Desempenho |
| [Miqueias Ezequiel](https://github.com/Kael-web7) | Classificação dos requisitos de Design |
| [Samuel Felipe](https://github.com/TerminaKng05) | Classificação dos requisitos de Confiabilidade |
| [Nayra Nery](https://github.com/NayraNery127) | Classificação dos requisitos de Usabilidade |
| [Heyttor Augusto](https://github.com/H3ytt0r62) | Classificação dos requisitos de Suportabilidade |

##  Especificação de Requisitos

###  F - Funcionalidade (Requisitos Funcionais Complementares)

Autor: [João Pedro](https://github.com/Jadequilin)

A funcionalidade refere-se aos requisitos funcionais que complementam os casos de uso principais, representando capacidades adicionais do sistema que não foram adequadamente capturadas na modelagem inicial.

*<p style="text-align: center;">Tabela 3: Requisitos funcionais que complementam os casos de uso principais</p>*

| ID | Descrição | Status | Rastreabilidade |
|:---:|-----------|:--------:|:---------------|
| [**RF33**](../../Pós-rastreabilidade/Backward%20from.md#rf33) | O aplicativo apresenta funções de acessibilidade aos idosos e deficientes | Não Implementado | [ENT15](../Elicitação/Técnicas/Entrevista.md) |
| [**RF36**](../../Pós-rastreabilidade/Backward%20from.md#rf36) | As páginas do aplicativo mais usadas pelo usuário estão em destaque na tela | Não Implementado | [ENT23](../Elicitação/Técnicas/Entrevista.md) |
| [**RF37**](../../Pós-rastreabilidade/Backward%20from.md#rf37) | O sistema fornece avisos ao usuário sobre seu limite diário de apostas | Não Implementado | [ENT25](../Elicitação/Técnicas/Entrevista.md) |
| [**RF28**](../../Pós-rastreabilidade/Backward%20from.md#rf28) | O aplicativo deve permitir o cancelamento de apostas antes do sorteio | Não Implementado | [OBS16](../Elicitação/Técnicas/Observação.md) |

### Validação com o Usuário (Funcionalidade)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

###  + - Design e Implementação

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

Esta categoria aborda requisitos relacionados a linguagens, ferramentas, padrões e restrições técnicas de implementação, bem como requisitos de design e arquitetura do sistema.

*<p style="text-align: center;">Tabela 4: Requisitos de design e implementação</p>*

| ID | Descrição | Status | Rastreabilidade |
|:---:|-----------|:--------:|:---------------|
| [**RNF19**](../../Pós-rastreabilidade/Backward%20from.md#rnf19) | O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados | Não Implementado | [AD13](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [**RNF20**](../../Pós-rastreabilidade/Backward%20from.md#rnf20) | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real | Não Implementado | [AD14](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [**RNF12**](../../Pós-rastreabilidade/Backward%20from.md#rnf12) | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store) | Implementado | [AD05](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [**RNF13**](../../Pós-rastreabilidade/Backward%20from.md#rnf13) | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema | Implementado | [AD06](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [**RNF14**](../../Pós-rastreabilidade/Backward%20from.md#rnf14) | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica | Implementado | [AD07](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |

### Validação com o Usuário (Design e Implementação)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

### + - Design (Restrições de Design e Padrões de Interface)

Autor: [Miquéias Ezequiel](https://github.com/Kael-web7)

Restrições de design abrangem padrões visuais, diretrizes de interface, compatibilidade com dispositivos e princípios de design que o sistema deve seguir.

*<p style="text-align: center;">Tabela 5: Restrições de design e padrões de interface</p>*

| **ID**   | **Descrição**                                                                                                                                  | **Status**              |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| **RN01** | A interface deve seguir as diretrizes de design da Caixa Econômica Federal, utilizando paleta de cores e tipografia padronizadas.              | **Implementado**              |
| **RN02** | O sistema deve ser compatível com dispositivos móveis Android e iOS, mantendo o mesmo layout e desempenho.                                     | **Implementado**              |
| **RN03** | A interface deve garantir usabilidade e acessibilidade: botões bem visíveis, texto legível e opção de ajuste de fonte e contraste.             | **Parcialmente implementado** |
| **RN04** | O aplicativo deve oferecer modo claro e modo escuro, ajustável manualmente e sincronizado com o sistema operacional do usuário.                | **Não implementado**          |
| **RN07** | O aplicativo deve incluir um tutorial interativo na primeira execução, explicando as principais funções (login, busca, pagamento, resultados). | **Não implementado**          |
| **RN08** | O tempo de resposta entre ação do usuário e retorno visual deve ser inferior a 2 segundos em condições normais de rede.                        | **Parcialmente implementado** |
| **RN12** | O design deve permitir futuras expansões (ex: novos tipos de jogos ou formas de pagamento) sem necessidade de reestruturação completa.         | **Parcialmente implementado** |
| **RN13** | O aplicativo deve alcançar ≥ 90% de avaliações positivas quanto à clareza e facilidade de uso nas pesquisas de satisfação.                     | **Não implementado**          |
| **RN14** | Deve reduzir para ≤ 5% os usuários que relatam dificuldade em encontrar funções como busca, pagamento e resultados.                            | **Não implementado**          |
| **RN15** | Todos os ícones e elementos visuais devem possuir rótulos alternativos (alt text) para compatibilidade com leitores de tela.                   | **Parcialmente implementado** |

### Validação com o Usuário (Design)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ziHnWxbzCk4?si=WeARNwYraMBp_OMv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local |
| ------------ | ----- | ----- | ------ | -------|
| [Miquéias Ezequiel](https://github.com/Kael-web7) | Integrante do grupo, responsável por coordenar a validação com o usuário. | 11/10/2025 | 20:41 | Online(Discord)
| Cléber Ribeiro | 25 anos usuário do app Loterias Caixa, responsável por validar a especificação suplementar desenvolvidos para o artefato. | 11/10/2025 | 20:41 | Online(Discord) |

###  U - Usabilidade

Autor: [Nayra Nery](https://github.com/NayraNery127)

A usabilidade abrange aspectos relacionados à facilidade de uso, experiência do usuário, acessibilidade, interface intuitiva e capacidade de aprendizado do sistema. Nesta seção são apresentados os requisitos que influenciam a usabilidade do sistema, ou seja, aqueles relacionados à forma como o usuário interage com o aplicativo e à facilidade de utilização de suas funcionalidades.

*<p style="text-align: center;">Tabela 6: Requisitos de Usabilidade</p>*

| **ID** | **Descrição** | **Status** | **Rastreabilidade** |
| :----: | :------------- | :---------- | :------------------- |
| [RNF01](../../Pós-rastreabilidade/Backward%20from.md#rnf01) | O software deve ter telas simples, com poucos textos | Implementado | [ENT01](../Elicitação/Técnicas/Entrevista.md) |
| [RNF02](../../Pós-rastreabilidade/Backward%20from.md#rnf02) | O software deve ter imagens explicativas | Não Implementado | [ENT08](../Elicitação/Técnicas/Entrevista.md) |
| [RF06](../../Pós-rastreabilidade/Backward%20from.md#rf06) | O software deve ter opções de cores escuras e claras | Não Implementado | [ENT07](../Elicitação/Técnicas/Entrevista.md) |
| [RF04](../../Pós-rastreabilidade/Backward%20from.md#rf04) | O software deve ter poucas telas | Implementado | [ENT05](../Elicitação/Técnicas/Entrevista.md) |
| [RNF03](../../Pós-rastreabilidade/Backward%20from.md#rnf03) | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo três toques | Implementado | [OBS17](../Elicitação/Técnicas/Observação.md) |
| [RNF06](../../Pós-rastreabilidade/Backward%20from.md#rnf06) | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste | Implementado | [OBS20](../Elicitação/Técnicas/Observação.md) |
| [RNF07](../../Pós-rastreabilidade/Backward%20from.md#rnf07) | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de apostas | Implementado | [OBS21](../Elicitação/Técnicas/Observação.md) |
| [RNF08](../../Pós-rastreabilidade/Backward%20from.md#rnf08) | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis | Implementado | [OBS22](../Elicitação/Técnicas/Observação.md) |
| [RNF09](../../Pós-rastreabilidade/Backward%20from.md#rnf09) | O sistema deve exibir feedback visual em até 1 segundo, destacando o carrinho e mostrando uma confirmação na tela sempre que o usuário adicionar uma aposta. | Implementado | [OBS23](../Elicitação/Técnicas/Observação.md) |
| [RNF11](../../Pós-rastreabilidade/Backward%20from.md#rnf11) | O sistema deve garantir que o acesso às funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação devem ser acompanhados por rótulos textuais | Não Implementado | [OBS25](../Elicitação/Técnicas/Observação.md) |
| [RNF23](../../Pós-rastreabilidade/Backward%20from.md#rnf23) | O aplicativo é de fácil acesso ao usuário | Implementado | [ENT14](../Elicitação/Técnicas/Entrevista.md) |
| [RF33](../../Pós-rastreabilidade/Backward%20from.md#rf33) | O aplicativo deve apresentar funções de acessibilidade voltadas a idosos e pessoas com deficiência | Não Implementado | [ENT15](../Elicitação/Técnicas/Entrevista.md) |
| [RF34](../../Pós-rastreabilidade/Backward%20from.md#rf34) | As opções de ações dentro do aplicativo devem estar facilmente disponíveis | Implementado | [ENT16](../Elicitação/Técnicas/Entrevista.md) |
| [RF36](../../Pós-rastreabilidade/Backward%20from.md#rf36) | As páginas do aplicativo mais usadas pelo usuário devem estar em destaque na tela | Não Implementado | [ENT23](../Elicitação/Técnicas/Entrevista.md) |
| [RNF29](../../Pós-rastreabilidade/Backward%20from.md#rnf29) | O aplicativo deve permitir que o usuário encontre qualquer modalidade de loteria ou resultado desejado em no máximo 2 toques e 3 segundos, com itens do menu claramente rotulados na tela inicial. | Implementado | [ENT24](../Elicitação/Técnicas/Entrevista.md) |

### Validação com o Usuário (Usabilidade)

<iframe width="560" height="315" src="https://www.youtube.com/embed/G98rq24DcHw?si=cB0ugEtGIuzD5nsP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local |
| ------------ | ------ | ---- | ------- | ----- |
| [Nayra Nery](https://github.com/NayraNery127) | Integrante do grupo, responsável por conduzir e coordenar a entrevista de usabilidade com o usuário. | 12/10/2025 | 11:20 | Online(Teams) |
| Diassis Nascimento | Jogador de Loterias Caixa, responsável por responder à entrevista de usabilidade e validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Online(Teams) |




###  R - Confiabilidade

Autor: [Samuel Felipe](https://github.com/TerminaKng05)

Confiabilidade refere-se ao quão confiável é o sistema, considerando a frequência de falhas, possibilidade de recuperação, prevenção de erros, tempo entre as falhas e segurança da informação. Abrange autenticação de usuários, proteção de dados e mecanismos de recuperação de falhas.

Para essa categoria, os requisitos identificados estão representados na tabela 7 a seguir.

*<p style="text-align: center;">Tabela 7: Requisitos de Confiabilidade</p>*

| **ID** | **Descrição** | **Status** | **Rastreabilidade** |
| :----: | :----------- | :--------: | :---------------: |
| [RF09](../../Pós-rastreabilidade/Backward%20from.md#rf09) | Deve haver uma verificação de identidade para login no aplicativo | Implementado | [ENT11](../Elicitação/Técnicas/Entrevista.md) |
| [RF12](../../Pós-rastreabilidade/Backward%20from.md#rf12) | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | Implementado | [OBS01](../Elicitação/Técnicas/Observação.md) |
| [RF14](../../Pós-rastreabilidade/Backward%20from.md#rf14) | O aplicativo deve permitir login com CPF e senha ou com biometria | Implementado | [OBS03](../Elicitação/Técnicas/Observação.md) |
| [RF24](../../Pós-rastreabilidade/Backward%20from.md#rf24) | O aplicativo deve mostrar se o pagamento foi confirmado | Implementado | [OBS12](../Elicitação/Técnicas/Observação.md) |
| [RF26](../../Pós-rastreabilidade/Backward%20from.md#rf26) | O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | Implementado | [OBS14](../Elicitação/Técnicas/Observação.md) |
| [RF28](../../Pós-rastreabilidade/Backward%20from.md#rf28) | O aplicativo deve permitir o cancelamento de apostas antes do sorteio | Não Implementado | [OBS16](../Elicitação/Técnicas/Observação.md) |
| [RNF05](../../Pós-rastreabilidade/Backward%20from.md#rnf05) | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | Implementado | [OBS19](../Elicitação/Técnicas/Observação.md) |
| [RNF10](../../Pós-rastreabilidade/Backward%20from.md#rnf10) | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | Implementado | [OBS24](../Elicitação/Técnicas/Observação.md) |
| [RNF13](../../Pós-rastreabilidade/Backward%20from.md#rnf13) | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema | Implementado | [AD06](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [RNF17](../../Pós-rastreabilidade/Backward%20from.md#rnf17) | O resgate dos prêmios é disponibilizado nos canais oficiais da empresa (Unidade Lotérica, Agência Caixa e Mercado Pago) | Implementado | [AD10](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| [RNF24](../../Pós-rastreabilidade/Backward%20from.md#rnf24) | O aplicativo é de uma fonte confiável para o usuário | Implementado | [ENT17](../Elicitação/Técnicas/Entrevista.md) |
| [RF35](../../Pós-rastreabilidade/Backward%20from.md#rf35) | Os dados do usuário são mantidos em sigilo e protegidos | Implementado | [ENT18](../Elicitação/Técnicas/Entrevista.md) |
| [RNF25](../../Pós-rastreabilidade/Backward%20from.md#rnf25) | Há um termo de uso | Implementado | [ENT19](../Elicitação/Técnicas/Entrevista.md) |
| [RNF26](../../Pós-rastreabilidade/Backward%20from.md#rnf26) | O termo de uso especifica os riscos para o usuário | Não Implementado | [ENT20](../Elicitação/Técnicas/Entrevista.md) |
| [RNF27](../../Pós-rastreabilidade/Backward%20from.md#rnf27) | O termo de uso especifica a classificação indicativa para o usuário | Implementado | [ENT21](../Elicitação/Técnicas/Entrevista.md) |
| [RNF28](../../Pós-rastreabilidade/Backward%20from.md#rnf28) | O termo de uso especifica o acesso aos dados do aplicativo para o usuário | Implementado | [ENT22](../Elicitação/Técnicas/Entrevista.md) |

###  P - Desempenho

Autor: [Luan Vinícius](https://github.com/luannvi)

O desempenho diz respeito às condições técnicas que os requisitos devem atender. Envolve a velocidade, limites superiores e inferiores de carga, tempo de resposta, throughput, restrições de interface e de funções. Define parâmetros mensuráveis para a eficiência operacional do sistema.

Para essa categoria os requisitos identificados estão representados na tabela 8 a seguir.

*<p style="text-align: center;">Tabela 8: Requisitos de Desempenho</p>*

| **ID** | **Descrição**                                                                                                            | **Status**           | **Rastreabilidade**                                                        |
| :----: | :----------------------------------------------------------------------------------------------------------------------- | :------------------- | :------------------------------------------------------------------------- |
|  [RNF04](../../Pós-rastreabilidade/Backward%20from.md#rnf04) | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão      | Implementado     | [OBS18](../Elicitação/Técnicas/Observação.md) |
|  [RNF07](../../Pós-rastreabilidade/Backward%20from.md#rnf07) | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | Implementado    | [OBS21](../Elicitação/Técnicas/Observação.md) |
|  [RNF08](../../Pós-rastreabilidade/Backward%20from.md#rnf08) | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis                            | Implementado     | [OBS22](../Elicitação/Técnicas/Observação.md) |
|  [RNF21](../../Pós-rastreabilidade/Backward%20from.md#rnf21) | O aplicativo ainda apresenta lentidão em aparelhos de smartphones antigos                                                | Não Implementado | [AD15](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
|  [RNF22](../../Pós-rastreabilidade/Backward%20from.md#rnf22) | O aplicativo ainda apresenta problemas de desconexão ao se conectar em internet 4G/5G                                    | Não Implementado | [AD16](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |

#### Validação com o Usuário (Desempenho)

<iframe width="560" height="315" src="https://www.youtube.com/embed/NDX3I737f9A?si=Te-NUZP4LyVt0lRG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local |
| ------------ | ----- | ----- | ------ | -------|
| [Luan Vinícius](https://github.com/luannvi) | Integrante do grupo, responsável por coordenar a validação com o usuário. | 12/10/2025 | 17:24 | Online(Discord)
| Matheus Queiroz | 20 anos, estudante de engenharia de software e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 17:24 | Online(Discord) |

###  S - Suportabilidade

Autor: [Heyttor Augusto](https://github.com/H3ytt0r62)

A suportabilidade diz respeito à acessibilidade técnica, manutenibilidade, adaptabilidade, internacionalização e compatibilidade do sistema com diferentes plataformas. Envolve questões de facilidade de suporte técnico, manutenção futura e portabilidade do aplicativo.

*<p style="text-align: center;">Tabela 9: Requisitos de Suportabilidade</p>*

| **ID** | **Descrição** | **Status** | **Rastreabilidade** |
| :----: | :----------- | :--------: | :---------------: |
| [RNF01](../../Pós-rastreabilidade/Backward%20from.md#rnf01) | O software deve ter telas simples com poucos textos | Implementado | [ENT01](../Elicitação/Técnicas/Entrevista.md) |
| [RF06](../../Pós-rastreabilidade/Backward%20from.md#rf06) | O software deve ter opções de modo escuro ou claro | Não Implementado | [ENT07](../Elicitação/Técnicas/Entrevista.md) |
| [RNF12](../../Pós-rastreabilidade/Backward%20from.md#rnf12) | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store) | Implementado | [AD05](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |

##  Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 11**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 11/10/2025.

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

> ESPECIFICAÇÃO SUPLEMENTAR. [S. l.], 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>. Acesso em: 12 out. 2025.

##  Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 11**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 11/10/2025.

> BOOCH, Grady; RUMBAUGH, James; JACOBSON, Ivar. **The Unified Modeling Language User Guide**. Addison-Wesley, 1998.

##  Agradecimentos

O grupo 7 agradece o apoio das ferramentas de inteligência artificial generativa - chatGPT, Google Gemini - na revisão gramatical e estilo de algumas partes do texto. As tecnologias foram utilizadas para organizar e deixar o texto mais claro, além de fornecer exemplos para melhorias na estrutura da especificação suplementar. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

##  Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| `1.0` | 11/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação inicial da especificação suplementar | [João Pedro](https://github.com/Jadequilin) |
| `1.1` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Adição de 2 requisitos não implementados na funcionalidade | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `1.2` | 12/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Adição de coluna de status e seleção de requisitos não implementados na implementação | [João Pedro](https://github.com/Jadequilin) |
| `1.3` | 12/10/2025 | [Luan Vinícius](https://github.com/luannvi) | Adição da especificação de desempenho | [Miquéias Ezequiel](https://github.com/Kael-web7) |
| `1.5` | 12/10/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7) | Adição da especificação de design | [Luan Vinícius](https://github.com/luannvi) |
| `1.6` | 12/10/2025 | [Samuel Felipe](https://github.com/TerminaKng05) | Adição da especificação de confiabilidade | [Heyttor Augusto](https://github.com/H3ytt0r62) |
| `1.7` | 12/10/2025 | [Luan Vinícius](https://github.com/luannvi) | Adição de validação com usuário (desempenho) | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `1.8` | 12/10/2025 | [Nayra Nery](https://github.com/NayraNery127) | Adição da usabilidade | [Heyttor Augusto](https://github.com/H3ytt0r62) |
| `1.9` | 12/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62) | Adição da suportabilidade | [Nayra Nery](https://github.com/NayraNery127) |
| `2.0` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Adição de vídeos da validação | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `2.1` | 21/10/2025 | [João Pedro](https://github.com/Jadequilin) | Correção dos IDs de referência à requisitos | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `2.2` | 18/11/2025 | [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Adição de explicação detalhada de FURPS+, correção de todas as referências, adição de hyperlinks e agradecimentos à IA | [Luan Vinícius](https://github.com/luannvi) |

| ``2.3``     | 20/11/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7)    | Especificação aprimorada RNF09 e RNF30 | [Luan Vinícius](https://github.com/luannvi) |
