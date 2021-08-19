# senai-versoes-colaboracoes

readme de exemplo

1. Instalação do Git no meu computador.
2. Configuração global do usuário (git config --global user.name "DIERGENE"/ git config --global user.email "diergene@gmail.com".
3. Criar uma pasta _Git > crie "senai-versoes-colaboracoes" dentro da pasta _Git.
4. Crie um repositório Git local (execute o Git Bash com o botão direito dentro da pasta senai-colaboracoes).
5. Com o prompt aberto execute o comando git init para iniciar o repositório local.
6. Abra a pasta "senai-versoes-colaboracoes" e crie um arquivo chamado "versoes" com a extensão ".txt"
7. Use o comando git status para rastrear alterações.
8. Depois use o comando git add versoes.txt para registrar.
9. Verifique a alteração com o comando git status.
10. Use em seguida o comando git commit -m "meu primeiro commit" para salvar no repositório.
11. Visualize as alterações com o comando git log no terminal.
12. Abra a pasta " senai-versoes-colaboracoes ", abra o arquivo versoes.txt e dentro dele coloque a palavra praticando!
13. Verifique a alteração com o comando git status.
14. Use o comando git add para registrar a modificação do arquivo versoes.txt
15. Use o comando  git commit -m "realizando uma alteracao no arquivo  versoes.txt" para salvar no repositório.
16. Crie um repositório remoto ( Online ) no github.
17. Com o prompt aberto realize a ligação dos repositórios (local com o remoto criado no github) atraves do comando git remote add origin https://github.com/DIERGENE/senai-versoes-colaboracoes.git
18. Depois visualize o repositório informado com o comando git remote -v.
19. Publique as alterações no repositório remoto com o comando git push -u origin main.
20. Quando executar o comando ele irá te encaminhar para autorizar seu usuário (no caso foi o meu)
21. Acesse a page do github para visualizar as informações que foi publicadas.
22. Faça uma alteração diretamente do repositório remoto (githhub) criando um arquivo com o nome README.
23. Baixe a alteração do repositório remoto (gihub) para o repositório local com o prompt aberto digite o comando git pull. (será possivel ver a atualização baixada no diretório local)
24. Depois foi criado dois arquivos, "arquivo-nao-publicado" e ".gitignore" na pasta "senai-versoes-colaboracoes"
25. Abri o arquivo ".gitignore" e escrevi "arquivo-nao-publicado" para ignora-lo.
26. Usei o comando git status para verificar as modificações.
27. Em seguida comando git add para registrar as modificações.
28. Confirmado com o comando git commit -m "adicionando o gitignore"
29. E publicado com o comando push -u origin main.
30. Com o prompt aberto digite comando git checkout -b tarefa/minha-primeira-branch para criar a primeira ramificação. (note que ela vai deixar de estar na local "main" e passará para "tarefa/minha-primeira-branch").
31. Depois vá na pasta "senai-versoes-colaboradoes" abra o arquivo README.md (vai ser feita a alteração nesse arquivo/bloco de notas). Escreva "lembrei do comando: git status" e salve.
32. Veja a alteração com o comando git status, registre com o comando git add . e faça o commit -m "adicionando comando git status", use o comando push -u origin tarefa/minha-primera-branch.
33. Veja a alteração no repositório remoto na page do github (na sua conta aonde você criou o repositório remoto)
34. Volter para a "master" (repositório local) com o comando  git checkout master.
35. Crie uma nova branch com o comando git checkout -b exemplo-branch.
36. Abra a pasta "senai-versoes-colaboracoes" e abra o arquivo "README.md" (vai perceber que não teve alteração aqui pois foi criado uma nova branch apartir da master).
37. Escreva no arquivo README.md "lembrei do comando: git commit" e salve.
38. eja a alteração com o comando git status, registre com o comando git add . e faça o commit -m "adicionando comando git status", use o comando push -u origin exemplo-branch.
39. Veja a alteração no repositório remoto na page do github (na sua conta aonde você criou o repositório remoto).
40. Unificaremos os ramos com o prompt aberto "tarefa/minha-primeira-branch" com a "exemplo-branch" com o comando "git merge tarefa/minha-primeira-branch" 
41. Resolva o conflito que irá aparecer abrindo o a pasta "senai-versoes-colaboracoes" abra o arquivo README.md e apague <<<<<<HEAD apague ====== apague >>>>>>> tarefa/minha-primeira-branch e depois salve o arquivo.
42. Com o prompt aberto registre com o comando git add . depois use o comando git commit -m "resolvendo conflito"
  e finalize com o comando git push origin exemplo-branch. (verifique no repositório remoto a alteração)
43. Criaremos uma tag na "master". (não esqueça de voltar para ela com o comando git checkout main)
44. Com o terminal aberto  use o comando git tag -a v1.0 -m "minha primeira tag.
45. Verifique com o comando git tag as tags criadas.
46. Para ver alguma informação de uma tag especifica como a que foi criada digite o comando git show v1.0.
47. E para encerrar publique no repositório remoto (github) com o comando git push origin --tags.
50. Não esqueça de acessar o repositório remoto (github) para visualizar a tag criada/publicada.
