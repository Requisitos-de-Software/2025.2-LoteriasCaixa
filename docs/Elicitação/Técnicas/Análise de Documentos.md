## Introdução

Para entendermos melhor como o aplicativo funciona e a interação do usuário com o mesmo, é preciso produzir uma **análise de documentos**, sendo um meio de elicitar requisitos pelo estudo de documentação disponível sobre uma solução existente, para identificar informações relevantes para o desenvolvimento do sistema, sendo por interesses chaves do usuário ou fornecedor.


## Metodologia

Para fazer essa análise de documentos, foi feito uma busca em escopo nas documentações disponibilizadas pela própria empresa de forma pública, sendo elas:
- Os comerciais feitos para o aplicativos disponiveis no youtube e no instagram oficial do aplicativo
- O site da Caixa relatando a visão geral sobre o aplicativo.
- Comentários de notas e avaliações do aplicativo no Google Play

A análise foi feita pelos integrantes [Samuel Felipe](https://github.com/TerminaKng05) e  [Heyttor Augusto](https://github.com/H3ytt0r62)

## Resultado da Análise de documentação

Após anotar os principais elementos retirados da análise da documentação, foi possível elicitar os devidos requisitos funcionais e não funcionais, nas *Tabelas 1 e 2*, respectivamente.

### *Legenda (Tabelas 1 e 2)*
- **RF**: Requisito funcional;
- **RNF**: Requisito não funcional;
- **AD**: Requisito elicitado pela análise de documentos;

### Requisitos funcionais

*<p style="test-align: center;"> Tabela 1: Requisitos funcionais.</p>*

| Tipo | Requisitos | ID |
|:----:| :-------------: |:--:|
| RF01| A realização de pagamento das apostas são acessíveis a quem usa o aplicativo, sendo cartão de crédito e débito ou Pix; | AD01|
| RF02 | As apostas são registradas dentro do app com base no CPF do usuário; | AD02|
| RF03 | O aplicativo apresenta todos os resultados e as arrecadações dos concursos, como também estimativa para os próximos sorteios; | AD03|
| RF04 | O aplicativo apresenta uma aba de trasparência e prestação de contas a sociedade chamada de "Repasses Sociais", onde há os valores repassados pelas Loterias CAIXA em àreas de desenvolvimento social; | AD04|

*<p style= "text-align: center;"> Fonte: <a href= "https://www.caixa.gov.br/atendimento/aplicativos/app-loterias/Paginas/default.aspx">CAIXA Econômica Federal.</a> </p>*

### Requisitos não funcionais

*<p style= "text-align: center;"> Tabela 2: Requisitos não funcionais.</p>*

| Tipo | Requisitos | ID |
|:----:| :---------: |:--:|
| RNF01 | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store); | AD05|
| RNF02 | O aplicativo utiliza tanto o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema; | AD06|
| RNF03 | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica; | AD07|
| RNF04 | O aplicativo segue a lei federal onde apenas maiores de 18 anos podem utilizar as funções que o mesmo oferece; | AD08 |
| RNF05 | O aplicativo apresenta uma funcionalidade chamada "rapidão", onde é montada uma aposta com base nas preferências do usuário; | AD09 |
| RNF06 | O resgate dos prêmios são apenas disponibilizados nos canais oficiais da empresa, como uma Unidade Lotérica ou Agência Caixa, e no Mercado Pago (Sendo o valor disponível na conta do usuário e ser transferido conforme as regras próprias do meio de pagamento); | AD10 |
| RNF07 | O aplicativo apresenta uma falta de opção de filtro para consulta de apostas premiadas ou concursos não realizados; | AD11 |
| RNF08 | O aplicativo apresenta uma falta de alerta para o usuário sobre uma aposta premiada que ainda não foi resgatada; | AD12 |
| RNF09 | O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados; | AD13 |
| RNF10 | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real; | AD14|
| RNF11 | O aplicativo ainda apresenta lentidão em aparelhos de smartphones antigos; | AD15 |
| RNF12 | O aplicativo ainda apresenta problemas de desconexão ao se conectar em internet 4G/5G; | AD16 |

*<p style= "text-align: center;"> Fonte: <a href= "https://www.caixa.gov.br/atendimento/aplicativos/app-loterias/Paginas/default.aspx">CAIXA Econômica Federal</a>, e <a href= "https://play.google.com/store/apps/details?id=br.gov.caixa.loterias.apostas&hl=en_GB&gl=BR&pli=1">APP Loterias CAIXA (Play Store/avaliações) </a>.</p>*


## Bibliografia
- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.
- GOOGLE. Avaliações de usuários sobre o aplicativo Loterias Caixa. Play Store, 2025. Disponível em:https://play.google.com/store/apps/details?id=br.gov.caixa.loterias.apostas&hl=en_GB&gl=BR&pli=1  Acesso em: 29/09/2025
- CAIXA ECONÔMICA FEDERAL.Em alguns segundos, o jogo pode mudar!.Youtube, 06/02/2025. Disponivel em: https://www.youtube.com/watch?v=KNT7SYq3Kc0 , Acesso em: 29/05/2025
- CAIXA ECONÔMICA FEDERAL.As Loterias CAIXA jogam com você., Youtube, 04/02/2025. Disponivel em: https://www.youtube.com/watch?v=AgX2HAZG32s , Acesso em: 29/05/2025
- CAIXA ECONÔMICA FEDERAL.loteriascaixaoficial , Instagram, 04/02/2025. Disponivel em: https://www.instagram.com/loteriascaixaoficial , Acesso em: 29/05/2025
- CAIXA ECONÔMICA FEDERAL. Atendimento, Aplicativos Caixa, Aplicativos Loterias. Disponível em: https://www.caixa.gov.br/atendimento/aplicativos/app-loterias/Paginas/default.aspx , Acesso em: 29/05/2025

# Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|:--------:|:------------:|:---------------------:|:----------------------------------------------:|:---------:|
| ``1.0``    | 25/09/2025 |[Samuel Felipe](https://github.com/TerminaKng05)| Montagem do perfil de usuário | [Heyttor Augusto](https://github.com/H3ytt0r62)     |
|  ``1.1``    | 25/09/2025 |[Samuel Felipe](https://github.com/TerminaKng05)| Adição da tabela de RF e RNF | - |
| ``1.2``    | 12/10/2025 |  [João Pedro](https://github.com/Jadequilin) | Correção de errata RF e RNF| [Samuel Felipe](https://github.com/TerminaKng05) |