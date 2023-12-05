## Criptografia
Como sabemos a criptografia é a prática de proteger informações por meio de algoritmos.

Existem alguns variados tipos de criptografia, porém os 2 principais são os seguintes:

1. Simétrica: A criptografia simétrica é a qual usamos uma chave tanto para criptografar quanto para descriptografar.
2. Assimétrica: A criptografia assimétrica é a qual usamos uma crave para criptografar e outra chave para descriptografar. 
## Utilizando SHA256 
SHA256 é um algoritmo de criptografia nativo do SA:MP, a saída possui um comprimento de 256 bytes, no Pawn seria equivalente a 64 células. 

Antes de começarmos utilizar existem alguns termos que devem ser compreendidos para que não haja nenhum problema futuro.

1. **SALT:** O Salt consiste em concatenar/adicionar caracteres aleatórios na senha antes de efetuar o hash.
2. **HASH:** O Hash consiste na saída final, ou seja, ele é a chave na qual está armazenado a senha.
#### **OBSERVAÇÕES:** 
1. Na criação de um SALT sempre utilize um valor aleatório, nunca um valor definido.

- SHA256 Exemplo: [[SHA256]]
