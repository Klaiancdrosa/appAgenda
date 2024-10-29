# **App Agenda**
&gt; Desenvolvido para cadastrar no banco de dados, listar os usuários e pesquisa-los.

## Descrição
O **App Agenda** permite ao cliente cadastrar informações de usuários ao banco de dados e realizar pesquisas.

## Funcionalidades
- [x] Entrada de dados (nome, cpf, telefone)
- [x] Interface simples e intuitiva

## Tecnologias Utilizadas
- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView, EditText e ListView** para entrada e exibição de dados
      
## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
```bash
git clone https://github.com/Klaiancdrosa/appAgenda.git
```
2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.
   
## Estrutura do Projeto
```bash
├── app
│ ├── src
│ │ ├── main
│ │ │ ├── java
| | | | |── br.ulbra.appagenda
│ │ │ │ | ├── Conexao.java # Realiza a conexão do banco de dados.
│ │ │ │ | ├── ListarPessoasActivity.java # Principal atividade aonde ocorre o funcionamento dos menus, cadastros e listview.
│ │ │ │ | ├── MainActivity.java # Atividade aonde ocorre a adição do usuário ao banco e a listview.
│ │ │ │ | ├── Pessoa.java # A classe do usuário cadastrado.
│ │ │ │ | ├── PessoaDAO.java # Banco de dados principal. 
| │ │ │ ├── res
| | | | ├── drawable # imagens e icones utilizados na tela principal
│ │ │ │ ├── layout
│ │ │ │ | ├── activity_listar_pessoas_activity.xml # Layout de tela de listagem dos usuários cadastrados e utilização dos menus
│ │ │ │ │ ├── activity_main.xml # Layout do cadastro de usuários
│ │ │ │ ├── menus
│ │ │ │ | ├── menus_contexto.xml
│ │ │ │ | ├── menus_principal.xml
│ │ │ │ └── values
│ │ │ │ ├── strings.xml # Strings usadas no app
│ │ │ │ ├── colors.xml # Cores definidas no projeto
│ └── build.gradle # Configuração do Gradle
└── README.md # Este arquivo
```

## Design e Prototipage
A interface do app foi criada usando **ConstraintLayout**;
O design é minimalista e fácil de usar, com foco na simplicidade.

## Telas do App Agenda
**Tela Principal**
Tela principal aonde o usuário, pode visualizar, editar, excluir e pesquisar os usuários através dos menus.

![image](https://github.com/user-attachments/assets/c28c3fa3-9062-429a-9cbd-eb8e3939f38a)

**Tela Secundária**
Tela aonde cliente cadastra os usuários na agenda.

![image](https://github.com/user-attachments/assets/95cec89f-3311-4184-8549-e9cedcfaf74e)

## Desenvolvedores
**Klaian Conceição da Rosa** - Desenvolvedor - [GitHub](https://github.com/Klaiancdrosa)

## Licenças
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
