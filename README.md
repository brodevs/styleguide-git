# Style Guide Github.

``` 
**Boas práticas para se trabalhar com @github.** 
```

Então nesse mundo de desenvolvimento e muitos projetos é sempre bom mantermos um padrão de como trabalhar com a nossa a equipe em projeto. Vendo isso pensei "Porque não criar um styleguide?" tendo em vista que se não pensarmos desde já de como nos organizar e manter um fluxo bem padronizado, pode ser que perderemos um projeto inteiro e assim atrapalhar completamente o fluxo de trabalho.

O workflow utiliza duas branches fixas: develop e master.

Dica: estamos utilizando develop como branch principal para evitar problemas menores de push's indevidos
Os papéis dos branches são os seguintes:

develop: versão que contém todas as novas features desenvolvidas (onde todo o ciclo de teste e validação foram feitos), não deve conter desenvolvimentos não aprovados e desenvolvimentos incompletos, ou seja, tudo que está preparado e aprovado para ir pra próxima release em produção. caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em develop

master: última versão estável, contém todos os recursos entregues em produção, caso tenha algum hotfix, o conteúdo do hotfix também fica disponível em master
feature/xxxx: uma branch temporária que contém a implementação candidata na próxima release, onde seu ciclo de vida fica limitado à sua aprovação e validação, na sua finalização deve ir para o branch develop

bugfix/xxxx: uma branch temporária que contém uma correção que não é emergencial e pode ser levada para a próxima release. seu ciclo de vida é semelhante ao feature, somente muda o nome por respeito à nomenclatura da classificação da implementação

hotfix/xxxx: uma branch temporária que contém uma correção que é emergencial, devido à sua operação, deve ser definido por toda a equipe se a correção é uma hotfix. Seu ciclo de vida termina na validação da correção do erro e seu conteúdo deve ir para master e develop.
