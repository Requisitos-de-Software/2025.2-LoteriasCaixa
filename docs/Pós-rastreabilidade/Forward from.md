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
| **RF01** | O usuário deve receber Comprovantes de seus ganhos e apostas | - | - | - | - | - |  - |
| **RF02** | O usuário deve ter mais de uma opção de aposta | - | -| - | - | [CN03](../Modelagem/Cenários.md)| - | 
| **RF03** | O usuário deve poder acompanhar jogos pelo software | - | - | - | - | - |  - |
| **RF04** | O software deve ter poucas telas | - | - | - | - | - |  - |
| **RF05** | O usuário deve poder consultar seus ganhos | - | - | - | - | - |  - |
| **RF06** | O software deve ter opções modo claro e modo escuro | - | [HU01](../Modelagem/Ágil/História%20de%20usuário.md) | [suportabilidade](../Modelagem/Especificação%20Suplementar.md) | - | - |  - |
| **RF07** | O usuário deve receber o resultado das apostas |  - | [HU03](../Modelagem/Ágil/História%20de%20usuário.md) | - | - | - |  - |
| **RF08** | O usuário deve poder fazer login no aplicativo | - | - | - | - | - |  - |
| **RF09** | Deve haver uma verificação de identidade para login no aplicativo | - | [HU02](../Modelagem/Ágil/História%20de%20usuário.md) | - | - | - |  - |
| **RF10** | O usuário deve poder acessar o próprio perfil |  - | [HU23](../Modelagem/Ágil/História%20de%20usuário.md) | - | - | - |  - |
| **RF11** | O usuário deve poder fazer logout no aplicativo | - | [HU28](../Modelagem/Ágil/História%20de%20usuário.md) | - | - | - |  - |
| **RNF01** | O software deve ter telas simples com poucos textos |- | - | [CNFR01](../Modelagem/Ágil/NFR.md) | [suportabilidade](../Modelagem/Especificação%20Suplementar.md)  | - |  - |
| **RNF02** | O software deve ter imagens explicativas |- | [Hu13](../Modelagem/Ágil/História%20de%20usuário.md)| - | - | [CN02](../Modelagem/Cenários.md) |  - |