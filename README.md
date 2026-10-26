# desafio-imersao-itau
# Desafio de Validação de Operações Bancárias - Imersão Itaú

Solução desenvolvida em **Java** para o desafio de validação de códigos de operação num sistema de caixa digital.

##  Sobre o Desafio
O programa lê uma string de entrada e verifica se ela corresponde exatamente a uma das três operações permitidas:
- `DEPOSITO`
- `SAQUE`
- `TRANSFERENCIA`

A verificação respeita estritamente a sensibilidade a maiúsculas e minúsculas (*case-sensitive*). 

- **Entrada:** Uma única linha contendo o código da operação.
- **Saída:** `VALID` se for uma operação válida, ou `INVALID` caso contrário.

##  Tecnologias
- Java (JDK)

##  Como Executar
1. Certifique-se de ter o Java instalado no seu computador.
2. Compile o ficheiro:
   ```bash
   javac Main.java
