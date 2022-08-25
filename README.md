# Olá, Mundo!
 **Repositorio versionado do curso de Git e GitHub**

Repositório criado durante uma aula ao vivo do Curso Em Vídeo no *YouTube*.

No curso foi utilizado o **GitHub Desktop**

---
# Abaixo comandos para uso no terminal que não foi ensinado durante o curso:

*git config --global user.email "meuemailn@github.com"* - Para configurar no Git o seu e-mail eo GitHub, para que os repositórios possam se comunicar;

*git init* - Para criar repoitório local;

*git add nomeDoArquivo* - Para adicionar arquivos ao repositório local;

*git diff* - Para ver quais foram as alterações do arquivo antes de fazer _commit_;

*git commit -m "Aqui você digita o que foi feito"* - Para commitar, colocar definitivamente os arquivos no repósitório local, deve ser feito depois do *git add nomeDoArquivo*;

*git status* - Para mostrar quais foram as alterações realizadas no arquivo;

*git checkout -b nome-da-branch* - Para criar uma nova branch;

*git branch* - Para ver todos os branchs e saber em qual branch você está;

*git checkout nome-da-branch* - Para mudar de branch;

*git show idDoGitLog* - Para ver as alterações do commit, primeiro no *git log* copie o id e utilize nesse comando no lugar de idDoGitLog;

*git merge nome-da-outra-branch* - Pegar modificações de outra branch e levar para a branch atual;

*git branch -d nome-da-branch* - Para deletar a branch;

*git remote add origin https://github.com/SEUUSUARIO/nomeDoSeuRepositorioCriadoNoGitHub* - Após criar manualmente um repositório no GitHub, faça a conexão do repositório local (Git) com o repositório remoto (GitHub);

*git push -u origin nome-da-branch* - Para enviar os dados da branch (códigos e arquivos) do repositório local (Git) para o repositório remoto (GitHub)

---

Para ignorar arquivos nos commits, crie o arquivo *.gitignore* de dentro informe os arquivos que devem ser ignorados.

