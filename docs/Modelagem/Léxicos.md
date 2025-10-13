## Introdução

Este documento apresenta a especificação dos léxicos do sistema Loterias Caixa utilizando a técnica **LAL (Léxico Ampliado da Linguagem)**. Os léxicos têm como objetivo definir de forma precisa e não ambígua os termos e conceitos do domínio do aplicativo, garantindo um vocabulário comum entre desenvolvedores, stakeholders e usuários finais, seguindo a metodologia apresentada no material da disciplina.

## Metodologia

Foi utilizada a técnica **LAL (Léxico Ampliado da Linguagem)** conforme apresentado por Serrano e Serrano (2010) para especificação dos símbolos do domínio. Cada léxico é composto pelos seguintes elementos:

- **Símbolo**: Nome do termo/conceito do domínio
- **Tipo**: Classificação em Verbo, Objeto ou Estado
- **Noção**: Definição denotativa do termo
- **Impacto**: Descrição conotativa dos efeitos no sistema

## Modelo Usado

### Tabela 1 - Modelo de Léxico LAL

| Item | Descrição |
|------|-----------|
| **Símbolo** | Nome do termo ou conceito do domínio |
| **Tipo** | Classificação: Verbo (ação), Objeto (entidade) ou Estado (condição) |
| **Noção** | Definição e significado do termo no contexto do sistema |
| **Impacto** | Efeitos, comportamentos e consequências do termo no sistema |

## Tabela de Contribuição

### Tabela 2 - Contribuição nos Léxicos

| Aluno | Léxicos Criados |
|-------|-----------------|
| [João Pedro](https://github.com/Jadequilin) | L01 (Não implementado obrigatório), L02 (Não implementado obrigatório), L05, L06, L07, L08, L09, L10, L11, L12, L13, L14, L15, L16 e L17 |
| [Rivadalvio Joaquim](https://github.com/RivaFilho) |L03 (Não implementado obrigatório), L04 (Não implementado obrigatório),L18, L19, L20, L21, L22, L23, L24, L25, L26, L27, L28, L29 e L30 |

### Validação com o Usuário (Léxicos)

<iframe width="560" height="315" src="https://www.youtube.com/embed/RBeWhwtlLVQ?si=yuVlgNB7Ay2UXfx7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

| Participante | Função | Data | Horário | Local | 
| ------------ | ----- | ----- | ------ | -------|
| [João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Integrantes do grupo, responsáveis por coordenar a validação com o usuário. | 12/10/2025 | 11:20 | Presencial, residência
| José da Silva | 59 anos, funcionário público e usuário do app Loterias Caixa, responsável por validar os cenários desenvolvidos para o artefato. | 12/10/2025 | 11:20 | Presencial, residência |

## Léxicos

### L01 – Aviso de Limite Diário

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 3: Controle de Limite Diário de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aviso de Limite Diário |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que monitora e alerta o usuário quando ele se aproxima ou atinge o valor máximo de apostas permitido para um período de 24 horas |
| **Impacto** | - Sistema emite notificação visual e sonora<br>- Exibe pop-up informativo com opções de continuar ou parar<br>- Bloqueia novas apostas se o limite for atingido<br>- Registra o evento no histórico de controle financeiro |
| **Rastreabilidade** | RF16, ENT25 |

### L02 – Tela Personalizável

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 4: Personalização da Tela Inicial</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Tela Personalizável |
| **Tipo** | Objeto |
| **Noção** | Interface inicial do aplicativo que permite ao usuário reorganizar ícones e atalhos conforme suas preferências e padrões de uso frequente |
| **Impacto** | - Aprende automaticamente as funcionalidades mais acessadas<br>- Permite personalização manual através de arrastar e soltar<br>- Salva configurações localmente no dispositivo<br>- Adapta a interface dinamicamente ao comportamento do usuário |
| **Rastreabilidade** | RF15, ENT23 |

### L03 – Termo de Responsabilidade

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 5: Termo de Esclarecimento sobre Riscos</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Termo de Responsabilidade |
| **Tipo** | Estado |
| **Noção** | Documento obrigatório que explica de forma clara e acessível os riscos envolvidos nas apostas, incluindo probabilidades reais e orientações sobre jogo consciente |
| **Impacto** | - Exibido antes da confirmação de qualquer aposta<br>- Apresenta informações em linguagem simples e compreensível<br>- Exige confirmação explícita do usuário através de checkbox<br>- Armazena aceitação no sistema para fins de auditoria |
| **Rastreabilidade** | RNF06, ENT20 |

### L04 – Modo de Acessibilidade

Autor:[Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 6: Modo Acessibilidade</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Modo de Acessibilidade |
| **Tipo** | Estado |
| **Noção** | Configuração especial da interface que amplia elementos visuais, aumenta contraste e simplifica a navegação para usuários idosos ou com deficiência visual |
| **Impacto** | - Aumenta significativamente o tamanho de fontes e botões<br>- Ativa esquema de cores de alto contraste<br>- Simplifica a estrutura de menus e navegação<br>- Oferece suporte a leitores de tela e navegação por voz |
| **Rastreabilidade** | RF12, ENT15 |

### L05 – Interface Simplificada

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 7: Interface com Telas Simples</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Interface Simplificada |
| **Tipo** | Estado |
| **Noção** | Design de interface com poucos textos e elementos visuais, focando na simplicidade e facilidade de uso |
| **Impacto** | - Reduz complexidade visual para usuários<br>- Facilita navegação intuitiva<br>- Diminui tempo de aprendizado<br>- Melhora experiência do usuário |
| **Rastreabilidade** | RNF01, RF04, ENT01, ENT05 |

### L06 – Comprovante de Aposta

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 8: Comprovante Digital de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Comprovante de Aposta |
| **Tipo** | Objeto |
| **Noção** | Documento digital que comprova a realização de uma aposta, contendo números selecionados, valor e identificação única |
| **Impacto** | - Gera registro oficial da transação<br>- Permite verificação posterior<br>- Serve como comprovante para resgate<br>- Armazena em "Minhas Apostas" |
| **Rastreabilidade** | RF01, RF25, ENT02, OBS14 |

### L07 – Multi-modalidade de Apostas

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 9: Múltiplas Opções de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Multi-modalidade de Apostas |
| **Tipo** | Estado |
| **Noção** | Capacidade do sistema de oferecer diferentes tipos de loterias (Mega-Sena, Lotofácil, Quina, etc.) e apostas esportivas |
| **Impacto** | - Expande opções para o usuário<br>- Permite diversificação de apostas<br>- Atende diferentes preferências<br>- Aumenta engajamento do usuário |
| **Rastreabilidade** | RF02, RF15, ENT03, OBS04 |

### L08 – Acompanhamento de Jogos

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 10: Acompanhamento de Jogos e Resultados</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Acompanhamento de Jogos |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário acompanhar eventos esportivos e resultados de loterias em tempo real através do aplicativo |
| **Impacto** | - Fornece informações atualizadas<br>- Mantém usuário engajado<br>- Permite verificação de resultados<br>- Oferece notificações em tempo real |
| **Rastreabilidade** | RF03, RF06, ENT04, OBS05 |

### L09 – Modo Claro/Escuro

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 11: Alternância entre Modo Claro e Escuro</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Modo Claro/Escuro |
| **Tipo** | Estado |
| **Noção** | Configuração de interface que permite alternar entre temas claro e escuro para melhor conforto visual em diferentes condições de iluminação |
| **Impacto** | - Melhora experiência visual<br>- Reduz fadiga ocular<br>- Adapta-se ao ambiente do usuário<br>- Oferece personalização |
| **Rastreabilidade** | RF06, ENT07 |

### L10 – Imagem Explicativa

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 12: Imagens para Explicação de Funcionalidades</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Imagem Explicativa |
| **Tipo** | Objeto |
| **Noção** | Elemento visual que auxilia na compreensão de funcionalidades através de ilustrações, screenshots ou ícones descritivos |
| **Impacto** | - Facilita aprendizado de funcionalidades<br>- Reduz necessidade de textos longos<br>- Melhora usabilidade para todos os públicos<br>- Auxilia usuários com dificuldade de leitura |
| **Rastreabilidade** | RNF02, ENT08 |

### L11 – Consulta de Ganhos

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 13: Consulta de Ganhos e Resultados</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Consulta de Ganhos |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário verificar valores ganhos em apostas, histórico de prêmios e saldo disponível |
| **Impacto** | - Fornece transparência financeira<br>- Permite controle de ganhos<br>- Facilita planejamento de resgates<br>- Mantém usuário informado |
| **Rastreabilidade** | RF05, ENT06 |

### L12 – Autenticação Segura

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 14: Sistema de Autenticação Segura</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Autenticação Segura |
| **Tipo** | Verbo |
| **Noção** | Processo de verificação de identidade do usuário através de CPF, senha ou biometria para acesso às funcionalidades do aplicativo |
| **Impacto** | - Garante segurança da conta<br>- Previne acesso não autorizado<br>- Protege dados pessoais<br>- Cumpre requisitos legais |
| **Rastreabilidade** | RF08, RF09, RF14, ENT10, ENT11, ENT18, OBS03, RNF05 |

### L13 – Perfil do Usuário

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 15: Perfil Personalizado do Usuário</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Perfil do Usuário |
| **Tipo** | Objeto |
| **Noção** | Área personalizada do aplicativo que contém dados do usuário, histórico de apostas, configurações e preferências |
| **Impacto** | - Centraliza informações do usuário<br>- Permite personalização<br>- Facilita gestão de conta<br>- Oferece acesso rápido a dados |
| **Rastreabilidade** | RF10, ENT12 |

### L14 – Logout Seguro

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 16: Logout Seguro do Sistema</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Logout Seguro |
| **Tipo** | Verbo |
| **Noção** | Processo de encerramento seguro da sessão do usuário no aplicativo, garantindo que os dados permaneçam protegidos |
| **Impacto** | - Protege conta em dispositivos compartilhados<br>- Encerra sessão ativa<br>- Limpa cache sensível<br>- Previne acesso indevido |
| **Rastreabilidade** | RF11, RF26, ENT13, OBS15 |

### L15 – Cadastro com Dados Pessoais

Autor: [João Pedro](https://github.com/Jadequilin)

*<p style="text-align: center;">Tabela 17: Cadastro com Dados Pessoais</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Cadastro com Dados Pessoais |
| **Tipo** | Verbo |
| **Noção** | Processo de registro inicial do usuário no aplicativo utilizando informações pessoais como CPF, nome completo e data de nascimento |
| **Impacto** | - Cria conta única do usuário<br>- Verifica maioridade (18+ anos)<br>- Associa apostas ao CPF<br>- Permite personalização |
| **Rastreabilidade** | RF12, OBS01, AD05, RNF01, AD08 |

### L16 – Volante Digital

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 18: Volante Digital para Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Volante Digital |
| **Tipo** | Objeto |
| **Noção** | Interface interativa que simula o volante físico de apostas, permitindo seleção de números para as diferentes modalidades de loteria |
| **Impacto** | - Facilita seleção de números<br>- Oferece experiência familiar<br>- Permite limpar e sortear números<br>- Mostra números selecionados claramente |
| **Rastreabilidade** | RF17, RF18, RF19, OBS06, OBS07, OBS08, RNF06 |

### L17 – Carrinho de Apostas

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 19: Carrinho para Gestão de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Carrinho de Apostas |
| **Tipo** | Objeto |
| **Noção** | Área temporária que armazena apostas selecionadas pelo usuário antes da confirmação e pagamento |
| **Impacto** | - Permite revisão antes do pagamento<br>- Calcula valor total automaticamente<br>- Oferece opção de remover itens<br>- Facilita gestão múltiplas apostas |
| **Rastreabilidade** | RF20, RF21, OBS09, OBS10, RNF09 |

### L18 – Pagamento Integrado

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 20: Sistema de Pagamento Integrado</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Pagamento Integrado |
| **Tipo** | Verbo |
| **Noção** | Sistema de processamento de pagamentos que aceita múltiplas formas, incluindo cartão de crédito/débito e PIX |
| **Impacto** | - Oferece flexibilidade de pagamento<br>- Processa transações seguras<br>- Confirma pagamento instantaneamente<br>- Integra com sistemas bancários |
| **Rastreabilidade** | RF22, RF23, OBS11, OBS12, AD04 |

### L19 – Cancelamento de Aposta

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 21: Cancelamento de Apostas</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Cancelamento de Aposta |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que permite ao usuário cancelar apostas realizadas antes do sorteio ocorrer |
| **Impacto** | - Oferece flexibilidade ao usuário<br>- Permite correção de erros<br>- Devolve valor apostado<br>- Registra cancelamento no histórico |
| **Rastreabilidade** | RF27, OBS16 |

### L20 – Navegação Intuitiva

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 22: Navegação Intuitiva</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Navegação Intuitiva |
| **Tipo** | Estado |
| **Noção** | Característica do sistema que permite navegação fluida entre telas com número mínimo de toques/interações |
| **Impacto** | - Reduz esforço do usuário<br>- Acelera realização de tarefas<br>- Melhora experiência geral<br>- Facilita aprendizado |
| **Rastreabilidade** | RNF03, OBS16, ENT16, ENT24 |

### L21 – Desempenho de Carregamento

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 23: Desempenho de Carregamento</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Desempenho de Carregamento |
| **Tipo** | Estado |
| **Noção** | Capacidade do sistema de carregar e exibir informações rapidamente, mesmo em condições de rede limitadas |
| **Impacto** | - Melhora experiência do usuário<br>- Reduz tempo de espera<br>- Mantém engajamento<br>- Funciona em diferentes condições de rede |
| **Rastreabilidade** | RNF04, OBS17, AD15, AD16 |

### L22 – Confiabilidade do Sistema

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 24: Confiabilidade do Sistema</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Confiabilidade do Sistema |
| **Tipo** | Estado |
| **Noção** | Característica do sistema de operar sem falhas ou encerramentos inesperados durante o uso normal |
| **Impacto** | - Garante continuidade das operações<br>- Previne perda de dados<br>- Mantém confiança do usuário<br>- Oferece experiência estável |
| **Rastreabilidade** | RNF07, RNF08, OBS20, OBS21 |

### L23 – Expiração de Sessão

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 25: Expiração de Sessão</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Expiração de Sessão |
| **Tipo** | Verbo |
| **Noção** | Mecanismo de segurança que encerra automaticamente a sessão do usuário após período de inatividade |
| **Impacto** | - Protege conta contra acesso não autorizado<br>- Cumpre requisitos de segurança<br>- Notifica usuário antes do encerramento<br>- Oferece renovação de sessão |
| **Rastreabilidade** | RNF10, OBS23 |

### L24 – Interface Autoexplicativa

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 26: Interface Autoexplicativa</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Interface Autoexplicativa |
| **Tipo** | Estado |
| **Noção** | Design de interface onde elementos visuais são acompanhados por textos explicativos para facilitar compreensão |
| **Impacto** | - Reduz necessidade de ajuda externa<br>- Facilita uso para todos os públicos<br>- Melhora acessibilidade<br>- Acelera aprendizado |
| **Rastreabilidade** | RNF11, OBS24 |

### L25 – Multiplataforma

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 27: Disponibilidade Multiplataforma</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Multiplataforma |
| **Tipo** | Estado |
| **Noção** | Capacidade do aplicativo de estar disponível e funcionar em diferentes sistemas operacionais e lojas oficiais |
| **Impacto** | - Amplia acesso aos usuários<br>- Oferece consistência entre plataformas<br>- Facilita download e instalação<br>- Mantém atualizações sincronizadas |
| **Rastreabilidade** | RF01, AD01 |

### L26 – Integração com Sistemas Existentes

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 28: Integração com Sistemas Existentes</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Integração com Sistemas Existentes |
| **Tipo** | Estado |
| **Noção** | Capacidade do aplicativo de se conectar e utilizar infraestrutura e dados dos sistemas já existentes da Caixa |
| **Impacto** | - Garante consistência de dados<br>- Oferece experiência unificada<br>- Utiliza infraestrutura confiável<br>- Facilita manutenção |
| **Rastreabilidade** | RF02, AD02 |

### L27 – Funcionalidade Completa

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 29: Funcionalidade Completa</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Funcionalidade Completa |
| **Tipo** | Estado |
| **Noção** | Característica do aplicativo de oferecer todas as funcionalidades disponíveis nos canais físicos e no site |
| **Impacto** | - Elimina necessidade de deslocamento<br>- Oferece conveniência total<br>- Mantém consistência de serviço<br>- Atende todas as necessidades do usuário |
| **Rastreabilidade** | RF03, AD03 |

### L28 – Transparência Social

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 30: Transparência Social</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Transparência Social |
| **Tipo** | Objeto |
| **Noção** | Seção do aplicativo que mostra informações sobre repasses sociais e contribuições da loteria para desenvolvimento social |
| **Impacto** | - Oferece transparência sobre uso dos recursos<br>- Mostra impacto social das apostas<br>- Fortalece confiança do usuário<br>- Cumpre função educativa |
| **Rastreabilidade** | RF07, AD07 |

### L29 – Aposta Rápida

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 31: Aposta Rápida</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aposta Rápida |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que cria automaticamente uma aposta com base nas preferências e histórico do usuário |
| **Impacto** | - Acelera processo de aposta<br>- Personaliza experiência<br>- Oferece conveniência<br>- Mantém padrões de preferência |
| **Rastreabilidade** | RNF02, AD09 |

### L30 – Sistema de Resgate

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 32: Sistema de Resgate</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Sistema de Resgate |
| **Tipo** | Verbo |
| **Noção** | Conjunto de regras e processos para resgate de prêmios através dos canais oficiais da Caixa |
| **Impacto** | - Define procedimentos de resgate<br>- Garante segurança das transações<br>- Oferece múltiplos canais<br>- Cumpre regulamentações |
| **Rastreabilidade** | RNF03, AD10 |

## Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|--------|-----------|---------|
| ``1.0`` | 12/10/2025 |[João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação dos 4 léxicos iniciais usando LAL | [Luan Vinícius](https://github.com/luannvi)  |
| ``1.1`` | 12/10/2025 |[João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Expansão para 30 léxicos cobrindo todos os requisitos principais | [Luan Vinícius](https://github.com/luannvi)  |
| `1.2` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Vídeos da validação implementados | [Rivadalvio Joaquim](https://github.com/RivaFilho) |