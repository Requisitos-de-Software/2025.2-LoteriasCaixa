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
| [João Pedro](https://github.com/Jadequilin) | L01 e L02 |
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | L03 e L04 |

## Léxicos

### L01 – Aviso de Limite Diário

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 3: Controle de Limite Diário de Apostas .</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Aviso de Limite Diário |
| **Tipo** | Verbo |
| **Noção** | Funcionalidade que monitora e alerta o usuário quando ele se aproxima ou atinge o valor máximo de apostas permitido para um período de 24 horas |
| **Impacto** | - Sistema emite notificação visual e sonora<br>- Exibe pop-up informativo com opções de continuar ou parar<br>- Bloqueia novas apostas se o limite for atingido<br>- Registra o evento no histórico de controle financeiro |

### L02 – Tela Personalizável

Autor: [João Pedro](https://github.com/Jadequilin) 

*<p style="text-align: center;">Tabela 4: Personalização da Tela Inicial (telas mais usadas) .</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Tela Personalizável |
| **Tipo** | Objeto |
| **Noção** | Interface inicial do aplicativo que permite ao usuário reorganizar ícones e atalhos conforme suas preferências e padrões de uso frequente |
| **Impacto** | - Aprende automaticamente as funcionalidades mais acessadas<br>- Permite personalização manual através de arrastar e soltar<br>- Salva configurações localmente no dispositivo<br>- Adapta a interface dinamicamente ao comportamento do usuário |

### L03 – Termo de Responsabilidade

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 5: Termo de Esclarecimento sobre Riscos .</p>*

| Item | Descrição |
|------|-----------|
| **Símbolo** | Termo de Responsabilidade |
| **Tipo** | Estado |
| **Noção** | Documento obrigatório que explica de forma clara e acessível os riscos envolvidos nas apostas, incluindo probabilidades reais e orientações sobre jogo consciente |
| **Impacto** | - Exibido antes da confirmação de qualquer aposta<br>- Apresenta informações em linguagem simples e compreensível<br>- Exige confirmação explícita do usuário através de checkbox<br>- Armazena aceitação no sistema para fins de auditoria |

### L04 – Modo de Acessibilidade

Autor: [Rivadalvio Joaquim](https://github.com/RivaFilho)

*<p style="text-align: center;">Tabela 6: Modo Acessibilidade para Usuários idosos e/ou pessoa com deficiências .</p>*


| Item | Descrição |
|------|-----------|
| **Símbolo** | Modo de Acessibilidade |
| **Tipo** | Estado |
| **Noção** | Configuração especial da interface que amplia elementos visuais, aumenta contraste e simplifica a navegação para usuários idosos ou com deficiência visual |
| **Impacto** | - Aumenta significativamente o tamanho de fontes e botões<br>- Ativa esquema de cores de alto contraste<br>- Simplifica a estrutura de menus e navegação<br>- Oferece suporte a leitores de tela e navegação por voz |

## Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

## Bibliografia

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

## Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|--------|-----------|---------|
| ``1.0`` | 12/10/2025 |[João Pedro](https://github.com/Jadequilin) e [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação dos 4 léxicos iniciais usando LAL | [Luan Vinícius](https://github.com/luannvi)  |