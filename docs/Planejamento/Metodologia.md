## Introdução 

Para a elaboração das etapas e visando aprimorar as atividades do grupo, foi utilizado a metodologia Scrum. O Scrum é um framework para desenvolvimento ágil tanto de software como de outras áreas. Derivado do manifesto ágil, se tornou o principal a ser utilizado para a organização e gerencia de grandes projetos, visando sempre a otimização do time, e entregas rápidas e contínuas de releases.

## Política de commit

Visando um controle mais claro das alterações feitas nos documentos, foi adotada uma política de commits. O objetivo é organizar melhor o registro das modificações e identificar quem realizou cada mudança.

A equipe definiu que a mensagem do commit deverá ser igual ou parecida com a descrição escrita no histórico de versionamento do arquivo ou uma mensagem que descreva se é uma correção/atualização. Assim, se for necessário localizar o commit no repositório, a busca será simples e direta. E se caso tenha uma remoção não proposital de conteúdo, a identificação com os termos do GitHub de correção facilitará a busca pelo commit específico. 

O modelo de commit a ser seguido é:

    git commit -m "Descrição da mudança feita no arquivo"

Se houver necessidade de usar *co-authored*, ele pode ser incluído normalmente, sem nenhuma regra adicional.

E como no projeto a página é montada pelo programa do MKDocs, toda vez que um integrante commitar e der push, ele deverá utilizar um comando do MKDocs para atualizar a página, no qual seria: 

    mkdocs gh-deploy 

## Política de revisão

Para que nenhum arquivo fique com alguma informação faltando ou errada, foi definido que a cada nova modificação feita nos arquivos, será escolhido pelo autor do commit um outro membro da equipe para ser o revisor e, assim, apontar os pontos que precisarão ser modificados, caso nescessário. 

## Versionamento 
| Versão | Data       | Autor               | Descrição                  | Revisor |
|:--------:|:------------:|:---------------------:|:---------------------:|:---------:|
| ``1.0``    | 07/09/2025 | [Luan Vinícius](https://github.com/luannvi)   | Abertura do documento | - |
| ``1.1``    | 07/09/2025 | [Luan Vinícius](https://github.com/luannvi)   | Adição de conteúdo | [Miquéias Ezequiel](https://github.com/Kael-web7) |