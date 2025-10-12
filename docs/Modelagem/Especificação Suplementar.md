# Especificação Suplementar

## 1. Introdução

Este documento apresenta a **Especificação Suplementar** do sistema **Loterias Caixa** seguindo o modelo FURPS+, abordando requisitos não funcionais organizados nas categorias: **Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Design, Implementação** e **Sistema de Ajuda**. O objetivo é garantir que todos os aspectos de qualidade do sistema sejam especificados de forma clara e mensurável.

## 2. Metodologia

A especificação foi elaborada utilizando o **modelo FURPS+** adaptado, que categoriza requisitos não funcionais em grupos padronizados, permitindo uma cobertura completa das características de qualidade do sistema. Cada categoria foi detalhada com requisitos específicos, mensuráveis e verificáveis.

## 3. Modelo Usado

### Tabela 1 - Categorias do Modelo FURPS+

| Categoria | Descrição |
|-----------|-----------|
| **Design** | Restrições de design e padrões de interface |
| **Implementação** | Linguagens, ferramentas e restrições de construção |
| **Funcionalidade** | Características funcionais e capacidades do sistema |
| **Usabilidade** | Facilidade de uso, aprendizado e acessibilidade |
| **Confiabilidade** | Disponibilidade, tolerância a falhas e recuperação |
| **Desempenho** | Tempo de resposta, throughput e eficiência |
| **Suportabilidade** | Adaptabilidade, manutenibilidade e internacionalização |
| **Sistema de Ajuda** | Documentação online e suporte ao usuário |

## 4. Tabela de Contribuição

### Tabela 2 - Contribuição na Especificação Suplementar

| Aluno | Seções Desenvolvidas |
|-------|---------------------|
| [Rivadalvio Joaquim](https://github.com/RivaFilho) | Especificação suplementar inicial e implementação |
| [João Pedro](https://github.com/Jadequilin) | Organização especificação inicial e funcionalidade | 

## 5. Especificação de Requisitos Não Funcionais

### 5.1 Design

*Seção a ser desenvolvida com requisitos específicos de design e interface*

### 5.2 Implementação

| ID | Descrição | Rastreabilidade |
|:---:|-----------|:---------------|
| **RNF13** | O frontend deve ser desenvolvido em React Native para iOS e Android | **AD17** |
| **RNF14** | O backend deve utilizar Java Spring Boot para serviços empresariais | **AD18** |
| **RNF15** | O banco de dados deve ser Oracle 19c para transações críticas | **AD19** |
| **RNF16** | Implementar arquitetura de microsserviços para escalabilidade e manutenção | **AD20** |
| **RNF17** | Seguir Clean Architecture e Domain-Driven Design | **AD21** |
| **RNF18** | Todas as APIs devem seguir OpenAPI 3.0 para documentação automática | **AD22** |
| **RNF19** | Cobertura de testes mínima de 80% do código | **AD23** |

### 5.3 Funcionalidade

| ID | Descrição | Rastreabilidade |
|:---:|-----------|:---------------|
| **RF29** | Permitir múltiplas modalidades de apostas (Mega-Sena, Quina, Lotofácil, Lotomania, Timemania, Dupla Sena) | **OBS26** |
| **RF30** | Implementar apostas esportivas (futebol, basquete, tênis) | **OBS27** |
| **RF31** | Oferecer apostas pré-marcadas e personalizadas | **OBS28** |
| **RF32** | Prover histórico completo de apostas com filtros por data e modalidade | **OBS29** |
| **RF33** | Permitir recarga de conta via PIX, cartão de crédito e boleto bancário | **OBS30** |
| **RF34** | Implementar saques com verificação de identidade (KYC) | **OBS31** |
| **RF35** | Oferecer notificações em tempo real sobre resultados e sorteios | **OBS32** |

### 5.4 Usabilidade

*Seção a ser desenvolvida com requisitos específicos de usabilidade*

### 5.5 Confiabilidade

*Seção a ser desenvolvida com requisitos específicos de confiabilidade*

### 5.6 Desempenho

*Seção a ser desenvolvida com requisitos específicos de desempenho*

### 5.7 Suportabilidade

*Seção a ser desenvolvida com requisitos específicos de suportabilidade*

### 5.8 Sistema de Ajuda e Documentação Online

*Seção a ser desenvolvida com requisitos específicos de sistema de ajuda*

## 6. Referências Bibliográficas

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

## 7. Bibliografia

> SERRANO, Milene; SERRANO, Maurício. **Requisitos - Aula 10**. Disponível em: <https://aprender3.unb.br/pluginfile.php/3210627/mod_resource/content/1/Aula%2010.pdf>. Acesso em: 11/10/2025.

## 8. Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|--------|-----------|---------|
| `1.0` | 11/10/2025 | [Rivadalvio Joaquim](https://github.com/RivaFilho) | Criação inicial da especificação suplementar | [João Pedro](https://github.com/Jadequilin) |
| `1.1` | 12/10/2025 | [João Pedro](https://github.com/Jadequilin) | Adaptação para modelo FURPS+ completo | [Rivadalvio Joaquim](https://github.com/RivaFilho) |