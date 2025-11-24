## Forward from 

A rastreabilidade é capacidade de rastrear ou encontrar algo ou alguem baseado nos rastros deixados, no contexto de software é a capacidade de acompanhar cada requisito ao longo de todo o ciclo de vida do sistema — desde sua origem até a implementação, testes e manutenção — garantindo que todos sejam atendidos e que qualquer mudança possa ser controlada. Ela permite entender como um requisito influencia outros artefatos do projeto e vice-versa.


 Nesse contexto, a rastreabilidade  pode ser dividida em:
 
 - backward (para trás) refere-se à ligação de um artefato com suas origens , backward from mostra de onde o artefato veio, e backward to mostra para qual requisito ele se refere. 
 - forward (para frente) indica a relação de um requisito com seus resultadosm ,forward from mostra o que deriva do requisito (como código ou testes), e forward to mostra para onde ele conduz dentro do processo de desenvolvimento.

## Metodologia 

 Para fazer a rastreabilidade forward-from, foi feita uma matriz onde a primeira e segunda colunas se referem ao requisito enquanto as colunas seguintes se referem a cada um dos tipos de artefatos (Cenários, Léxicos, Casos de Uso, Histórias de Usuário, entre outros).

 | Sigla  |          Técnica de Modelagem       |                      
| ---- | --------------------------------- | 
| UCXX | Casos de uso (User case) |
| HUXX   | Histórias de Usuário |
| CNFRXX | NFR Framework |
| ESXX | Especificação Suplementar |
| CNXX | Cenário |
| LXXX | Léxico |

## Rastreabilidade

### Requisitos Funcionais

| ID | Descrição | UC | HU | CNFR | ES | CN | L |
|:---|:---|:---|:---|:---|:---|:---|:---|
| **RF01** | O usuário deve receber Comprovantes de seus ganhos e apostas | - | [HU06](../Modelagem/Ágil/História%20de%20usuário.md#HU06) | - | - | - | [L06](../Modelagem/Léxicos.md#L06) |
| **RF02** | O usuário deve ter mais de uma opção de aposta | - | - | - | - | [CN03](../Modelagem/Cenários.md#CN03) | [L07](../Modelagem/Léxicos.md#L07) |
| **RF03** | O usuário deve poder acompanhar jogos pelo software | - | [HU19](../Modelagem/Ágil/História%20de%20usuário.md#HU19) | - | - | - | [L08](../Modelagem/Léxicos.md#L08) |
| **RF04** | O software deve ter poucas telas (menos que 20)| - | [HU24](../Modelagem/Ágil/História%20de%20usuário.md#HU24) | - | - | - | [L05](../Modelagem/Léxicos.md#L05) |
| **RF05** | O usuário deve poder consultar seus ganhos | - | [HU16](../Modelagem/Ágil/História%20de%20usuário.md#HU16) | - | - | - | [L11](../Modelagem/Léxicos.md#L11) |
| **RF06** | O software deve ter opções de modo claro e escuro | - | [HU01](../Modelagem/Ágil/História%20de%20usuário.md#HU01) | - | - | [CN01](../Modelagem/Cenários.md#CN01) | [L09](../Modelagem/Léxicos.md#L09) |
| **RF07** | O usuário deve receber o resultado das apostas | - | [HU03](../Modelagem/Ágil/História%20de%20usuário.md#HU03) | - | - | - | [L08](../Modelagem/Léxicos.md#L08) |
| **RF08** | O usuário deve poder fazer login no aplicativo | [UC01](../Modelagem/Casos%20de%20uso.md#UC01) | - | - | - | - | [L12](../Modelagem/Léxicos.md#L12) |
| **RF09** | Deve haver uma verificação de identidade para login no aplicativo | - | [HU02](../Modelagem/Ágil/História%20de%20usuário.md#HU02) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L12](../Modelagem/Léxicos.md#L12) |
| **RF10** | O usuário deve poder acessar o próprio perfil | - | [HU23](../Modelagem/Ágil/História%20de%20usuário.md#HU23) | - | - | - | [L13](../Modelagem/Léxicos.md#L13) |
| **RF11** | O usuário deve poder fazer logout no aplicativo | - | [HU38](../Modelagem/Ágil/História%20de%20usuário.md#HU38) | - | - | - | [L14](../Modelagem/Léxicos.md#L14) |
| **RF12** | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | - | [HU04](../Modelagem/Ágil/História%20de%20usuário.md#HU04) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L15](../Modelagem/Léxicos.md#L15) |
| **RF13** | O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar | - | [HU41](../Modelagem/Ágil/História%20de%20usuário.md#HU41) | - | - | - | [L16](../Modelagem/Léxicos.md#L16) |
| **RF14** | O aplicativo deve permitir login com CPF e senha ou com biometria | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L12](../Modelagem/Léxicos.md#L12) |
| **RF15** | O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.) | [UC01](../Modelagem/Casos%20de%20uso.md#UC01), [UC02](../Modelagem/Casos%20de%20uso.md#UC02) | [HU15](../Modelagem/Ágil/História%20de%20usuário.md#HU15) | - | - | - | [L16](../Modelagem/Léxicos.md#L16) |
| **RF16** | O aplicativo deve exibir o último resultado do sorteio de cada loteria | [UC02](../Modelagem/Casos%20de%20uso.md#UC02) | [HU05](../Modelagem/Ágil/História%20de%20usuário.md#HU05), [HU18](../Modelagem/Ágil/História%20de%20usuário.md#HU18) | - | - | - | [L16](../Modelagem/Léxicos.md#L16) |
| **RF17** | O aplicativo deve possibilitar a escolha de números para fazer uma aposta | - | [HU33](../Modelagem/Ágil/História%20de%20usuário.md#HU33) | - | - | - | [L16](../Modelagem/Léxicos.md#L16) |
| **RF18** | O aplicativo deve permitir limpar a seleção feita | - | - | - | - | - | [L16](../Modelagem/Léxicos.md#L16) |
| **RF19** | O aplicativo deve permitir completar a aposta com números aleatórios | - | [HU34](../Modelagem/Ágil/História%20de%20usuário.md#HU34) | - | - | [CN01](../Modelagem/Cenários.md#CN01) | [L16](../Modelagem/Léxicos.md#L16) |
| **RF20** | O aplicativo deve permitir adicionar o jogo ao carrinho de apostas | - | [HU35](../Modelagem/Ágil/História%20de%20usuário.md#HU35) | - | - | - | [L17](../Modelagem/Léxicos.md#L17) |
| **RF21** | O aplicativo deve calcular automaticamente o valor da aposta | - | - | - | - | - | [L17](../Modelagem/Léxicos.md#L17) |
| **RF22** | O aplicativo deve possibilitar pagamento via cartão de crédito ou PIX | [UC03](../Modelagem/Casos%20de%20uso.md#UC03) | - | - | - | - | [L18](../Modelagem/Léxicos.md#L18) |
| **RF23** | O aplicativo deve permitir pagamento de apostas utilizando carteiras digitais como Google Pay, Apple Pay | - | [HU17](../Modelagem/Ágil/História%20de%20usuário.md#HU17) | - | - | [CN05](../Modelagem/Cenários.md#CN05) | [L18](../Modelagem/Léxicos.md#L18) |
| **RF24** | O aplicativo deve mostrar se o pagamento foi confirmado | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L17](../Modelagem/Léxicos.md#L17) |
| **RF25** | O aplicativo deve permitir visualizar sua aposta | [UC03](../Modelagem/Casos%20de%20uso.md#UC03) | - | - | - | - | [L17](../Modelagem/Léxicos.md#L17) |
| **RF26** | O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | [UC05](../Modelagem/Casos%20de%20uso.md#UC05) | [HU40](../Modelagem/Ágil/História%20de%20usuário.md#HU40) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L06](../Modelagem/Léxicos.md#L06) |
| **RF27** | O aplicativo deve possibilitar logout do usuário | - | - | - | - | - | [L14](../Modelagem/Léxicos.md#L14) |
| **RF28** | O aplicativo deve permitir o cancelamento de apostas antes do sorteio | - | [HU20](../Modelagem/Ágil/História%20de%20usuário.md#HU20) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | [CN06](../Modelagem/Cenários.md#CN06) | [L19](../Modelagem/Léxicos.md#L19) |
| **RF29** | A realização de pagamento das apostas são acessíveis a quem usa o aplicativo, sendo cartão de crédito e débito ou Pix | - | - | - | - | - | [L18](../Modelagem/Léxicos.md#L18) |
| **RF30** | O aplicativo apresenta todos os resultados e as arrecadações dos concursos, como também estimativa para os próximos sorteios | - | - | - | - | - | - |
| **RF31** | O aplicativo apresenta uma aba de transparência e prestação de contas à sociedade chamada de "Repasses Sociais" | - | - | - | - | - | [L28](../Modelagem/Léxicos.md#L28) |
| **RF32** | O aplicativo apresenta funções de acessibilidade aos idosos e deficientes | - | [HU08](../Modelagem/Ágil/História%20de%20usuário.md#HU08) | [CNFR03](../Modelagem/Ágil/NFR.md#CNFR03) | [Funcionalidade](../Modelagem/Especificação%20Suplementar.md#Funcionalidade) | [CN11](../Modelagem/Cenários.md#CN11) | [L04](../Modelagem/Léxicos.md#L04) |
| **RF33** | As opções de ações dentro do aplicativo são acessíveis em 3 cliques para o apostante | - | - | - | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | [L20](../Modelagem/Léxicos.md#L20) |
| **RF34** | Os dados do usuário são mantidos em sigilo e protegidos | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | - |
| **RF35** | As apostas do aplicativo mais jogadas pelo usuário estão em destaque na tela | - | [HU09](../Modelagem/Ágil/História%20de%20usuário.md#HU09) | - | [Funcionalidade](../Modelagem/Especificação%20Suplementar.md#Funcionalidade) | [CN09](../Modelagem/Cenários.md#CN09) | [L02](../Modelagem/Léxicos.md#L02) |
| **RF36** | O sistema fornece avisos ao usuário sobre seu limite diário de apostas | - | [HU10](../Modelagem/Ágil/História%20de%20usuário.md#HU10) | - | [Funcionalidade](../Modelagem/Especificação%20Suplementar.md#Funcionalidade) | [CN08](../Modelagem/Cenários.md#CN08) | [L01](../Modelagem/Léxicos.md#L01) |
| **RF37** | O sistema apresenta uma tela chamada "favoritos", onde o apostante consegue realizar jogos com base nas suas preferências de aposta | - | - | - | - | - | [L02](../Modelagem/Léxicos.md#L02) |
| **RF38** | O aplicativo deve permitir mudar e remover foto de perfil | - | - | - | - | - | [L13](../Modelagem/Léxicos.md#L13) |
| **RF39** | O sistema notifica o apostante quando sua aposta foi premiada | - | [HU12](../Modelagem/Ágil/História%20de%20usuário.md#HU12) | - | - | - | [L31](../Modelagem/Léxicos.md#L31) |
| **RF40** | O aplicativo notifica o usuário dentro do próprio app quando sua aposta é premiada | - | [HU12](../Modelagem/Ágil/História%20de%20usuário.md#HU12), [HU30](../Modelagem/Ágil/História%20de%20usuário.md#HU30) | - | - | - | [L31](../Modelagem/Léxicos.md#L31) |

### Requisitos Não-Funcionais

| ID | Descrição | UC | HU | CNFR | ES | CN | L |
|:---|:---|:---|:---|:---|:---|:---|:---|
| **RNF01** | O software deve ter telas simples com poucos elementos | - | - | [CNFR01](../Modelagem/Ágil/NFR.md#CNFR01) | [Suportabilidade](../Modelagem/Especificação%20Suplementar.md#Suportabilidade), [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | [L05](../Modelagem/Léxicos.md#L05) |
| **RNF02** | O software deve ter imagens explicativas que mostrem as funções principais do aplicativo, em uma aba especial só para elas | - | [HU13](../Modelagem/Ágil/História%20de%20usuário.md#HU13) | - | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | [CN02](../Modelagem/Cenários.md#CN02) | [L10](../Modelagem/Léxicos.md#L10) |
| **RNF03** | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 4 toques | - | - | [CNFR07](../Modelagem/Ágil/NFR.md#CNFR07) | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | [L20](../Modelagem/Léxicos.md#L20), [L30](../Modelagem/Léxicos.md#L30) |
| **RNF04** | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão | - | [HU36](../Modelagem/Ágil/História%20de%20usuário.md#HU36) | [CNFR08](../Modelagem/Ágil/NFR.md#CNFR08) | [Desempenho](../Modelagem/Especificação%20Suplementar.md#Desempenho) | - | [L21](../Modelagem/Léxicos.md#L21) |
| **RNF05** | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L12](../Modelagem/Léxicos.md#L12) |
| **RNF06** | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados | - | [HU07](../Modelagem/Ágil/História%20de%20usuário.md#HU07) | [CNFR09](../Modelagem/Ágil/NFR.md#CNFR09) | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | - |
| **RNF07** | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | - | [HU11](../Modelagem/Ágil/História%20de%20usuário.md#HU11) | [CNFR10](../Modelagem/Ágil/NFR.md#CNFR10) | [Desempenho](../Modelagem/Especificação%20Suplementar.md#Desempenho), [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L22](../Modelagem/Léxicos.md#L22) |
| **RNF08** | A transição de telas durante o fluxo de aposta não deve ter travamentos perceptíveis | - | - | [CNFR02](../Modelagem/Ágil/NFR.md#CNFR02) | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade), [Desempenho](../Modelagem/Especificação%20Suplementar.md#Desempenho) | - | - |
| **RNF09** | O sistema deve exibir feedback visual em até 1 segundo, destacando o carrinho e mostrando uma confirmação na tela sempre que o usuário adicionar uma aposta | - | [HU22](../Modelagem/Ágil/História%20de%20usuário.md#HU22) | [CNFR05](../Modelagem/Ágil/NFR.md#CNFR05) | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | - |
| **RNF10** | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | - | [HU21](../Modelagem/Ágil/História%20de%20usuário.md#HU21) | [CNFR06](../Modelagem/Ágil/NFR.md#CNFR06) | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L23](../Modelagem/Léxicos.md#L23) |
| **RNF11** | O sistema deve garantir que o acesso a funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex: "Menu") | - | [HU32](../Modelagem/Ágil/História%20de%20usuário.md#HU32) | [CNFR11](../Modelagem/Ágil/NFR.md#CNFR11) | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | [CN07](../Modelagem/Cenários.md#CN07) | [L24](../Modelagem/Léxicos.md#L24) |
| **RNF12** | As apostas são registradas dentro do app com base no CPF do usuário | - | [HU27](../Modelagem/Ágil/História%20de%20usuário.md#HU27) | [CNFR12](../Modelagem/Ágil/NFR.md#CNFR12) | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação) | - | [L25](../Modelagem/Léxicos.md#L25) |
| **RNF13** | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS 15.1 ou superior/Apple Store, Android 5.1 ou superior/Play Store) | - | - | - | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação), [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L26](../Modelagem/Léxicos.md#L26) |
| **RNF14** | O aplicativo utiliza o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema | - | - | - | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação) | - | [L26](../Modelagem/Léxicos.md#L26) |
| **RNF15** | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica | - | - | [CNFR14](../Modelagem/Ágil/NFR.md#CNFR14) | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação) | - | [L27](../Modelagem/Léxicos.md#L27) |
| **RNF16** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece | - | [HU37](../Modelagem/Ágil/História%20de%20usuário.md#HU37) | - | - | - | - |
| **RNF17** | O aplicativo apresenta uma funcionalidade chamada "rapidão", onde é montada uma aposta com base nas preferências do usuário | - | [HU37](../Modelagem/Ágil/História%20de%20usuário.md#HU37) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L29](../Modelagem/Léxicos.md#L29) |
| **RNF18** | O resgate dos prêmios são apenas disponibilizados nos canais oficiais da empresa, como uma Unidade Lotérica ou Agência Caixa, e no Mercado Pago | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | [L30](../Modelagem/Léxicos.md#L30) |
| **RNF19** | O aplicativo apresenta a opção de filtrar as apostas premiadas ou concursos não realizados | - | [HU11](../Modelagem/Ágil/História%20de%20usuário.md#HU11) | - | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação) | - | - |
| **RNF20** | O aplicativo deve apresentar uma forma de mostrar os resultados em tempo real | - | [HU31](../Modelagem/Ágil/História%20de%20usuário.md#HU31) | - | [Design e Implementação](../Modelagem/Especificação%20Suplementar.md#Design-e-Implementação) | [CN15](../Modelagem/Cenários.md#CN15) | - |
| **RNF21** | O aplicativo mostra os resultado dos jogos realizados em "tempo real", com 5 segundos de atraso máximo | [UC04](../Modelagem/Casos%20de%20uso.md#UC04) | [HU39](../Modelagem/Ágil/História%20de%20usuário.md#HU39) | - | [Desempenho](../Modelagem/Especificação%20Suplementar.md#Desempenho) | [CN14](../Modelagem/Cenários.md#CN14) | - |
| **RNF22** | Em dispositivos anteriores ao Android 5.1 e iOS 15.1, o aplicativo é estável para uso | - | - | [CNFR04](../Modelagem/Ágil/NFR.md#CNFR04) | [Desempenho](../Modelagem/Especificação%20Suplementar.md#Desempenho) | - | - |
| **RNF23** | O aplicativo funciona ao utilizar conexão de internet 4G/5G | - | [HU42](../Modelagem/Ágil/História%20de%20usuário.md#HU42) | - | [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | - |
| **RNF24** | O aplicativo é encontrado, pesquisado e utilizado de forma que o apostante sabe o que procura | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | - |
| **RNF25** | O aplicativo é de uma fonte confiável para o usuário | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | - |
| **RNF26** | Há um termo de uso | - | [HU07](../Modelagem/Ágil/História%20de%20usuário.md#HU07) | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | [CN10](../Modelagem/Cenários.md#CN10) | [L03](../Modelagem/Léxicos.md#L03) |
| **RNF27** | O termo de uso especifica os riscos para o usuário | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | [CN10](../Modelagem/Cenários.md#CN10) | [L03](../Modelagem/Léxicos.md#L03) |
| **RNF28** | O termo de uso especifica a classificação indicativa para o usuário | - | - | [CNFR14](../Modelagem/Ágil/NFR.md#CNFR14) | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade) | - | - |
| **RNF29** | O termo de uso especifica o acesso aos dados do aplicativo para o usuário | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md#Confiabilidade), [Usabilidade](../Modelagem/Especificação%20Suplementar.md#Usabilidade) | - | - |
| **RNF30** | O aplicativo deve permitir que o usuário encontre qualquer modalidade de loteria ou resultado desejado em no máximo 2 toques e 3 segundos, com itens do menu claramente rotulados na tela inicial | - | [HU29](../Modelagem/Ágil/História%20de%20usuário.md#HU29) | [CNFR13](../Modelagem/Ágil/NFR.md#CNFR13) | - | - | - |


## Agradecimentos
O grupo 7 agradece o apoio das ferramentas de inteligência artificial generativa - chatGPT, Google Gemini - na revisão gramatical e estilo de algumas partes do texto. As tecnologias foram utilizadas para organizar e deixar o texto mais claro, além de fornecer alguns exemplos de códigos de mkdocs para servir de referência para os autores. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Versionamento 

| Versão | Data       | Autor               | Descrição                                    | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 10/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62)   | Adição Foward-From dos RF de Entrevista| [Samuel Felipe](https://github.com/TerminaKng05) |
| ``1.1``     | 11/10/2025 | [Samuel Felipe](https://github.com/TerminaKng05)    | Adição Foward-From dos RF de Análise de Documento (RF29 a 32, RNF 12 a 23) | [Luan Vinícius](https://github.com/luannvi) |
| ``1.2``     | 11/10/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7)    | Adição Foward-From dos RF de Análise de Documento (RF12 a 19, RNF 03 a 07) | [Luan Vinícius](https://github.com/luannvi) |
| ``1.3``     | 28/10/2025 | [Nayra Silva Nery](https://github.com/NayraNery127)    | Adição Foward-From dos RF de Análise de Documento (RF01, RF03,RF04, RF05, RF08) | [Luan Vinícius](https://github.com/luannvi) |
| ``1.4``     | 28/10/2025 | [João Pedro](https://github.com/Jadequilin)    | Adição dos requisitos RF33-37 e RNF24-30 | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| ``1.5``     | 19/11/2025 | [João Pedro](https://github.com/Jadequilin)    | Correção de duplicados, inclusão de requisitos faltantes e alinhamento com backward from e restante do documento| [João Pedro](https://github.com/Jadequilin) |
| ``1.6``     | 20/11/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7)    | Especificação aprimorada RNF09 e RNF30 | [Luan Vinícius](https://github.com/luannvi) |
| ``1.7`` | 20/11/2025 | [Samuel Felipe](https://github.com/TerminaKng05) | atualização e modificação dos rfs e rnfs | [Heyttor Augusto](https://github.com/H3ytt0r62) |
|``1.8``| 21/11/2015/ | [Heyttor Augusto](https://github.com/H3ytt0r62) | atualização dos requisitos RF04,RF35,RNF01 e NNF02 | [Samuel Felipe](https://github.com/TerminaKng05) |
| ``2.0``     | 20/11/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7)    | Adição RF38 | [Luan Vinícius](https://github.com/luannvi) |
| ``2.1``     | 24/11/2025 | [Luan Vinícius](https://github.com/luannvi)   | Correção da parte restante dos requisitos funcionais e não funcionais   | [Heyttor Augusto](https://github.com/H3ytt0r62) |