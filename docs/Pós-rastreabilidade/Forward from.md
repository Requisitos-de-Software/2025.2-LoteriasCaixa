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

## Ratreabilidade

| ID | Descrição | UC | HU | CNFR | ES | CN | L |
|:---|:---|:---|:---|:---|:---|:---|:---|
| **RF01** | O usuário deve receber Comprovantes de seus ganhos e apostas | - | [HU06](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/%C3%81gil/Hist%C3%B3ria%20de%20usu%C3%A1rio/)| - | - | - | [L06](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/L%C3%A9xicos/)|
| **RF02** | O usuário deve ter mais de uma opção de aposta | - | - | - | - | [CN03](../Modelagem/Cenários.md/#CN03)| - | 
| **RF03** | O usuário deve poder acompanhar jogos pelo software | - | [HU19](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/%C3%81gil/Hist%C3%B3ria%20de%20usu%C3%A1rio/)| - | - | - |  [L27](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/L%C3%A9xicos/) |
| **RF04** | O software deve ter poucas telas | - | [HU24](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/%C3%81gil/Hist%C3%B3ria%20de%20usu%C3%A1rio/) | - | - | - |  - |
| **RF05** | O usuário deve poder consultar seus ganhos | - | [HU16](https://requisitos-de-software.github.io/2025.2-LoteriasCaixa/Modelagem/%C3%81gil/Hist%C3%B3ria%20de%20usu%C3%A1rio/)  | - | - | - |  - |
| **RF06** | O software deve ter opções modo claro e modo escuro | - | [HU01](../Modelagem/Ágil/História%20de%20usuário.md/#HU01) | [suportabilidade](../Modelagem/Especificação%20Suplementar.md) | - | - |  [L09](../Modelagem/Léxicos.md/#L09) |
| **RF07** | O usuário deve receber o resultado das apostas |  - | [HU03](../Modelagem/Ágil/História%20de%20usuário.md/#HU03) | - | - | - |  - |
| **RF08** | O usuário deve poder fazer login no aplicativo | - | - | - | - | - |  - |
| **RF09** | Deve haver uma verificação de identidade para login no aplicativo | - | [HU02](../Modelagem/Ágil/História%20de%20usuário.md/#HU02) | - | - | - |  - |
| **RF10** | O usuário deve poder acessar o próprio perfil |  - | [HU23](../Modelagem/Ágil/História%20de%20usuário.md/#HU23 ) | - | - | - |  - |
| **RF11** | O usuário deve poder fazer logout no aplicativo | - | [HU38](../Modelagem/Ágil/História%20de%20usuário.md/#HU38) | - | - | - |  - |
| **RF12** | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais. | - | [HU04](../Modelagem/Ágil/História%20de%20usuário.md/#HU04) | - | - | - | - |
| **RF13** | O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar. | - | [HU41](../Modelagem/Ágil/História%20de%20usuário.md/#HU41) | - | - | - | - |
| **RF14** | O aplicativo deve permitir login com CPF e senha ou com biometria. | - | - | - | - | - | - |
| **RF15** | O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.). | [UC01](../Modelagem/Casos%20de%20uso.md) | [HU15](../Modelagem/Ágil/História%20de%20usuário.md/#HU15) | - | - | - | [L12](../Modelagem/Léxicos.md/#L12) |
| **RF16** | O aplicativo deve exibir o último resultado do sorteio de cada loteria. | [UC02](../Modelagem/Casos%20de%20uso.md) | [HU05](../Modelagem/Ágil/História%20de%20usuário.md) | - | - | - | - |
| **RF17** | O aplicativo deve possibilitar a escolha de números para fazer uma aposta. | - | [HU33](../Modelagem/Ágil/História%20de%20usuário.md/#HU33) | - | - | - | [L05](../Modelagem/Léxicos.md) |
| **RF18** | O aplicativo deve permitir limpar a seleção feita. | - | - | - | - | - | [L11](../Modelagem/Léxicos.md/#L05) |
| **RF19** | O aplicativo deve permitir completar a aposta com números aleatórios. | - | [HU34](../Modelagem/Ágil/História%20de%20usuário.md/#HU34) | - | - | [CN01](../Modelagem/Cenários.md/#CN01) | [L09](../Modelagem/Léxicos.md/#L09) |
| **RF29** | A realização de pagamento das apostas são acessíveis a quem usa o aplicativo, sendo cartão de crédito e débito ou Pix; | - | - | - | - | [CN29](../Modelagem/Cenários.md) |  [L19](../Modelagem/Léxicos.md/#L19), [L25](../Modelagem/Léxicos.md/#L25) |
| **RF30** |As apostas são registradas dentro do app com base no CPF do usuário; | - | - | - | - | [CN08](../Modelagem/Cenários.md/#CN08) | [L01](../Modelagem/Léxicos.md/#L01), [L26](../Modelagem/Léxicos.md/#L26) |
| **RF31** | O aplicativo apresenta todos os resultados e as arrecadações dos concursos, como também estimativa para os próximos sorteios; | - | [HU28](../Modelagem/Ágil/História%20de%20usuário.md/#HU28) | - | - | [CN12](../Modelagem/Cenários.md/#CN12) | [L27](../Modelagem/Léxicos.md/#L27) |
| **RF32** | O aplicativo apresenta uma aba de transparência e prestação de contas à sociedade chamada de "Repasses Sociais", onde há os valores repassados pelas Loterias CAIXA em áreas de desenvolvimento social; | - | [HU28](../Modelagem/Ágil/História%20de%20usuário.md/#HU28) | - | - | [CN13](../Modelagem/Cenários.md/#CN13) |  - |
| **RNF01** | O software deve ter telas simples com poucos textos |- | - | [CNFR01](../Modelagem/Ágil/NFR.md/#CNFR01) | [suportabilidade](../Modelagem/Especificação%20Suplementar.md)  | - |  - |
| **RNF02** | O software deve ter imagens explicativas |- | [Hu13](../Modelagem/Ágil/História%20de%20usuário.md/#HU13)| - | - | [CN02](../Modelagem/Cenários.md/#CN02) |  - |
| **RNF03** | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 3 toques para ir de uma seção a outra. | - | - | [CNFR07](../Modelagem/Ágil/NFR.md/#CNFR07) | Usabilidade | - | [L30](../Modelagem/Léxicos.md/#L30--sistema-de-resgate) |
| **RNF04** | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão. | - | [HU36](../Modelagem/Ágil/História%20de%20usuário.md/#HU36) | [CNFR08](../Modelagem/Ágil/NFR.md/#CNFR08) | Desempenho | - | - |
| **RNF05** | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão. | - | - | - | - | - | - |
| **RNF06** | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste. | - | [HU07](../Modelagem/Ágil/História%20de%20usuário.md/#HU07), [HU33](../Modelagem/Ágil/História%20de%20usuário.md/#HU33) | [CNFR09](../Modelagem/Ágil/NFR.md/#CNFR09) | Usabilidade | - | - |
| **RNF07** | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta. | - | [HU11](../Modelagem/Ágil/História%20de%20usuário.md/#HU11) | [CNFR10](../Modelagem/Ágil/NFR.md/#CNFR10) | Desempenho - Usabilidade | - | - |
| **RNF12** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | - | - | [CNFR14](../Modelagem/Ágil/NFR.md/#CNFR14) | [Suportabilidade](../Modelagem/Especificação%20Suplementar.md) | - |  - |
| **RNF13** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md) | - |  - |
| **RNF14** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | - | - | - | - | - | [L28](../Modelagem/Léxicos.md/#L28) |
| **RNF15** | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | - | - | [CNFR14](../Modelagem/Ágil/NFR.md/#CNFR14) | - | - |  - |
| **RNF16** | O aplicativo apresenta uma funcionalidade chamada "rapidão", onde é montada uma aposta com base nas preferências do usuário; | - | [HU37](../Modelagem/Ágil/História%20de%20usuário.md/#HU37) | - | - | - |  [L29](../Modelagem/Léxicos.md/#l29--aposta-rápida) |
| **RNF17** | O resgate dos prêmios são apenas disponibilizados nos canais oficiais da empresa, como uma Unidade Lotérica ou Agência Caixa, e no Mercado Pago (Sendo o valor disponível na conta do usuário e ser transferido conforme as regras próprias do meio de pagamento); | - | - | - | [Confiabilidade](../Modelagem/Especificação%20Suplementar.md) | - | - |
| **RNF18** | O aplicativo apresenta uma falta de opção de filtro para consulta de apostas premiadas ou concursos não realizados; | - | - | - | - | [CN04](../Modelagem/Cenários.md/#CN04) | [L22](../Modelagem/Léxicos.md/#l22--confiabilidade-do-sistema) |
| **RNF19** | O aplicativo apresenta uma falta de alerta para o usuário sobre uma aposta premiada que ainda não foi resgatada; | - | - | - | - | [CN07](../Modelagem/Cenários.md/#CN07) | [L22](../Modelagem/Léxicos.md/#L22), [L24](../Modelagem/Léxicos.md/#L24) |
| **RNF20** | 	O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados; | - | [HU31](../Modelagem/Ágil/História%20de%20usuário.md/#HU31) | - | [Implementação](../Modelagem/Especificação%20Suplementar.md) | [CN10](../Modelagem/Cenários.md/#CN10) | [L03](../Modelagem/Léxicos.md/#l03--termo-de-responsabilidade), [L23](../Modelagem/Léxicos.md/#L23) |
| **RNF21** | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real; | - | [HU39](../Modelagem/Ágil/História%20de%20usuário.md/#HU39) | - | [Implementação](../Modelagem/Especificação%20Suplementar.md) | [CN10](../Modelagem/Cenários.md/#CN10) | [L08](../Modelagem/Léxicos.md/#l08--acompanhamento-de-jogos) |
| **RNF22** | O aplicativo ainda apresenta lentidão em aparelhos de smartphones antigos; | - | - | [CNFR04](../Modelagem/Ágil/NFR.md/#CNFR04) | [Desempenho](../Modelagem/Especificação%20Suplementar.md) | [CN15](../Modelagem/Cenários.md/#CN15) |  - |
| **RNF23** | O aplicativo ainda apresenta problemas de desconexão ao se conectar em internet 4G/5G; | - | [HU42](../Modelagem/Ágil/História%20de%20usuário.md/#HU42) | - | [Desempenho](../Modelagem/Especificação%20Suplementar.md) | [CNFR04](../Modelagem/Ágil/NFR.md/#CNFR04) | - | - |

## Versionamento 

| Versão | Data       | Autor               | Descrição                                    | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 10/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62)   | Adição Foward-From dos RF de Entrevista| [Samuel Felipe](https://github.com/TerminaKng05) |
| ``1.1``     | 11/10/2025 | [Samuel Felipe](https://github.com/TerminaKng05)    | Adição Foward-From dos RF de Análise de Documento (RF29 a 32, RNF 12 a 23) | [Luan Vinícius](https://github.com/luannvi) |
| ``1.2``     | 11/10/2025 | [Miquéias Ezequiel](https://github.com/Kael-web7)    | Adição Foward-From dos RF de Análise de Documento (RF12 a 19, RNF 03 a 07) | [Luan Vinícius](https://github.com/luannvi) |
| ``1.3``     | 28/10/2025 | [Nayra Silva Nery](https://github.com/NayraNery127)    | Adição Foward-From dos RF de Análise de Documento (RF01, RF03,RF04, RF05, RF08) | [Luan Vinícius](https://github.com/luannvi) |
