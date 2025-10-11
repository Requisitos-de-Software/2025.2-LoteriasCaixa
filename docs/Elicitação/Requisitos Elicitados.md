## Introdução
Essa página reúne todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [análise de documentos](Técnicas/Análise%20de%20Documentos.md), [entrevista](Técnicas/Entrevista.md), [glossário](Técnicas/Glossário.md) e [observação](Técnicas/Observação.md).

## Metodologia 
A tabela 1 apresenta os requisitos funcionais e não funcionais, sendo que cada linha contém um ID, sua respectiva descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisitão em questão e se ele foi implementado ou não.

A legenda para cada sigla:

| Sigla  | Descrição | 
| :-----------: | :----------: |
| RFxx | Requisito Funcional |
| RNFxx | Requisito Não-Funcional | 
| ENTxx | Requisito elicitado pela Entrevista | 
| ADxx | Requisito elicitado pela Análise de Documentos |
| OBSxx| Requisito elicitado pela Observação  | 
| GLRxx | Requisito elicitado pelo Glossário |

## Requisitos funcionais 

*<p style="text-align: center;">Tabela 1: Requisitos consolidados.</p>*

| ID | Descrição | Status | Rastreabilidade | 
|:----:|: -----------:|: ----------: | :--------:|
|RNF01| O software deve ter telas simples com poucos textos | Implementado | [ENT01](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado)| 
|RF01|  O usuário deve receber Comprovantes de seus ganhos e apostas | Implementado | [ENT02](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) |
|RF02|  O usuário deve ter mais de uma opção de aposta | Implementado| [ENT03](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF03|  O usuário deve poder acompanhar jogos pelo software | Não implementado |[ENT04](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF04|  O software deve ter poucas telas | Implementado | [ENT05](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF05|  O usuário deve poder consultar seus ganhos | Implementado | [ENT06](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado)| 
|RF06|  O software deve ter opções de cores escuras e claras | Não Implementado | [ENT07](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado)| 
|RNF02|  O software deve ter imagens explicativas | Não Implementado | [ENT08](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF07|  O usuário deve receber o resultado das apostas | Implementado | [ENT09](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF08| O usuário deve poder fazer login no aplicativo | Implementado | [ENT10](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF09| Deve haver uma verificação de identidade para login no aplicativo | Implementado | [ENT11](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF10| O usuário deve poder acessar o próprio perfil | Implementado | [ENT12](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF11| O usuário deve poder fazer logout no aplicativo | Implementado | [ENT13](./Técnicas/Entrevista.md/#pela-entrevista-1-foi-identificado) | 
|RF12| O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | Implementado | [OBS01](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF13| O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar | Implementado | [OBS02](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF14| O aplicativo deve permitir login com CPF e senha ou com biometria | Implementado | [OBS03](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF15| O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.) | Implementado | [OBS04](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF16| O aplicativo deve exibir o último resultado do sorteio de cada loteria | Implementado | [OBS05](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF17| O aplicativo deve possibilitar a escolha de números para fazer uma aposta | Implementado | [OBS06](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF18| O aplicativo deve permitir limpar a seleção feita | Implementado | [OBS07](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF19| O aplicativo deve permitir completar a aposta com números aleatórios | Implementado | [OBS08](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF20| O aplicativo deve permitir adicionar o jogo ao carrinho de apostas | Implementado | [OBS09](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF21| O aplicativo deve calcular automaticamente o valor da aposta | Implementado | [OBS10](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF22| O aplicativo deve possibilitar pagamento via cartão de crédito ou PIX | Implementado | [OBS11](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF23| O aplicativo deve mostrar se o pagamento foi confirmado | Implementado | [OBS12](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF24| O aplicativo deve permitir visualizar sua aposta | Implementado | [OBS13](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF25| O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | Implementado | [OBS14](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF26| O aplicativo deve possibilitar logout do usuário | Implementado | [OBS15](./Técnicas/Observação.md/#requisitos-funcionais) |
|RF27| O aplicativo deve permitir o cancelamento de apostas antes do sorteio. | Não Implementado | [OBS16](./Técnicas/Observação.md/#requisitos-funcionais) |
| RNF03 | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 3 toques | Implementado | [OBS16](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF04 | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão | Implementado | [OBS17](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF05 | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | Implementado | [OBS18](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF06 | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste | Implementado | [OBS19](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF07 | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | Implementado | [OBS20](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF08 | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis | Implementado | [OBS21](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF09 | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho | Implementado | [OBS22](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF10 | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | Implementado | [OBS23](./Técnicas/Observação.md/#requisitos-não-funcionais) |
| RNF11 | O sistema deve garantir que o acesso a funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex: "Menu"). | Não Implementado | [OBS24](./Técnicas/Observação.md/#requisitos-não-funcionais) |

  


## Versionamento 

| Versão | Data       | Autor               | Descrição                                    | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 10/10/2025 | [Heyttor Augusto](https://github.com/H3ytt0r62)   | Criação da página com os requisitos de Entrevista | [Samuel Felipe](https://github.com/TerminaKng05) |
| ``1.1``     | 11/10/2025 | [Luan Vinícius](https://github.com/luannvi)    | Adição dos requisitos de Observação | |