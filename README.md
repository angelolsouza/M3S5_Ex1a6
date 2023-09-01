LabSchool Manager - Gestão de Atendimentos Escolares

 - Escopo do Projeto
A LABSchool Edu, renomada empresa do ramo de tecnologia educacional, que está expandindo seus serviços. Por conta da expansão, o time de gestão necessita da criação de um sistema online(WEB), intitulado LABSchool Manager, para gerenciamento das informações de atendimentos realizados aos estudantes que será utilizado pelos Pedagogos para melhor acompanhamento e orientações pedagógicas.

- Requisitos do sistema
Para construção do sistema LabSchool Manager foram utilzados as seguintes ferramentas:
Skills: Organização com Trello, criação de documentação e apresentação de solução;
Versionamento: Uso do GitHub para versionamento de código;
IDE utilizada: Visual Studio Code;
Programação WEB: Javascript, Typescript, CSS, HTML, Angular e Bootstrap;

- Descritivo para execução do sistema
Considerando que os procedimentos para execução via linha de comando do GitHub estejam instalados segue:
Escolher um diretório da sua preferência;
Clicar com o botão direito e escolhar a opção (Git Bash Here);
Executar a linha de comando (Git init);
Executar a linha de comando:
(Git clone https://github.com/repositorio/Modulo2-Projeto_Avaliativo.git)
No mesmo diretório onde foi efetuado o clone(download) do sistema, executar a linha de comando (code .) para abrir o Visual Studio Code;
Depois de aberto o Visual Studio clone, clicar na barra superior, opção (New Terminal) para abrir um terminal para digitação dos comandos necessários para execução do sistema, segue os comandos:
            npm install <instalação dos pacotes Angular, necessários para execução do sistema>
            ng serve <compilação do sistema e demais inicializações dos pacotes do Angular>

Se a execução do comando (ng serve) ocorrer sem erros de compílação, deverá ser exibido no terminal a seguinte mensagem:

-------------------------------------------------------------------------------------
           ✔ Browser application bundle generation complete.

Initial Chunk Files   | Names         |  Raw Size
vendor.js             | vendor        |   2.65 MB |
styles.css, styles.js | styles        | 497.63 kB |
polyfills.js          | polyfills     | 333.17 kB |
main.js               | main          | 117.61 kB |
runtime.js            | runtime       |   6.53 kB |

                      | Initial Total |   3.58 MB

Build at: 2023-07-30T00:56:08.699Z - Hash: a41de363e72f37de - Time: 3288ms

** Angular Live Development Server is listening on localhost:4200, open your browser on <http://localhost:4200/> **

√ Compiled successfully.
--------------------------------------------------------------------------------------

Abra outro terminal, e execute o comando (json-server --watch db.json) para iniciar o servidor db.json;
Se a execução do comando ocorrer sem erros, deverá ser exibido no terminal a seguinte mensagem:
--------------------------------------------------------------------------------------
  Loading db.json
  Done

  Resources
  <http://localhost:3000/alunos>
  <http://localhost:3000/pedagogicos>
  <http://localhost:3000/usuarios>

  Home
  <http://localhost:3000>

  Type s + enter at any time to create a snapshot of the database
  Watching...
------------------------------------------------------------------------------------------

Se nenhum tipo de erro ocorrer nos dois terminais, abra um navegador da sua preferência e digite a seguinte URL: <http://localhost:4200/> e tecle Enter;

O sistema Web LabSchool Manager será exibido no navegador.

- Melhorias sugeridas:
Inclusão da opção de impressão de relatórios;
Inclusão de log de ocorrências dos procedimentos operacionais;
Acrescentar cadastro dos pais do aluno;

FIM
