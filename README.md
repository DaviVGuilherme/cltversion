Criei o site a partir de Html e Css, usando comandos para fazer um site que tivesse informações sobre 
- Controle de Versão
- Controle de Mudanças
- Integração Contínua
no código utilizei body head para montar a estrutura e section para separar cada tópico e h para títulos maiores
e p para mais textos
no git usei
git init
git add.
git commit
git branch
git remote
git push



Documentação 
Main:De maneira simplificada, os ramos (branches) no Git são semelhantes a um ramo de uma árvore, onde o tronco seria a base do código. Desse modo é possível criar diversos ramos e fazer alterações, enquanto a base permanece intacta. Por padrão o ramo principal é denominado de main (master, na versão antiga).

Features:são branches para o desenvolvimento de uma funcionalidade específica. Elas devem ter o nome iniciado por feature, por exemplo, “feature / payment-system”. É importante saber que essas features branches são criadas sempre a partir da branch Develop.

bugfix: Uma branch criada a partir da Staging para realizar correções e no final ela faz o merge na Staging e na Main. A branch é removida após realizar o merge. Hotfix – Uma branch criada a partir da Production para realizar correções e no final ela faz o merge diretamente na Staging e Production.

