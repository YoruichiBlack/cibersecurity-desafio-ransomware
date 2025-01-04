# Ransomware para Sequestro de Dados

### Ferramentas

- Kali Linux
- Python
- Scripts encrypter.py e decrypter.py

## Scripts
- encrypter.py: Script responsável por criptografar o arquivo "texto.txt" e incluir em seu nome ".ransomwaretroll".
- decrypter.py: Script responsável por descriptografar o arquivo "texto.txt.ransomwaretroll" e retomar o seu nome de origem

### Executando o Ransomware no Kali Linux

- Acesso root: ``` sudo su ```
- Indo para a pasta documentos: ``` cd Documents ```
- Nessa pasta estão armazenados os scripts de criptografia e descriptografia e o arquivo de texto que será utilizado.
- Criptografando os dados do arquivo de texto: ``` python encrypter.py ```
- Lendo o arquivo criptografado: ``` cat teste.txt.ransomwaretroll ```
- Descriptografando os dados do arquivo de texto: ``` python decrypter.py ```
- Lendo o arquivo descriptografado: ``` cat teste.txt ```

### Resultados

![Alt text](./projeto-de-ransomware.png "Criptografia e Descriptografia dos Dados")

### Conclusão

Esse desafio prático foi uma oportunidade incrível para aprofundar meu entendimento sobre os mecanismos de criptografia e descriptografia de dados, além de explorar como essas técnicas são aplicadas em cenários reais de segurança cibernética.

