## Introdução

Este documento apresenta a especificação dos léxicos do sistema Loterias Caixa utilizando a técnica **LAL (Léxico Ampliado da Linguagem)**. Os léxicos têm como objetivo definir de forma precisa e não ambígua os termos e conceitos do domínio do aplicativo, garantindo um vocabulário comum entre desenvolvedores, stakeholders e usuários finais, seguindo a metodologia apresentada no material da disciplina.

## Metodologia

O léxico funciona como uma notação que lista e define os símbolos (palavras ou expressões) usados em uma linguagem. Em Engenharia de Requisitos, seu papel central é identificar termos ou frases próprios do contexto social em que o sistema será aplicado <a id="anchor_1" href="#REF1">[1]</a> . Cada símbolo do léxico é caracterizado por:

* **Noção**: o seu significado literal, aquilo que ele denota <a id="anchor_2" href="#REF2">[2]</a>.
* **Impacto**: a sua conotação ou efeito prático, ou seja, a resposta gerada quando o símbolo é utilizado <a id="anchor_2" href="#REF2">[2]</a>.

Para elaborar os léxicos do Loterias Caixa, adotamos a abordagem do **Léxico Ampliado da Linguagem (LAL)**, conforme proposta por Sayão e Carvalho. Nesse modelo, cada símbolo é classificado em uma das quatro categorias:

* **Sujeito**: identifica quem é o agente ou entidade responsável pela ação, enquanto o impacto descreve quais operações esse agente executa sobre o sistema ou ambiente.
* **Verbo**: detalha quem realiza determinada ação, em que momento ela ocorre e quais procedimentos a compõem; o impacto mapeia os efeitos dessa ação no contexto e os novos estados que podem emergir.
* **Objeto**: define o elemento ou recurso do sistema e suas associações com outros objetos; o impacto especifica que tipos de operações podem ser aplicadas a esse objeto.
* **Estado**: descreve a condição ou situação atual do sistema, indicando quais eventos o levaram a tal ponto, e o impacto projeta os estados seguintes possíveis a partir dessa condição.

Cada léxico é estruturado com os seguintes campos:

- **Símbolo**: Nome do termo/conceito do domínio
- **Tipo**: Classificação em Verbo, Objeto ou Estado
- **Noção**: Definição denotativa do termo
- **Impacto**: Descrição conotativa dos efeitos no sistema
- **Sinônimos**: Palavras ou expressões alternativas com significado similar

## Modelo Usado

### Tabela 1 - Modelo de Léxico LAL

| Item | Descrição |
|------|-----------|
| **Símbolo** | Nome do termo ou conceito do domínio |
| **Tipo** | Classificação: Verbo (ação), Objeto (entidade) ou Estado (condição) |
| **Noção** | Definição e significado do termo no contexto do sistema |
| **Impacto** | Efeitos, comportamentos e consequências do termo no sistema |
| **Sinônimos** | Palavras ou expressões alternativas com significado similar |

Autor: [João Pedro](https://github.com/Jadequilin) 

## Tabela de Contribuição

### Tabela 2 - Contribuição nos Léxicos

| Aluno | Léxicos Criados |
|-------|-----------------|
| [João Pedro](https://github.com/Jadequilin) | L01, L02, L05, L06, L07, L08, L09, L10, L11, L12, L13, L14, L15, L16 e L17 |
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | L03, L04, L18, L19, L20, L21, L22, L23, L24, L25, L26, L27, L28, L29, L30 e L31 |

### Validação com o Usuário (Léxicos)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

## Léxicos

### L01 – Aviso de Limite Diário

Autor: [João Pedro](https://github.com/Jadequilin) 

<a id = "L01"></a>

*<p style="text-align: center;">Tabela 3: Controle de Limite Diário de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aviso de Limite Diário |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que monitora e alerta o usuário quando ele se aproxima ou atinge o valor máximo de apostas permitido para um período de 24 horas |
| **Impacto** | - Sistema emite notificação visual e sonora<br>- Exibe pop-up informativo com opções de continuar ou parar<br>- Bloqueia novas apostas se o limite for atingido<br>- Registra o evento no histórico de controle financeiro |
| **Sinônimos** | Alerta de limite diário; Notificação de limite de apostas; Controle de despesa diária; Aviso de limite de apostas |
| **Rastreabilidade** | [RF37](../../Pós-rastreabilidade/Backward%20from.md#rf37) |



### L02 – Aba de Favoritos

Autor: [João Pedro](https://github.com/Jadequilin) 

<a id = "L02" ></a>

*<p style="text-align: center;">Tabela 4: Aba de Favoritos para Apostas Rápidas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aba de Favoritos |
| **Tipo** | Objeto |
| **Noção** | Seção do aplicativo que permite ao usuário salvar e acessar rapidamente suas apostas preferidas, favoritos e jogos frequentes conforme suas preferências |
| **Impacto** | - Facilita acesso às apostas mais usadas<br>- Reduz tempo de seleção de números<br>- Permite salvar combinações personalizadas<br>- Melhora experiência do usuário com atalhos diretos |
| **Sinônimos** | Apostas salvas; Jogos favoritos; Atalhos de aposta; Jogos preferidos |
| **Rastreabilidade** | [RF38](../../Pós-rastreabilidade/Backward%20from.md#rf38) |



### L03 – Termo de Responsabilidade

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L03" ></a>

*<p style="text-align: center;">Tabela 5: Termo de Esclarecimento sobre Riscos</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Termo de Responsabilidade |
| **Tipo** | Estado |
| **Noção** | Documento obrigatório que explica de forma clara e acessível os riscos envolvidos nas apostas, incluindo probabilidades reais e orientações sobre jogo consciente |
| **Impacto** | - Exibido antes da confirmação de qualquer aposta<br>- Apresenta informações em linguagem simples e compreensível<br>- Exige confirmação explícita do usuário através de checkbox<br>- Armazena aceitação no sistema para fins de auditoria |
| **Sinônimos** | Termo de risco; Aviso de responsabilidade; Termo de esclarecimento; Documento de consentimento |
| **Rastreabilidade** | [RNF26](../../Pós-rastreabilidade/Backward%20from.md#rnf26) |



### L04 – Modo de Acessibilidade

Autor:[Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L04" ></a>

*<p style="text-align: center;">Tabela 6: Modo Acessibilidade</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Modo de Acessibilidade |
| **Tipo** | Estado |
| **Noção** | Configuração especial da interface que amplia elementos visuais, aumenta contraste e simplifica a navegação para usuários idosos ou com deficiência visual |
| **Impacto** | - Aumenta significativamente o tamanho de fontes e botões<br>- Ativa esquema de cores de alto contraste<br>- Simplifica a estrutura de menus e navegação<br>- Oferece suporte a leitores de tela e navegação por voz |
| **Sinônimos** | Modo inclusivo; Modo adaptado; Modo assistivo; Configuração de acessibilidade |
| **Rastreabilidade** | [RF33](../../Pós-rastreabilidade/Backward%20from.md#rf33) |



### L05 – Interface Simplificada

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = L05></a>
*<p style="text-align: center;">Tabela 7: Interface com Telas Simples</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Interface Simplificada |
| **Tipo** | Estado |
| **Noção** | Design de interface com poucos textos e elementos visuais, focando na simplicidade e facilidade de uso |
| **Impacto** | - Reduz complexidade visual para usuários<br>- Facilita navegação intuitiva<br>- Diminui tempo de aprendizado<br>- Melhora experiência do usuário |
| **Sinônimos** | Interface minimalista; Tela simplificada; Interface limpa; Design simples |
| **Rastreabilidade** | [RNF01](../../Pós-rastreabilidade/Backward%20from.md#rnf01), [RF04](../../Pós-rastreabilidade/Backward%20from.md#rf04) |



### L06 – Comprovante de Aposta

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L06" ></a>

*<p style="text-align: center;">Tabela 8: Comprovante Digital de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Comprovante de Aposta |
| **Tipo** | Objeto |
| **Noção** | Documento digital que comprova a realização de uma aposta, contendo números selecionados, valor e identificação única |
| **Impacto** | - Gera registro oficial da transação<br>- Permite verificação posterior<br>- Serve como comprovante para resgate<br>- Armazena em "Minhas Apostas" |
| **Sinônimos** | Comprovante digital; Recibo de aposta; Boleto de aposta; Confirmação de aposta |
| **Rastreabilidade** | [RF01](../../Pós-rastreabilidade/Backward%20from.md#rf01), [RF26](../../Pós-rastreabilidade/Backward%20from.md#rf26) |



### L07 – Multi-modalidade de Apostas

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L07" ></a>

*<p style="text-align: center;">Tabela 9: Múltiplas Opções de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Multi-modalidade de Apostas |
| **Tipo** | Estado |
| **Noção** | Capacidade do sistema de oferecer diferentes tipos de loterias (Mega-Sena, Lotofácil, Quina, etc.) e apostas esportivas |
| **Impacto** | - Expande opções para o usuário<br>- Permite diversificação de apostas<br>- Atende diferentes preferências<br>- Aumenta engajamento do usuário |
| **Sinônimos** | Variedade de apostas; Múltiplas opções; Diversidade de jogos; Variedade de modalidades |
| **Rastreabilidade** | [RF02](../../Pós-rastreabilidade/Backward%20from.md#rf02) |



### L08 – Acompanhamento de Jogos

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L08" ></a>

*<p style="text-align: center;">Tabela 10: Acompanhamento de Jogos e Resultados</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Acompanhamento de Jogos |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário acompanhar eventos esportivos e resultados de loterias em tempo real através do aplicativo |
| **Impacto** | - Fornece informações atualizadas<br>- Mantém usuário engajado<br>- Permite verificação de resultados<br>- Oferece notificações em tempo real |
| **Sinônimos** | Acompanhamento de resultados; Monitoramento de jogos; Rastreamento de apostas; Acompanhamento de sorteios |
| **Rastreabilidade** | [RF03](../../Pós-rastreabilidade/Backward%20from.md#rf03), [RF07](../../Pós-rastreabilidade/Backward%20from.md#rf07) |



### L09 – Modo Claro/Escuro

<a id = "L09"></a>
Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 11: Alternância entre Modo Claro e Escuro</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Modo Claro/Escuro |
| **Tipo** | Estado |
| **Noção** | Configuração de interface que permite alternar entre temas claro e escuro para melhor conforto visual em diferentes condições de iluminação |
| **Impacto** | - Melhora experiência visual<br>- Reduz fadiga ocular<br>- Adapta-se ao ambiente do usuário<br>- Oferece personalização |
| **Sinônimos** | Tema claro e escuro; Modo noturno; Modo luz; Alternância de tema |
| **Rastreabilidade** | [RF06](../../Pós-rastreabilidade/Backward%20from.md#rf06) |



### L10 – Imagem Explicativa

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L10" ></a>

*<p style="text-align: center;">Tabela 12: Imagens para Explicação de Funcionalidades</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Imagem Explicativa |
| **Tipo** | Objeto |
| **Noção** | Elemento visual que auxilia na compreensão de funcionalidades através de ilustrações, screenshots ou ícones descritivos |
| **Impacto** | - Facilita aprendizado de funcionalidades<br>- Reduz necessidade de textos longos<br>- Melhora usabilidade para todos os públicos<br>- Auxilia usuários com dificuldade de leitura |
| **Sinônimos** | Imagem de ajuda; Imagem tutorial; Screenshot explicativo; Ilustração informativa |
| **Rastreabilidade** | [RNF02](../../Pós-rastreabilidade/Backward%20from.md#rnf02) |



### L11 – Consulta de Ganhos

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L11" ></a>

*<p style="text-align: center;">Tabela 13: Consulta de Ganhos e Resultados</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Consulta de Ganhos |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário verificar valores ganhos em apostas, histórico de prêmios e saldo disponível |
| **Impacto** | - Fornece transparência financeira<br>- Permite controle de ganhos<br>- Facilita planejamento de resgates<br>- Mantém usuário informado |
| **Sinônimos** | Consulta de prêmios; Verificação de ganhos; Histórico de ganhadores; Saldo de prêmios |
| **Rastreabilidade** | [RF05](../../Pós-rastreabilidade/Backward%20from.md#rf05) |



### L12 – Autenticação Segura

<a id = "L12">
Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 14: Sistema de Autenticação Segura</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Autenticação Segura |
| **Tipo** | Verbo |
| **Noção** | Processo de verificação de identidade do usuário através de CPF, senha ou biometria para acesso às funcionalidades do aplicativo |
| **Impacto** | - Garante segurança da conta<br>- Previne acesso não autorizado<br>- Protege dados pessoais<br>- Cumpre requisitos legais |
| **Sinônimos** | Autenticação de usuário; Verificação de identidade; Login seguro; Acesso autenticado |
| **Rastreabilidade** | [RF08](../../Pós-rastreabilidade/Backward%20from.md#rf08), [RF09](../../Pós-rastreabilidade/Backward%20from.md#rf09), [RF14](../../Pós-rastreabilidade/Backward%20from.md#rf14) |



### L13 – Perfil do Usuário

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L13" ></a>

*<p style="text-align: center;">Tabela 15: Perfil Personalizado do Usuário</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Perfil do Usuário |
| **Tipo** | Objeto |
| **Noção** | Área personalizada do aplicativo que contém dados do usuário, histórico de apostas, configurações e preferências |
| **Impacto** | - Centraliza informações do usuário<br>- Permite personalização<br>- Facilita gestão de conta<br>- Oferece acesso rápido a dados |
| **Sinônimos** | Conta do usuário; Perfil pessoal; Painel do usuário; Área pessoal |
| **Rastreabilidade** | [RF10](../../Pós-rastreabilidade/Backward%20from.md#rf10) |

*<p style="text-align: center;">Autoria: Próprio do Grupo</p>*

### L14 – Logout Seguro

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L14" ></a>

*<p style="text-align: center;">Tabela 16: Logout Seguro do Sistema</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Logout Seguro |
| **Tipo** | Verbo |
| **Noção** | Processo de encerramento seguro da sessão do usuário no aplicativo, garantindo que os dados permaneçam protegidos |
| **Impacto** | - Protege conta em dispositivos compartilhados<br>- Encerra sessão ativa<br>- Limpa cache sensível<br>- Previne acesso indevido |
| **Sinônimos** | Sair da conta; Encerrar sessão; Desconectar; Finalizar sessão |
| **Rastreabilidade** | [RF11](../../Pós-rastreabilidade/Backward%20from.md#rf11), [RF27](../../Pós-rastreabilidade/Backward%20from.md#rf27) |


### L15 – Cadastro com Dados Pessoais

Autor: [João Pedro](https://github.com/Jadequilin)
<a id = "L15" ></a>

*<p style="text-align: center;">Tabela 17: Cadastro com Dados Pessoais</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Cadastro com Dados Pessoais |
| **Tipo** | Verbo |
| **Noção** | Processo de registro inicial do usuário no aplicativo utilizando informações pessoais como CPF, nome completo e data de nascimento |
| **Impacto** | - Cria conta única do usuário<br>- Verifica maioridade (18+ anos)<br>- Associa apostas ao CPF<br>- Permite personalização |
| **Sinônimos** | Registro de usuário; Criação de conta; Inscrição; Cadastro inicial |
| **Rastreabilidade** | [RF12](../../Pós-rastreabilidade/Backward%20from.md#rf12) |


### L16 – Volante Digital

Autor: [João Pedro](https://github.com/Jadequilin) 
<a id = "L16" ></a>

*<p style="text-align: center;">Tabela 18: Volante Digital para Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Volante Digital |
| **Tipo** | Objeto |
| **Noção** | Interface interativa que simula o volante físico de apostas, permitindo seleção de números para as diferentes modalidades de loteria |
| **Impacto** | - Facilita seleção de números<br>- Oferece experiência familiar<br>- Permite limpar e sortear números<br>- Mostra números selecionados claramente |
| **Sinônimos** | Cartela digital; Formulário de apostas; Bilhete digital; Boletim de jogo |
| **Rastreabilidade** | [RF13](../../Pós-rastreabilidade/Backward%20from.md#rf13), [RF15](../../Pós-rastreabilidade/Backward%20from.md#rf15), [RF16](../../Pós-rastreabilidade/Backward%20from.md#rf16), [RF17](../../Pós-rastreabilidade/Backward%20from.md#rf17), [RF18](../../Pós-rastreabilidade/Backward%20from.md#rf18), [RF19](../../Pós-rastreabilidade/Backward%20from.md#rf19) |

### L17 – Carrinho de Apostas
<a id = "L17" ></a>

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 19: Carrinho para Gestão de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Carrinho de Apostas |
| **Tipo** | Objeto |
| **Noção** | Área temporária que armazena apostas selecionadas pelo usuário antes da confirmação e pagamento |
| **Impacto** | - Permite revisão antes do pagamento<br>- Calcula valor total automaticamente<br>- Oferece opção de remover itens<br>- Facilita gestão múltiplas apostas |
| **Sinônimos** | Cesta de apostas; Carrinho de compras; Apostas pendentes; Reserva de apostas |
| **Rastreabilidade** | [RF20](../../Pós-rastreabilidade/Backward%20from.md#rf20), [RF21](../../Pós-rastreabilidade/Backward%20from.md#rf21), [RF22](../../Pós-rastreabilidade/Backward%20from.md#rf22), [RF24](../../Pós-rastreabilidade/Backward%20from.md#rf24), [RF25](../../Pós-rastreabilidade/Backward%20from.md#rf25), [RF28](../../Pós-rastreabilidade/Backward%20from.md#rf28) |

### L18 – Pagamento Integrado

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L18" ></a>

*<p style="text-align: center;">Tabela 20: Sistema de Pagamento Integrado</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Pagamento Integrado |
| **Tipo** | Verbo |
| **Noção** | Sistema de processamento de pagamentos que aceita múltiplas formas, incluindo cartão de crédito/débito e PIX |
| **Impacto** | - Oferece flexibilidade de pagamento<br>- Processa transações seguras<br>- Confirma pagamento instantaneamente<br>- Integra com sistemas bancários |
| **Sinônimos** | Processamento de pagamento; Sistema de cobrança; Gateway de pagamento; Transação de pagamento |
| **Rastreabilidade** | [RF29](../../Pós-rastreabilidade/Backward%20from.md#rf29) |

### L19 – Cancelamento de Aposta

<a id= "L19"></a>

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 21: Cancelamento de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Cancelamento de Aposta |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário cancelar apostas realizadas antes do sorteio ocorrer |
| **Impacto** | - Oferece flexibilidade ao usuário<br>- Permite correção de erros<br>- Devolve valor apostado<br>- Registra cancelamento no histórico |
| **Sinônimos** | Revogação de aposta; Anulação de aposta; Exclusão de aposta; Devolução de aposta |
| **Rastreabilidade** | [RF28](../../Pós-rastreabilidade/Backward%20from.md#rf28) |

### L20 – Navegação Intuitiva

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L20" ></a>

*<p style="text-align: center;">Tabela 22: Navegação Intuitiva</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Navegação Intuitiva |
| **Tipo** | Estado |
| **Noção** | Característica do sistema que permite navegação fluida entre telas com número mínimo de toques/interações |
| **Impacto** | - Reduz esforço do usuário<br>- Acelera realização de tarefas<br>- Melhora experiência geral<br>- Facilita aprendizado |
| **Sinônimos** | Navegação fluida; Fluxo natural; Navegação inteligente; Caminho lógico |
| **Rastreabilidade** | [RNF03](../../Pós-rastreabilidade/Backward%20from.md#rnf03) |

### L21 – Desempenho de Carregamento

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L21" ></a>

*<p style="text-align: center;">Tabela 23: Desempenho de Carregamento</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Desempenho de Carregamento |
| **Tipo** | Estado |
| **Noção** | Capacidade do sistema de carregar e exibir informações rapidamente, mesmo em condições de rede limitadas |
| **Impacto** | - Melhora experiência do usuário<br>- Reduz tempo de espera<br>- Mantém engajamento<br>- Funciona em diferentes condições de rede |
| **Sinônimos** | Velocidade de carregamento; Tempo de resposta rápido; Carregamento ágil; Desempenho de velocidade |
| **Rastreabilidade** | [RNF04](../../Pós-rastreabilidade/Backward%20from.md#rnf04) |

### L22 – Confiabilidade do Sistema

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L22" ></a>

*<p style="text-align: center;">Tabela 24: Confiabilidade do Sistema</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Confiabilidade do Sistema |
| **Tipo** | Estado |
| **Noção** | Característica do sistema de operar sem falhas ou encerramentos inesperados durante o uso normal |
| **Impacto** | - Garante continuidade das operações<br>- Previne perda de dados<br>- Mantém confiança do usuário<br>- Oferece experiência estável |
| **Sinônimos** | Estabilidade do sistema; Confiabilidade técnica; Robustez; Segurança operacional |
| **Rastreabilidade** | [RNF05](../../Pós-rastreabilidade/Backward%20from.md#rnf05), [RNF07](../../Pós-rastreabilidade/Backward%20from.md#rnf07) |

### L23 – Expiração de Sessão

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L23" ></a>

*<p style="text-align: center;">Tabela 25: Expiração de Sessão</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Expiração de Sessão |
| **Tipo** | Verbo |
| **Noção** | Mecanismo de segurança que encerra automaticamente a sessão do usuário após período de inatividade |
| **Impacto** | - Protege conta contra acesso não autorizado<br>- Cumpre requisitos de segurança<br>- Notifica usuário antes do encerramento<br>- Oferece renovação de sessão |
| **Sinônimos** | Timeout de sessão; Encerramento automático; Expiração de login; Finalização de sessão inativa |
| **Rastreabilidade** | [RNF10](../../Pós-rastreabilidade/Backward%20from.md#rnf10) |

### L24 – Interface Autoexplicativa

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L24" ></a>

*<p style="text-align: center;">Tabela 26: Interface Autoexplicativa</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Interface Autoexplicativa |
| **Tipo** | Estado |
| **Noção** | Design de interface onde elementos visuais são acompanhados por textos explicativos para facilitar compreensão |
| **Impacto** | - Reduz necessidade de ajuda externa<br>- Facilita uso para todos os públicos<br>- Melhora acessibilidade<br>- Acelera aprendizado |
| **Sinônimos** | Interface clara; Interface com instruções; Interface guiada; Interface didática |
| **Rastreabilidade** | [RNF11](../../Pós-rastreabilidade/Backward%20from.md#rnf11) |

### L25 – Multiplataforma

<a id= "L25"></a>
Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 27: Disponibilidade Multiplataforma</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Multiplataforma |
| **Tipo** | Estado |
| **Noção** | Capacidade do aplicativo de estar disponível e funcionar em diferentes sistemas operacionais e lojas oficiais |
| **Impacto** | - Amplia acesso aos usuários<br>- Oferece consistência entre plataformas<br>- Facilita download e instalação<br>- Mantém atualizações sincronizadas |
| **Sinônimos** | Compatibilidade multiplataforma; Disponibilidade em múltiplos sistemas; Aplicativo cross-platform; Suporte a várias plataformas |
| **Rastreabilidade** | [RNF12](../../Pós-rastreabilidade/Backward%20from.md#rnf12) |

### L26 – Integração com Sistemas Existentes

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L26" ></a>

*<p style="text-align: center;">Tabela 28: Integração com Sistemas Existentes</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Integração com Sistemas Existentes |
| **Tipo** | Estado |
| **Noção** | Capacidade do aplicativo de se conectar e utilizar infraestrutura e dados dos sistemas já existentes da Caixa |
| **Impacto** | - Garante consistência de dados<br>- Oferece experiência unificada<br>- Utiliza infraestrutura confiável<br>- Facilita manutenção |
| **Sinônimos** | Conectividade com sistemas legados; Integração de infraestrutura; Compatibilidade com sistemas; Interoperabilidade |
| **Rastreabilidade** | [RNF13](../../Pós-rastreabilidade/Backward%20from.md#rnf13) |

### L27 – Funcionalidade Completa

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L27" ></a>

*<p style="text-align: center;">Tabela 29: Funcionalidade Completa</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Funcionalidade Completa |
| **Tipo** | Estado |
| **Noção** | Característica do aplicativo de oferecer todas as funcionalidades disponíveis nos canais físicos e no site |
| **Impacto** | - Elimina necessidade de deslocamento<br>- Oferece conveniência total<br>- Mantém consistência de serviço<br>- Atende todas as necessidades do usuário |
| **Sinônimos** | Funcionalidade integral; Todas as features; Operação completa; Disponibilidade integral |
| **Rastreabilidade** | [RNF14](../../Pós-rastreabilidade/Backward%20from.md#rnf14) |

### L28 – Transparência Social

<a id = "L28" ></a>
Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 30: Transparência Social</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Transparência Social |
| **Tipo** | Objeto |
| **Noção** | Seção do aplicativo que mostra informações sobre repasses sociais e contribuições da loteria para desenvolvimento social |
| **Impacto** | - Oferece transparência sobre uso dos recursos<br>- Mostra impacto social das apostas<br>- Fortalece confiança do usuário<br>- Cumpre função educativa |
| **Sinônimos** | Informação social; Responsabilidade social; Impacto comunitário; Dados de repasse social |
| **Rastreabilidade** | [RF31](../../Pós-rastreabilidade/Backward%20from.md#rf31), [RF32](../../Pós-rastreabilidade/Backward%20from.md#rf32) |

### L29 – Aposta Rápida

<a id= "L29"></a>

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 31: Aposta Rápida</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aposta Rápida |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que cria automaticamente uma aposta com base nas preferências e histórico do usuário |
| **Impacto** | - Acelera processo de aposta<br>- Personaliza experiência<br>- Oferece conveniência<br>- Mantém padrões de preferência |
| **Sinônimos** | Aposta automática; Aposta simplificada; Gerador de apostas; Aposta sugerida |
| **Rastreabilidade** | [RNF16](../../Pós-rastreabilidade/Backward%20from.md#rnf16) |

### L30 – Sistema de Resgate

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L30" ></a>

*<p style="text-align: center;">Tabela 32: Sistema de Resgate</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Sistema de Resgate |
| **Tipo** | Verbo |
| **Noção** | Conjunto de regras e processos para resgate de prêmios através dos canais oficiais da Caixa |
| **Impacto** | - Define procedimentos de resgate<br>- Garante segurança das transações<br>- Oferece múltiplos canais<br>- Cumpre regulamentações |
| **Sinônimos** | Processo de resgate; Saque de prêmio; Transferência de ganhos; Operação de resgate |
| **Rastreabilidade** | [RNF17](../../Pós-rastreabilidade/Backward%20from.md#rnf17) |

### L31 – Notificação de Aposta Premiada

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)
<a id = "L31" ></a>

*<p style="text-align: center;">Tabela 33: Notificação de Aposta Premiada</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Notificação de Aposta Premiada |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que notifica automaticamente o usuário quando uma de suas apostas foi contemplada com prêmio |
| **Impacto** | - Informa o usuário sobre ganhos imediatamente<br>- Evita perda de prazos para resgate<br>- Oferece notificações push e por email<br>- Facilita descoberta de ganhos |
| **Sinônimos** | Alerta de aposta ganhadora; Notificação de ganho; Aviso de prêmio; Alertas de premiação |
| **Rastreabilidade** | [RF40](../../Pós-rastreabilidade/Backward%20from.md#rf40) |

## Agradecimentos

O grupo 7 agradece o apoio das ferramentas de inteligência artificial generativa - chatGPT, Google Gemini - na revisão gramatical e estilo de algumas partes do texto. As tecnologias foram utilizadas para organizar e deixar o texto mais claro, além de fornecer exemplos de sinônimos e melhorias na estrutura dos léxicos. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

##  Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SERRANO M., SERRANO M. Requisitos - Aula 10 - p. 13 - Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 11/10/2025

> <a id="REF2" href="#anchor_2">2.</a> SERRANO M., SERRANO M. Requisitos - Aula 10 - p. 14 - Disponível em: https://aprender3.unb.br/pluginfile.php/3096108/mod_resource/content/1/Aula%2010.pdf. Acesso em: 11/10/2025.

> 3.SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: http://www.nilc.icmc.usp.br/til/til2006/0030.pdf. Acesso em: 10/05/2025.

> 4.LÉXICOS. [S. l.], 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos>. Acesso em: 12 out. 2025.

##  Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

## Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|--------|-----------|---------|
| ``1.0`` | 12/10/2025 |[João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação dos 4 léxicos iniciais usando LAL | [Luan Vinícius](https://github.com/luannvi)  |
| ``1.1`` | 12/10/2025 |[João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Expansão para 30 léxicos cobrindo todos os requisitos principais | [Luan Vinícius](https://github.com/luannvi)  |
| `1.2` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Vídeos da validação implementados, adição da referência e bibliografia | [Rivadalvio Joaquim](https://github.com/RivaFilho) |
| ``1.3``    | 21/10/2025 | [João Pedro](https://github.com/Jadequilin)   | Correção dos IDs de referência à requisitos |[Rivadalvio Joaquim](https://github.com/RivaFilho)  |
| ``1.4``    | 18/11/2025 | [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho)   | Adição de autoria das tabelas como próprio do grupo, inclusão de sinônimos em todos os léxicos e seção de agradecimentos à IA | [Luan Vinícius](https://github.com/luannvi) |
| ``1.5``    | 18/11/2025 | [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho)   | Remoção de "Não implementado obrigatório", mudança de L02 para "Aba de Favoritos", correção de requisitos conforme numeração consolidada e adição de L31 | [Luan Vinícius](https://github.com/luannvi) |
| ``1.6``    | 18/11/2025 | [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho)   | Adição de hyperlinks em todos os IDs de requisitos permitindo navegação para Backward from | [Luan Vinícius](https://github.com/luannvi) |
| ``1.7``    | 18/11/2025 | [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho)   | Adição de hyperlinks nas referências | [Luan Vinícius](https://github.com/luannvi) |