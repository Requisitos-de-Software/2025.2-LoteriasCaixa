# Técnicas de Priorização: Valor, Risco e Custo
a
## Introdução

A priorização de requisitos é uma etapa crucial no desenvolvimento de software, pois permite que a equipe identifique quais funcionalidades devem ser implementadas primeiro, considerando critérios como valor agregado, risco envolvido e custo de desenvolvimento. Diferentes técnicas podem ser utilizadas para essa finalidade, sendo a tecnica utilizada pelo integrante João Pedro uma das mais comuns baseadas em valor, risco e custo.

## Participantes

**Tabela 1: Participantes da Entrevista**

| Nome | Função |
|------|--------|
| [João Pedro Araújo](https://github.com/Jadequilin) | Entrevistador | 
| Janice José Araújo | Usuária |

## Metodologia

A entrevista foi conduzida por João Pedro Araújo no dia 30/09/2025, no horário 11:40 às 12:10, com a usuária Janice José Araújo. Durante a reunião, foram apresentados os conceitos de priorização baseada em valor, risco e custo, e o usuário colaborou na classificação dos requisitos com base nesses critérios, também permitindo a filmagem durante o processo.

## Técnica Utilizada

A técnica aplicada combina três dimensões principais:

- **Valor**: benefício que o requisito agrega ao usuário e ao negócio.
- **Risco**: probabilidade de o requisito não ser atendido ou de causar impactos negativos.
- **Custo**: esforço necessário para implementar o requisito.

Cada requisito foi avaliado em uma escala de 1 a 5 para cada dimensão, e a prioridade final foi calculada com base na fórmula:

**Prioridade = (Valor + Risco) / Custo**

Quanto maior o resultado, maior a prioridade.

## Link do vídeo
Link direto:[Assistir no YouTube](https://youtu.be/rEuk4FJvrqM)
## Requisitos Priorizados

### *Legenda (Tabelas 2,3 e 4)*
- **RF**: Requisito funcional.
- **RNF**: Requisito não-funcional.
- **OBS**: Requisito elicitado pela entrevista.
- **ENT**: Requisito priorizado pela entrevista.

Após a entrevista foi possível elicitar os seguintes requisitos:

### Requisitos de Alta Prioridade (Prioridade ≥ 4.0)

**Tabela 2**

| Tipo | Requisito | Valor | Risco | Custo | Prioridade | ID |
|------|-----------|-------|-------|-------|------------|----|
| RF | O software deve ter telas simples com poucos textos | 5 | 5 | 1 | 10.0 | ENT01 |
| RF | O usuário deve receber o resultado das apostas | 5 | 5 | 1 | 10.0 | ENT09 |
| RNF | Há um termo de uso | 5 | 5 | 1 | 10.0 | ENT19 |
| RNF | O termo de uso especifica os riscos para o usuário | 5 | 5 | 1 | 10.0 | ENT20 |
| RNF | O termo de uso especifica a classificação indicativa para o usuário | 5 | 5 | 1 | 10.0 | ENT21 |
| RNF | O termo de uso especifica o acesso aos dados do aplicativo para o usuário | 5 | 5 | 1 | 10.0 | ENT22 |
| RF | O aplicativo deve exibir os tipos de loteria disponíveis (Mega-Sena, Lotofácil etc.) | 5 | 5 | 1 | 10.0 | OBS RF04 |
| RF | O aplicativo deve permitir gerar o comprovante da aposta em "minhas apostas" | 5 | 5 | 1 | 10.0 | OBS RF14 |
| RNF | O sistema deve proteger o acesso às funcionalidades transacionais exigindo a autenticação do usuário no início da sessão | 5 | 5 | 1 | 10.0 | OBS RNF03 |
| RNF | O aplicativo não deve apresentar erros ou fechar inesperadamente durante o processo de criação e pagamento de uma aposta | 5 | 5 | 1 | 10.0 | OBS RNF05 |
| RF | O software deve ter imagens explicativas | 4 | 4 | 1 | 8.0 | ENT08 |
| RF | O usuário deve receber Comprovantes de seus ganhos e apostas | 5 | 5 | 2 | 5.0 | ENT02 |
| RF | O usuário deve poder acompanhar jogos pelo software | 5 | 5 | 2 | 5.0 | ENT04 |
| RF | O usuário deve poder consultar seus ganhos | 5 | 5 | 2 | 5.0 | ENT06 |
| RF | O usuário deve poder fazer login no aplicativo | 5 | 5 | 2 | 5.0 | ENT10 |
| RF | O usuário deve poder acessar o próprio perfil | 5 | 5 | 2 | 5.0 | ENT12 |
| RF | O usuário deve poder fazer logout no aplicativo | 5 | 5 | 2 | 5.0 | ENT13 |
| RNF | O aplicativo é de fácil acesso ao usuário | 5 | 5 | 2 | 5.0 | ENT14 |
| RNF | O usuário consegue achar com facilidade o que procura no aplicativo | 5 | 5 | 2 | 5.0 | ENT24 |
| RF | O aplicativo deve permitir que o usuário realize o cadastro com dados pessoais | 5 | 5 | 2 | 5.0 | OBS RF01 |
| RF | O aplicativo deve permitir login com CPF e senha ou com biometria | 5 | 5 | 2 | 5.0 | OBS RF03 |
| RF | O aplicativo deve exibir o último resultado do sorteio de cada loteria | 5 | 5 | 2 | 5.0 | OBS RF05 |
| RF | O aplicativo deve possibilitar a escolha de números para fazer uma aposta | 5 | 5 | 2 | 5.0 | OBS RF06 |
| RF | O aplicativo deve permitir visualizar sua aposta | 5 | 5 | 2 | 5.0 | OBS RF13 |
| RF | O usuário deve ter mais de uma opção de aposta | 4 | 5 | 2 | 4.5 | ENT03 |
| RF | As opções de ações dentro do aplicativo estão facilmente disponíveis | 5 | 4 | 2 | 4.5 | ENT16 |
| RNF | O sistema deve fornecer feedback visual imediato quando o usuário adiciona uma aposta ao carrinho | 5 | 4 | 2 | 4.5 | OBS RNF07 |
| RF | O software deve ter poucas telas | 4 | 4 | 2 | 4.0 | ENT05 |
| RF | O aplicativo deve calcular automaticamente o valor da aposta | 4 | 4 | 2 | 4.0 | OBS RF10 |
| RF | O aplicativo deve possibilitar logout do usuário | 4 | 4 | 2 | 4.0 | OBS RF15 |

### Requisitos de Média Prioridade (Prioridade 2.0 - 3.9)

**Tabela 3**

| Tipo | Requisito | Valor | Risco | Custo | Prioridade | ID |
|------|-----------|-------|-------|-------|------------|----|
| RF | Deve haver uma verificação de identidade para login no aplicativo | 5 | 5 | 3 | 3.3 | ENT11 |
| RF | O aplicativo apresenta funções de acessibilidade aos idosos e deficientes | 5 | 5 | 3 | 3.3 | ENT15 |
| RNF | O aplicativos é de uma fonte confiável para o usuário | 5 | 5 | 3 | 3.3 | ENT17 |
| RF | As páginas do aplicativo mais usadas estão em destaque na tela | 5 | 5 | 3 | 3.3 | ENT23 |
| RF | O aplicativo deve permitir completar a aposta com números aleatórios | 5 | 5 | 3 | 3.3 | OBS RF08 |
| RF | O aplicativo deve mostrar se o pagamento foi confirmado | 5 | 5 | 3 | 3.3 | OBS RF12 |
| RNF | O sistema deve garantir que o acesso a funcionalidades primárias seja feito através de componentes de interface autoexplicativos. Ícones de navegação, como o menu principal, devem ser acompanhados por um rótulo textual (ex: "Menu") para facilitar a descoberta por parte do usuário | 5 | 5 | 3 | 3.3 | OBS RNF09 |
| RF | O aplicativo deve permitir limpar a seleção feita | 4 | 3 | 2 | 3.5 | OBS RF07 |
| RF | Os dados do usuário são mantidos em sigilo e protegidos | 5 | 5 | 4 | 2.5 | ENT18 |
| RNF | A transição de telas durante o fluxo de aposta deve ser fluida e sem travamentos perceptíveis | 4 | 4 | 3 | 2.6 | OBS RNF06 |
| RNF | O resultado de uma loteria deve ser carregado e exibido na tela em menos de 3 segundos sob uma conexão 4G/5G padrão | 5 | 4 | 4 | 2.25 | OBS RNF02 |
| RF | O aplicativo deve permitir interação com o menu de loterias ao clicar em experimentar | 3 | 3 | 3 | 2.0 | OBS RF02 |
| RF | O aplicativo deve permitir adicionar o jogo ao carrinho de apostas | 3 | 3 | 3 | 2.0 | OBS RF09 |
| RNF | A navegação entre a seleção de jogos, o preenchimento do volante e o carrinho de compras deve ser intuitiva, exigindo no máximo 3 toques para ir de uma seção a outra | 3 | 3 | 3 | 2.0 | OBS RNF01 |
| RNF | Os números selecionados no volante digital devem ser claramente diferenciados dos não selecionados, através de cor e contraste | 3 | 3 | 3 | 2.0 | OBS RNF04 |
| RNF | A sessão do usuário deve expirar automaticamente após 15 minutos de inatividade para proteger a conta | 3 | 3 | 3 | 2.0 | OBS RNF08 |

### Requisitos de Baixa Prioridade (Prioridade < 2.0)

**Tabela 4**

| Tipo | Requisito | Valor | Risco | Custo | Prioridade | ID |
|------|-----------|-------|-------|-------|------------|----|
| RF | O software deve ter opções de cores escuras e claras | 1 | 1 | 3 | 0.7 | ENT07 |

## Conclusão

A utilização de uma técnica de priorização baseada em valor, risco e custo permitiu uma análise mais refinada e estratégica dos requisitos, facilitando a tomada de decisão sobre o que deve ser desenvolvido primeiro. Essa abordagem ajuda a equilibrar as expectativas do usuário com a viabilidade técnica e os recursos disponíveis.

## Bibliografia

SERRANO, Milene; SERRANO, Maurício. **Requisitos (Aula 07): Elicitação, Modelagem e Análise**. UnB Gama, Brasília, 2025. Disponível em:  <https://aprender3.unb.br/pluginfile.php/3210604/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>. Acesso em: 29/09/2025.

## Versionamento

| Versão | Data | Autor | Descrição | Revisor |
|--------|------|-------|------------|---------|
| ``1.0`` | 30/09/2025 |  [João Pedro Araújo](https://github.com/Jadequilin) | Priorização com base em valor, risco e custo |[Rivadalvio Joaquim](https://github.com/RivaFilho) |





