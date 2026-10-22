# Portal de Turmas — UNICEPLAC

Atividade integradora de Programação para Web, Engenharia de Software, 4º período (2026/2).

## Conteúdo

- `index.html` e `estilo.css`: portal semântico e responsivo.
- `portal-bootstrap.html`: versão Bootstrap com cards, formulário, validação e toast.
- `processar.jsp`: valida o cadastro enviado por POST, apresenta o resultado e guarda o último nome na sessão.
- `turmas.jsp`: lista as turmas e mostra o último cadastro da sessão.
- `respostas-conceituais.txt`: respostas das questões teóricas.

## Visualizar

- [Frontend no CodeSandbox](https://codesandbox.io/p/sandbox/r8hqwj) — demonstra as páginas HTML e CSS. O CodeSandbox não executa JSP nesta configuração.
- [Código-fonte no GitHub](https://github.com/FilipeFilg/portal-turmas).

## Executar as páginas JSP

Use Java e Apache Tomcat 10.1. Copie os arquivos do projeto para `webapps/portal-turmas/` no Tomcat, inicie o servidor e abra `http://localhost:8080/portal-turmas/portal-bootstrap.html`. O formulário envia os dados para `processar.jsp`; a página `turmas.jsp` lê o último nome salvo na sessão.

O projeto foi testado no GitHub Codespaces com OpenJDK 25 e Tomcat 10.1.61. No Codespace criado para este repositório, o Tomcat está em `~/tomcat10`; para reiniciá-lo, execute `~/tomcat10/bin/startup.sh` e abra a porta encaminhada 8080.
