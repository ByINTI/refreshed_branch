## Descrição
O objetivo deste é criar uma action composta para ser utilizada com step ao início de cada job dos testes automatizados do IMS. Isso é necessário pois a branch é deletada em caso de cancelamento do workflow ou falha de qualquer um dos jobs dos testes. Sendo assim não sendo possível re executar um job separadamente, pois a branch já foi deletada.

Sendo assim, esse vai gerenciar a criação de uma branch temporária, que será deletada ao final do workflow.