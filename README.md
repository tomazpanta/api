![image](https://github.com/user-attachments/assets/c6cd9656-6af4-4b0b-a38e-1dc4b4ea2dab)

# Exercício 1 
![image](https://github.com/user-attachments/assets/752537b9-09b0-46bb-bd79-a9f147ee08ea)
![image](https://github.com/user-attachments/assets/8b3ee967-dfcc-4ab2-8685-8335915eeb02)
![image](https://github.com/user-attachments/assets/285fc11c-7d6e-4b0a-b4d2-0f115fdb635f)

# Foi desenvolvido um API REST que foi em Spring Boot utilizando o IntelliJ. Foi criado o AlunoController como o controlador e possuiu um endpoint (/alunos) para receber as requisições em POST. 
# Foi criado um metodo chamado (criarAluno) que recebeu um objeto (Aluno) no corpo da requisição com o nome de @RequestBody e foi colocada a lógica de criação no AlunoService. 
# Para testar a API utilizamos o Insomnia, onde foi configurada uma requisição em POST no link local (http://localhost:8080/alunos) e enviei um JSON com os dados do aluno que foram: nome, email, cpf. Após esse processo a API retornou o código 201, confirmando que o aluno foi salvo. PS: testei 3 vezes e percebi que cada vez que era enviado pelo Insomnia o nome, email e cpf ficava salvo no banco de dados.
# Banco de dados esse que foi gerenciado pelo Dbeaver utilizando o PostgreSQL. A tabela aluno armazena os registros enviados pela API (Insomnia). E finalmente realizamos uma consulta com o (select * from aluno) para mostrar os dados que foram corretamente inseridos, confirmando que o funcionamento do processo foi realizado com sucesso!
# Resumindo, o projeto envolveu uma criação de uma API para inserir os dados no banco, utilizando o Insomnia para os testes e o DBeaver para verificar os registros.
