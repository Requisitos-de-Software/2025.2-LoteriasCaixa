# Especificação Suplementar

##  Introdução

Este documento apresenta a **Especificação Suplementar** do sistema **Loterias Caixa** seguindo o modelo FURPS+, abordando **requisitos não funcionais** e **requisitos funcionais complementares** que não foram adequadamente representados nos casos de uso.

##  Metodologia

A especificação foi elaborada utilizando o **modelo FURPS+** adaptado, incluindo requisitos elicitados através de entrevistas, observações e análise de documentos.

##  Modelo Usado

### Tabela 1 - Categorias do Modelo FURPS+ para Especificação Suplementar

| Categoria | Descrição |
|-----------|-----------|
| *Design* | Restrições de design e padrões de interface |
| *Implementação* | Linguagens, ferramentas e restrições de construção |
| *Funcionalidade* | Características funcionais e capacidades do sistema |
| *Usabilidade* | Facilidade de uso, aprendizado e acessibilidade |
| *Confiabilidade* | Disponibilidade, tolerância a falhas e recuperação |
| *Desempenho* | Tempo de resposta, throughput e eficiência |
| *Suportabilidade* | Adaptabilidade, manutenibilidade e internacionalização |


## Vídeo da validação 

Link da Gravação Especificação suplementar Nayra Nery:
[Gravação Especificação Suplementar.](https://www.youtube.com/watch?v=G98rq24DcHw)

##  Tabela de Contribuição

### Tabela 2 - Contribuição na Especificação Suplementar 

| Aluno | Seções Desenvolvidas |
|-------|---------------------|
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | Especificação suplementar inicial e implementação |
| [João Pedro](https://github.com/Jadequilin) | Organização especificação inicial e funcionalidade | 
| [Luan Vinícius](https://github.com/luannvi) | Classificação dos requisitos de desempenho |
| [Miqueias Ezequiel](https://github.com/Kael-web7) | Classificação dos requisitos de design |
| [Samuel Felipe](https://github.com/TerminaKng05) | Classificação dos requisitos de confiabilidade |
| [Nayra Nery](https://github.com/NayraNery127) | Classificação dos requisitos de usuabilidade |
| [Heyttor Augusto](https://github.com/H3ytt0r62) | Classificação dos requisitos de suportabilidade |



##  Especificação de Requisitos

###  Funcionalidade (Requisitos Funcionais Complementares)
Autor: João Pedro
tabela 3: Requisitos funcionais que complementam os casos de uso principais*

| ID | Descrição | Status | Rastreabilidade |
|:---:|-----------|:--------:|:---------------|
| **RF12** | O aplicativo apresenta funções de acessibilidade aos idosos e deficientes | Não Implementado | **ENT15** |
| **RF15** | As páginas do aplicativo mais usadas pelo usuário estão em destaque na tela | Não Implementado | **ENT23** |
| **RF16** | O sistema fornece avisos ao usuário sobre seu limite diário de apostas | Não Implementado | **ENT25** |
| **RF27** | O aplicativo deve permitir o cancelamento de apostas antes do sorteio | Não Implementado | **OBS16** |

### Validação com o Usuário (Funcionalidade)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

###  Implementação
Autor: Rivadalvio Joaquim 
tabela 4: Requisitos não funcionais relacionados a tecnologias e arquitetura*

| ID | Descrição | Status | Rastreabilidade |
|:---:|-----------|:--------:|:---------------|
| **RNF20** | O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados | Não Implementado | **AD13** |
| **RNF21** | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real | Não Implementado | **AD14** |
| **RNF12** | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso | Implementado | **AD05** |
| **RNF13** | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema | Implementado | **AD06** |
| **RNF14** | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica | Implementado | **AD07** |

### Validação com o Usuário (Implementação)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

### Design
Autor: Miquéias Ezequiel Gonçalves Carvalho

tabela 5: Restrições de design e padrões de interface

| **ID**   | **Descrição**                                                                                                                                  | **Rastreamento**              |
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

### Validação com o Usuário (tabela 5)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ziHnWxbzCk4?si=WeARNwYraMBp_OMv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local |
| ------------ | ----- | ----- | ------ | -------|
| [Miquéias Ezequiel](https://github.com/Kael-web7) | Integrante do grupo, responsável por coordenar a validação com o usuário. | 11/10/2025 | 20:41 | Online(Discord)
| Cléber Ribeiro | 25 anos usuário do app Loterias Caixa, responsável por validar a especificação suplementar desenvolvidos para o artefato. | 11/10/2025 | 20:41 | Online(Discord) |

###  Usabilidade

Autor: [Nayra Nery](https://github.com/NayraNery127)

Nessa seção são apresentados os requisitos que influenciam a usabilidade do sistema, isto é, aqueles relacionados à forma como o usuário interage com o aplicativo e à facilidade de utilização de suas funcionalidades.

<p style="text-align: center;">Tabela 6: Requisitos de Usabilidade.</p>

| **ID** | **Descrição** | **Status** | **Rastreabilidade** |
| :----: | :------------- | :---------- | :------------------- |
| RNF01 | O software deve ter telas simples, com poucos textos. | Implementado | [ENT01](../Elicitação/Técnicas/Entrevista.md/#requisitos-não-funcionais) |
| RNF02 | O software deve ter imagens explicativas. | Não Implementado | [ENT08](../Elicitação/Técnicas/Entrevista.md/#requisitos-não-funcionais) |
| RF06 | O software deve ter opções de cores escuras e claras. | Não Implementado | [ENT07](../Elicitação/Técnicas/Entrevista.md/#requisitos-funcionais) |
| RNF04 | O software deve ter poucas telas. | Implementado | [ENT05](../Elicitação/Técnicas/Entrevista.md/#requisitos-não-funcionais) |
| RNF03 | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo três toques. | Implementado | [OBS16](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF06 | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste. | Implementado | [OBS19](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF07 | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de apostas. | Implementado | [OBS20](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF08 | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis. | Implementado | [OBS21](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF09 | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho. | Implementado | [OBS22](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF11 | O sistema deve garantir que o acesso às funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex.: “Menu”). | Não Implementado | [OBS24](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF03 | O aplicativo é de fácil acesso ao usuário. | Implementado | [ENT14](../Elicitação/Técnicas/Entrevista.md/#requisitos-não-funcionais) |
| RF12 | O aplicativo deve apresentar funções de acessibilidade voltadas a idosos e pessoas com deficiência. | Não Implementado | [ENT15](../Elicitação/Técnicas/Entrevista.md/#requisitos-funcionais) |
| RF13 | As opções de ações dentro do aplicativo devem estar facilmente disponíveis. | Implementado | [ENT16](../Elicitação/Técnicas/Entrevista.md/#requisitos-funcionais) |
| RF15 | As páginas do aplicativo mais usadas pelo usuário devem estar em destaque na tela. | Não Implementado | [ENT23](../Elicitação/Técnicas/Entrevista.md/#requisitos-funcionais) |
| RNF09 | O usuário consegue achar com facilidade o que procura no aplicativo. | Implementado | [ENT24](../Elicitação/Técnicas/Entrevista.md/#requisitos-não-funcionais) |


###  Confiabilidade  

Autor: [Samuel Felipe](https://github.com/TerminaKng05)

Diz respeito ao quão confiável é o sistema, ou seja, qual é a frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Para essa categoria, os requisitos identificados estão representados na tabela 7 a seguir.

*<p style="text-align: center;">Tabela 7: Requisitos de confiabilidade.</p>*

| **ID** | **Descrição** | **Status** | Rastreabilidade** |
| :----: | :-----------: | :--------: | :---------------: |
|RF09| Deve haver uma verificação de identidade para login no aplicativo | Implementado | [ENT11](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) |
|RF12| O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | Implementado | [OBS01](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF14| O aplicativo deve permitir login com CPF e senha ou com biometria | Implementado | [OBS03](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF23| O aplicativo deve mostrar se o pagamento foi confirmado | Implementado | [OBS12](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF25| O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | Implementado | [OBS14](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF27| O aplicativo deve permitir o cancelamento de apostas antes do sorteio. | Não Implementado | [OBS16](./Técnicas/Observação.md/#requisitos-funcionais) |
| RNF05 | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | Implementado | [OBS18](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF10 | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | Implementado | [OBS23](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF02 | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema; | Implementado | [AD06](./Técnicas/Análise%20de%20Documentos.md/#requisitos-não-funcionais) |
| RNF06 | O resgate dos prêmios são apenas disponibilizados nos canais oficiais da empresa, como uma Unidade Lotérica ou Agência Caixa, e no Mercado Pago (Sendo o valor disponível na conta do usuário e ser transferido conforme as regras próprias do meio de pagamento); | Implementado | [AD10](./Técnicas/Análise%20de%20Documentos.md/#requisitos-não-funcionais) |
|RNF04| O aplicativos é de uma fonte confiável para o usuário| Implementado | [ENT17](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado) |
|RF14 | Os dados do usuário são mantidos em sigilo e protegidos| Implementado | [ENT18](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado) |
|RNF05 | Há um termo de uso| Implementado |[ENT19](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado)|
|RNF06 | O termo de uso especifica os riscos para o usuário| Não Implementado | [ENT20](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado)|
|RNF07 | O termo de uso especifica a classificação indicativa para o usuário| Implementado | [ENT21](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado)|
|RNF08 | O termo de uso especifica o acesso aos dados do aplicativo para o usuário| Implementado | [ENT22](./Técnicas/Entrevista.md/#pela-entrevista-2-foi-identificado)|

###  Desempenho

Autor: [Luan Vinícius](https://github.com/luannvi)

Diz respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

Para essa categoria os requisitos identificados estão representados na tabela 8 a seguir.

*<p style="text-align: center;">Tabela 8: Requisitos de desempenho.</p>*

| **ID** | **Descrição**                                                                                                            | **Status**           | **Rastreabilidade**                                                        |
| :----: | :----------------------------------------------------------------------------------------------------------------------- | :------------------- | :------------------------------------------------------------------------- |
|  RNF04 | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão      | Implementado     | [OBS17](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais)               |
|  RNF07 | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | Implementado    | [OBS20](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais)               |
|  RNF08 | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis                            | Implementado     | [OBS21](../Elicitação/Técnicas/Observação.md/#requisitos-não-funcionais)               |
|  RNF11 | O aplicativo ainda apresenta lentidão em aparelhos de smartphones antigos                                                | Não Implementado | [AD15](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
|  RNF12 | O aplicativo ainda apresenta problemas de desconexão ao se conectar em internet 4G/5G                                    | Não Implementado | [AD16](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |

#### Validação com o Usuário (Desempenho)

<iframe width="560" height="315" src="https://www.youtube.com/embed/NDX3I737f9A?si=Te-NUZP4LyVt0lRG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local |
| ------------ | ----- | ----- | ------ | -------|
| [Luan Vinícius](https://github.com/luannvi) | Integrante do grupo, responsável por coordenar a validação com o usuário. | 12/10/2025 | 17:24 | Online(Discord)
| Matheus Queiroz | 20 anos, estudante de engenharia de software e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 17:24 | Online(Discord) |

###  Suportabilidade

Autor:[Heyttor Augusto](https://github.com/H3ytt0r62) 

Diz a respeito da acessibilidade e suporte que os usuarios podem ter usando o aplicativo.

| **ID** | **Descrição** | **Status** | Rastreabilidade** |
| :----: | :-----------: | :--------: | :---------------: |
| RFN01  | O software deve ter telas simples com poucos textos | Implementado | [ENT01](../Elicitação/Requisitos%20Elicitados.md) |
| RF06  | O software deve ter opções de cores escuras e claras | Não implementado | [ENT07](../Elicitação/Técnicas/Entrevista.md) |
| RFN01 | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store) | Não implementado | [AD05](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |

##  Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 11**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 11/10/2025.

> ESPECIFICAÇÃO SUPLEMENTAR. [S. l.], 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>. Acesso em: 12 out. 2025.

##  Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 11**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210637/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf>. Acesso em: 11/10/2025.

##  Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| `1.0` | 11/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação inicial da especificação suplementar | [João Pedro](https://github.com/Jadequilin) |
| `1.1` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Adição de 2 requisitos não implementados na funcionalidade | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `1.2` | 12/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Adição de coluna de status e seleção de requisitos não implementados na implementação | [João Pedro](https://github.com/Jadequilin) |
| `1.3` | 12/10/2025 | [Luan Vinícius](https://github.com/luannvi) | Adição da especificação de performance | [Miquéias Ezequiel](https://github.com/Kael-web7) |
| ``1.5``    | 12/10/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7) | Adição da especificação de design| [Luan Vinícius](https://github.com/luannvi) |
| ``1.6`` | 12/10/2025 | [Samuel Felipe](https://github.com/TerminaKng05) | Adição da especificação de confiabilidade | [Heyttor Augusto](https://github.com/H3ytt0r62) |
| ``1.7`` |  12/10/2025 | [Luan Vinícius](https://github.com/luannvi) | Adiciona validação com o usuario (desempenho) |  | 
| ``1.8`` | 12/10/2025 | [Nayra Nery](https://github.com/NayraNery127) | Adição da usuabilidade | [Heyttor Augusto](https://github.com/H3ytt0r62) |
| ``1.8`` | 12/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62) | Adição da suportabilidade | [Nayra Nery](https://github.com/NayraNery127) |
| `1.9` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Vídeos da validação implementados | [Rivadalvio Joaquim](https://github.com/RivaFilho) |



