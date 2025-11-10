## Introdução

A técnica de observação (etnografia) consiste em permitir ao observador/analista acompanhar diretamente como o usuário interage com o sistema, sendo um recurso valioso quando outros métodos não são suficientes para capturar a execução de tarefas e interações. Esse método é particulamente útil para identificar requisitos sociais, organizacionais e de usabilidade, além de trazer à tona requisitos implícitos que dificilmente seriam revelados em entrevistas normais. 

Nesse processo, o observador pode adotar uma postura **passiva** (apenas registrar o que acontece) ou **ativa** (interagindo e questionando o usuário durante a execução das tarefas). Já o usuário é aquele que desempenha atividades no sistema ou em processos relacionados, podendo ser especialistas ou novatos, dependendo do escopo da análise.

## Metodologia 

Para realizar essa técnica, foi convocado uma pessoa do sexo masculino que entra nas características de perfil de usuário do aplicativo. O usuário foi responsável por navegar pelo aplicativo desde a parte de cadastro/login até a parte de apostas e pagamentos. O observador ficou responsável por extrair cada um dos possíveis requisitos, sendo funcionais e/ou não funcionais, e também optou pela análise ativa, instruindo o usuário em algumas ações. O cronograma e os participantes estão descritos na *Tabela 1*.

## Tabela de contribuição

|Aluno| Contribuição|
|-----|-------------|
|Luan vinicuis| Tecnica Observação |

*Tabela 1: Participantes e funções*

| Participantes | Função | Data | Horário | Reunião |
| :-----------: | :----: | :--: | :-----: | :---: |
| [Luan Vinícius](https://github.com/luannvi) | Observador | 29/09 | 19:58 | Presencial |
| Valdemir da Costa | Usuário | 29/09 | 19:58 | Presencial | 

*Fonte: [Luan Vinícius](https://github.com/luannvi), 2025.*

## Gravação da tela
O link da gravação da tela de onde foi extraída os requisitos da observação se encontra aqui: 
[Gravação (observação).](https://www.youtube.com/watch?v=XA2A58uY8ks)

## Requisitos elicitados

Depois das anotações do observador e com as ações do usuário dentro do aplicativo Loterias Caixa, foi possível elicitar os devidos requisitos funcionais e não funcionais, nas *Tabelas 2 e 3*, respectivamente.

### *Legenda (Tabelas 2 e 3)*
- **RF**: Requisito funcional.
- **RNF**: Requisito não-funcional.
- **OBS**: Requisito elicitado pela observação.

### Requisitos funcionais

*<p style="text-align: center;">Tabela 2: Requisitos funcionais.</p>*

| Tipo  | Requisitos                                                                 |   ID   |
|:-----:|--------------------------------------------------------------------------- |:------:|
| RF01  | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais. | OBS01 |
| RF02  | O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar. | OBS02 |
| RF03  | O aplicativo deve permitir login com CPF e senha ou com biometria.             | OBS03 |
| RF04  | O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.). | OBS04 |
| RF05  | O aplicativo deve exibir o último resultado do sorteio de cada loteria.       | OBS05 |
| RF06  | O aplicativo deve possibilitar a escolha de números para fazer uma aposta.    | OBS06 |
| RF07  | O aplicativo deve permitir limpar a seleção feita.                            | OBS07 |
| RF08  | O aplicativo deve permitir completar a aposta com números aleatórios.         | OBS08 |
| RF09  | O aplicativo deve permitir adicionar o jogo ao carrinho de apostas.           | OBS09 |
| RF10  | O aplicativo deve calcular automaticamente o valor da aposta.                 | OBS10 |
| RF11  | O aplicativo deve possibilitar pagamento via cartão de crédito ou PIX.        | OBS11 |
| RF12  | O aplicativo deve mostrar se o pagamento foi confirmado.                      | OBS12 |
| RF13  | O aplicativo deve permitir visualizar sua aposta.                             | OBS13 |
| RF14  | O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas". | OBS14 |
| RF15  | O aplicativo deve possibilitar logout do usuário.                             | OBS15 |
| RF16  | O aplicativo deve permitir o cancelamento de apostas antes do sorteio.        | OBS16 |

*<p style="text-align: center;">Fonte: <a href="https://github.com/luannvi">Luan Vinícius.</a></p>*

### Requisitos não-funcionais

*<p style="text-align: center;">Tabela 3: Requisitos não-funcionais.</p>*

| Tipo  | Requisitos                                                                 |   ID   |
|:-----:|---------------------------------------------------------------------------|:------:|
| RNF01 | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 3 toques para ir de uma seção a outra. | OBS17 |
| RNF02 | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão. | OBS18 |
| RNF03 | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão. | OBS19 |
| RNF04 | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste. | OBS20 |
| RNF05 | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta. | OBS21 |
| RNF06 | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis. | OBS22 |
| RNF07 | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho. | OBS23 |
| RNF08 | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta. | OBS24 |
| RNF09 | O sistema deve garantir que o acesso a funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex: "Menu") para facilitar a descoberta por parte do usuário. | OBS25 |

*<p style="text-align: center;">Fonte: <a href="https://github.com/luannvi">Luan Vinícius.</a></p>*

## Referências

> UNIVERSIDADE DE BRASÍLIA. *Elicitação de Requisitos*. Brasília: UnB, 2022. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210603/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf>. Acesso em: 29 set. 2025.

## Bibliografia

> UNIVERSIDADE FEDERAL DE SANTA CATARINA. *Técnicas de Elicitação de Requisitos – Observação Direta*. Retraining, Florianópolis, 2023. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-observacao-direta>. Acesso em: 29 set. 2025.


## Versionamento

| Versão | Data       | Autor               | Descrição                       | Revisor |
|:--------:|:------------:|:---------------:|:-------------------------------:|:---------:|
| ``1.0``    | 24/09/2025 | [Luan Vinícius](https://github.com/luannvi)  | Abertura da documentação | [Miquéias Ezequiel](https://github.com/Kael-web7) |
| ``1.1``    | 29/09/2025 | [Luan Vinícius](https://github.com/luannvi)  | Adição de conteúdo       | [Miquéias Ezequiel](https://github.com/Kael-web7) |
