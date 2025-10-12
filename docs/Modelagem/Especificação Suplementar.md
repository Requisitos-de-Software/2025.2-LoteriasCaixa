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
| *Sistema de Ajuda* | Documentação online e suporte ao usuário |

##  Tabela de Contribuição

### Tabela 2 - Contribuição na Especificação Suplementar

| Aluno | Seções Desenvolvidas |
|-------|---------------------|
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | Especificação suplementar inicial e implementação |
| [João Pedro](https://github.com/Jadequilin) | Organização especificação inicial e funcionalidade | 
| [Luan Vinícius](https://github.com/luannvi) | Classificação dos requisitos de desempenho |

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

###  Implementação
Autor: Rivadalvio Joaquim 
tabela 4: Requisitos não funcionais relacionados a tecnologias e arquitetura*

| ID | Descrição | Status | Rastreabilidade |
|:---:|-----------|:--------:|:---------------|
| **RNF06** | O aplicativo poderia apresentar uma forma de baixar o comprovante da compra dos jogos cadastrados | Não Implementado | **AD13** |
| **RNF07** | O aplicativo não apresenta uma forma de mostrar os resultado em tempo real | Não Implementado | **AD14** |
| **RF01** | O aplicativo segue a questão de disponibilidade em plataformas que os usuários tem acesso (IOS/Apple Store, Android/Play Store) | Implementado | **AD01** |
| **RF02** | O aplicativo utiliza tanto o sistema da própria empresa para que o usuário consiga acessar os seus dados no sistema | Implementado | **AD02** |
| **RF03** | O aplicativo entrega as facilidades para realizar as mesmas funções que o site ou ir pessoalmente a uma lotérica | Implementado | **AD03** |

### Design
*A ser desenvolvido*

###  Usabilidade
*A ser desenvolvido*

###  Confiabilidade  
*A ser desenvolvido*

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

###  Suportabilidade
*A ser desenvolvido*

### Sistema de ajuda 
*A ser desenvolvido*

##  Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

> ESPECIFICAÇÃO SUPLEMENTAR. [S. l.], 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/>. Acesso em: 12 out. 2025.

##  Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

##  Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|--------|-----------|---------|
| `1.0` | 11/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação inicial da especificação suplementar | [João Pedro](https://github.com/Jadequilin) |
| `1.1` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Adição de 2 requisitos não implementados na implementação | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| `1.2` | 12/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Adição de coluna de status e seleção de requisitos não implementados | [João Pedro](https://github.com/Jadequilin) |
| `1.3` | 12/10/2025 | [Luan Vinícius](https://github.com/luannvi) | Adição da especificação de performance | [Miquéias Ezequiel](https://github.com/Kael-web7) |


