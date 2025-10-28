## backward from 
A rastreabilidade é capacidade de rastrear ou encontrar algo ou alguem baseado nos rastros deixados, no contexto de software é a capacidade de acompanhar cada requisito ao longo de todo o ciclo de vida do sistema — desde sua origem até a implementação, testes e manutenção — garantindo que todos sejam atendidos e que qualquer mudança possa ser controlada. Ela permite entender como um requisito influencia outros artefatos do projeto e vice-versa.


 Nesse contexto, a rastreabilidade  pode ser dividida em:
 
 - backward (para trás) refere-se à ligação de um artefato com suas origens , backward from mostra de onde o artefato veio, e backward to mostra para qual requisito ele se refere. 
 - forward (para frente) indica a relação de um requisito com seus resultadosm ,forward from mostra o que deriva do requisito (como código ou testes), e forward to mostra para onde ele conduz dentro do processo de desenvolvimento.

## Metodologia 
As tabelas 1 e 2 apresentam, respectivamente, os requisitos funcionais e não funcionais, sendo que cada linha contém um ID, sua respectiva descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisito em questão e se ele foi implementado ou não.

A legenda para cada sigla:

| Sigla  | Descrição | 
| :-----------: | :----------: |
| RFxx | Requisito Funcional |
| RNFxx | Requisito Não-Funcional | 
| ENTxx | Requisito elicitado pela Entrevista | 
| ADxx | Requisito elicitado pela Análise de Documentos |
| OBSxx| Requisito elicitado pela Observação  | 
| GLRxx | Requisito elicitado pelo Glossário |

## Requisitos Consolidados

### Requisitos Funcionais

*<p style="text-align: center;">Tabela 1: Requisitos Funcionais.</p>*

| ID | Descrição | Status | Rastreabilidade |
|:---|:---|:---|:---|
| **RF01** | O usuário deve receber Comprovantes de seus ganhos e apostas | Implementado | [ENT02](../Elicitação/Técnicas/Entrevista.md) |
| **RF02** | O usuário deve ter mais de uma opção de aposta | Implementado | [ENT03](../Elicitação/Técnicas/Entrevista.md)  |
| **RF03** | O usuário deve poder acompanhar jogos pelo software | Não implementado | [ENT04](../Elicitação/Técnicas/Entrevista.md)  |
| **RF04** | O software deve ter poucas telas | Implementado | [ENT05](../Elicitação/Técnicas/Entrevista.md)  |
| **RF05** | O usuário deve poder consultar seus ganhos | Implementado | [ENT06](../Elicitação/Técnicas/Entrevista.md)  |
| **RF06** | O software deve ter opções de modo claro e escuro | Não Implementado | [ENT07](../Elicitação/Técnicas/Entrevista.md)  |
| **RF07** | O usuário deve receber o resultado das apostas | Implementado | [ENT09](../Elicitação/Técnicas/Entrevista.md)  |
| **RF08** | O usuário deve poder fazer login no aplicativo | Implementado | [ENT10](../Elicitação/Técnicas/Entrevista.md)  |
| **RF09** | Deve haver uma verificação de identidade para login no aplicativo | Implementado | [ENT11](../Elicitação/Técnicas/Entrevista.md)  |
| **RF10** | O usuário deve poder acessar o próprio perfil | Implementado | [ENT12](../Elicitação/Técnicas/Entrevista.md)  |
| **RF11** | O usuário deve poder fazer logout no aplicativo | Implementado | [ENT13](../Elicitação/Técnicas/Entrevista.md) |
| **RF12** | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | Implementado | [OBS01](../Elicitação/Técnicas/Observação.md) |
| **RF13** | O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar | Implementado | [OBS02](../Elicitação/Técnicas/Observação.md) |
| **RF14** | O aplicativo deve permitir login com CPF e senha ou com biometria | Implementado | [OBS03](../Elicitação/Técnicas/Observação.md) |
| **RF15** | O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.) | Implementado | [OBS04](../Elicitação/Técnicas/Observação.md) |
| **RF16** | O aplicativo deve exibir o último resultado do sorteio de cada loteria | Implementado | [OBS05](../Elicitação/Técnicas/Observação.md) |
| **RF17** | O aplicativo deve possibilitar a escolha de números para fazer uma aposta | Implementado | [OBS06](../Elicitação/Técnicas/Observação.md) |
| **RF18** | O aplicativo deve permitir limpar a seleção feita | Implementado | [OBS07](../Elicitação/Técnicas/Observação.md) |
| **RF19** | O aplicativo deve permitir completar a aposta com números aleatórios | Implementado | [OBS08](../Elicitação/Técnicas/Observação.md) |
| **RF20** | O aplicativo deve permitir adicionar o jogo ao carrinho de apostas | Implementado | [OBS09](../Elicitação/Técnicas/Observação.md) |
| **RF21** | O aplicativo deve calcular automaticamente o valor da aposta | Implementado | [OBS10](../Elicitação/Técnicas/Observação.md) |
| **RF22** | O aplicativo deve possibilitar pagamento via cartão de crédito ou PIX | Implementado | [OBS11](../Elicitação/Técnicas/Observação.md) |
| **RF23** | O aplicativo deve permitir pagamento de apostas utilizando carteiras digitais como Google Pay, Apple Pay e Mercado Pago | Não Implementado | [OBS12](../Elicitação/Técnicas/Observação.md) |
| **RF24** | O aplicativo deve mostrar se o pagamento foi confirmado | Implementado | [OBS12](../Elicitação/Técnicas/Observação.md) |
| **RF25** | O aplicativo deve permitir visualizar sua aposta | Implementado | [OBS13](../Elicitação/Técnicas/Observação.md) |
| **RF26** | O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | Implementado | [OBS14](../Elicitação/Técnicas/Observação.md) |
| **RF27** | O aplicativo deve possibilitar logout do usuário | Implementado | [OBS15](../Elicitação/Técnicas/Observação.md) |
| **RF28** | O aplicativo deve permitir o cancelamento de apostas antes do sorteio. | Não Implementado | [OBS16](../Elicitação/Técnicas/Observação.md) |
| **RF29** | A realização de pagamento das apostas são acessíveis a quem usa o aplicativo, sendo cartão de crédito e débito ou Pix; | Implementado | [AD01](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RF30** | As apostas são registradas dentro do app com base no CPF do usuário; | Implementado | [AD02](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RF31** | O aplicativo apresenta todos os resultados e as arrecadações dos concursos, como também estimativa para os próximos sorteios; | Implementado | [AD03](../Elicitação/Técnicas/Análise%20de%20Documentos.md)|
| **RF32** | O aplicativo apresenta uma aba de transparência e prestação de contas à sociedade chamada de "Repasses Sociais", onde há os valores repassados pelas Loterias CAIXA em áreas de desenvolvimento social; | Implementado | [AD04](./Técnicas/Análise%20de%20Documentos.md/#requisitos-não-funcionais) |
| **RF33** | O aplicativo apresenta funções de acessibilidade aos idosos e deficientes | Não Implementado | [ENT15](../Elicitação/Técnicas/Entrevista.md) |
| **RF34** | As opções de ações dentro do aplicativo estão facilmente disponíveis | Implementado | [ENT16](../Elicitação/Técnicas/Entrevista.md) |
| **RF35** | Os dados do usuário são mantidos em sigilo e protegidos | Implementado | [ENT18](../Elicitação/Técnicas/Entrevista.md) |
| **RF36** | As páginas do aplicativo mais usadas pelo usuário estão em destaque na tela | Não implementado | [ENT23](../Elicitação/Técnicas/Entrevista.md) |
| **RF37** | O sistema fornece avisos ao usuário sobre seu limite diário de apostas | Não Implementado | [ENT25](../Elicitação/Técnicas/Entrevista.md) |

### Requisitos Não-Funcionais

*<p style="text-align: center;">Tabela 2: Requisitos Não-Funcionais.</p>*

| ID | Descrição | Status | Rastreabilidade |
|:---|:---|:---|:---|
| **RNF01** | O software deve ter telas simples com poucos textos | Implementado | [ENT01](../Elicitação/Técnicas/Entrevista.md) |
| **RNF02** | O software deve ter imagens explicativas | Não Implementado | [ENT08](../Elicitação/Técnicas/Entrevista.md) |
| **RNF03** | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 3 toques | Implementado | [OBS16](../Elicitação/Técnicas/Observação.md) |
| **RNF04** | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão | Implementado | [OBS17](../Elicitação/Técnicas/Observação.md) |
| **RNF05** | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | Implementado | [OBS18](../Elicitação/Técnicas/Observação.md) |
| **RNF06** | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste | Implementado | [OBS19](../Elicitação/Técnicas/Observação.md) |
| **RNF07** | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | Implementado | [OBS20](../Elicitação/Técnicas/Observação.md) |
| **RNF08** | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis | Implementado | [OBS21](../Elicitação/Técnicas/Observação.md) |
| **RNF09** | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho | Implementado | [OBS22](../Elicitação/Técnicas/Observação.md) |
| **RNF10** | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | Implementado | [OBS23](../Elicitação/Técnicas/Observação.md) |
| **RNF11** | O sistema deve garantir que o acesso a funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex: "Menu"). | Não Implementado | [OBS24](../Elicitação/Técnicas/Observação.md) |
| **RNF12** | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store); | Implementado | [AD05](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF13** | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema; | Implementado | [AD06](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF14** | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica; | Implementado | [AD07](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF15** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | Implementado | [AD08](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF16** | O aplicativo apresenta uma funcionalidade chamada "rapidão", onde é montada uma aposta com base nas preferências do usuário; | Implementado | [AD09](../Elicitação/Técnicas/Análise%20de%20Documentos.md)|
| **RNF17** | O resgate dos prêmios são apenas disponibilizados nos canais oficiais da empresa, como uma Unidade Lotérica ou Agência Caixa, e no Mercado Pago (Sendo o valor disponível na conta do usuário e ser transferido conforme as regras próprias do meio de pagamento); | Implementado | [AD10](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF18** | O aplicativo apresenta uma falta de opção de filtro para consulta de apostas premiadas ou concursos não realizados; | Não implementado | [AD11](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF19** | O aplicativo apresenta uma falta de alerta para o usuário sobre uma aposta premiada que ainda não foi resgatada; | Não implementado | [AD12](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF20** | O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados; | Não implementado | [AD13](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF21** | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real; | Não implementado | [AD14](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF22** | O aplicativo ainda apresenta lentidão em aparelhos de smartphones antigos; | Não implementado | [AD15](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF23** | O aplicativo ainda apresenta problemas de desconexão ao se conectar em internet 4G/5G; | Não implementado | [AD16](../Elicitação/Técnicas/Análise%20de%20Documentos.md) |
| **RNF24** | O aplicativo é de fácil acesso ao usuário | Implementado | [ENT14](../Elicitação/Técnicas/Entrevista.md) |
| **RNF25** | O aplicativos é de uma fonte confiável para o usuário | Implementado | [ENT17](../Elicitação/Técnicas/Entrevista.md) |
| **RNF26** | Há um termo de uso | Implementado | [ENT19](../Elicitação/Técnicas/Entrevista.md) |
| **RNF27** | O termo de uso especifica os riscos para o usuário | Não Implementado | [ENT20](../Elicitação/Técnicas/Entrevista.md)|
| **RNF28** | O termo de uso especifica a classificação indicativa para o usuário | Implementado | [ENT21](../Elicitação/Técnicas/Entrevista.md) |
| **RNF29** | O termo de uso especifica o acesso aos dados do aplicativo para o usuário | Implementado |(../Elicitação/Técnicas/Entrevista.md) |
| **RNF30** | O usuário consegue achar com facilidade o que procura no aplicativo | Implementado | [ENT24](../Elicitação/Técnicas/Entrevista.md) |


## Versionamento 

| Versão | Data       | Autor               | Descrição                                    | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 28/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62)   | Criação da página com os requistos| [Samuel Felipe](https://github.com/TerminaKng05) |
