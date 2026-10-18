1. No Ciclo 1 usamos return 70. Por que isso é aceitável no TDD? O que
obrigou a escrever a soma de verdade?
R:Porque no inicio do Tdd tentamos fazer o teste passar da forma mais simples que conseguirmos. A complexidade dos testes subsequentes, que nos obrigram a fazer a validação real.

2. No Ciclo 3, por que testar com 69 e 70, e não com 50 e 90?
R:Pois a nota de aprovação é 70, sendo assim deve-se testar no limite da aprovação.

3. No Ciclo 4, o que mudou na refatoração? Como você teve certeza de
que não quebrou nada?
R:Foi criado um método para validar a nota e simplicar o código, sem ficar repetindo if's. Os testes nos falaram que o resultado continuou o mesmo.

4. No Ciclo 8, por que alteramos os testes antes de mudar o código?
R: Porque os testes documentam o novo resquisito e mostram que a atinga implementação não atendem mais ao comportamento que se espera.

5. Qual ciclo foi o mais difícil para você, e por quê?
R: Clico 7, porque nos fez alterar bastante a estrutura e refazer os testes.
