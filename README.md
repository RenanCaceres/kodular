# 📲 App de Cadastro de Alunos - UTFPR-CP

Este aplicativo foi desenvolvido como projeto da disciplina **Desenvolvimento Sem Código**, ofertada no curso de **Análise e Desenvolvimento de Sistemas** da **UTFPR - Campus Cornélio Procópio**.

## 💡 Objetivo do Projeto

O objetivo principal deste app é simular um **sistema de cadastro de alunos da UTFPR-CP**, onde o usuário (aluno) pode inserir seus 
dados pessoais e acadêmicos em um formulário simples e funcional. O foco do projeto está no uso de ferramentas de desenvolvimento visual, sem a necessidade de programação tradicional.

## 🧑‍🎓 Sobre o Autor

Desenvolvido por **Renan Cáceres Anselmo**, estudante de **Análise e Desenvolvimento de Sistemas**.  
Durante a disciplina, Renan utilizou os recursos da plataforma **Kodular** para criar um aplicativo funcional com foco em **experiência de usuário** e **armazenamento local de dados**.

## 🧩 Funcionalidades e Telas do Aplicativo

O aplicativo conta com uma navegação simples e objetiva, composta pelas seguintes telas:

### 📌 Tela Inicial
- Apresenta o nome do app e botões de navegação.
- Acesso ao menu principal.

### 🧾 Tela de Cadastro
- Formulário de cadastro com os seguintes campos:
  - **Nome Completo**
  - **CPF**
  - **Logradouro (Endereço)**
  - **Data de Nascimento**
  - **Curso**
- Botão **"Cadastrar"**, que salva os dados no banco local (**TinyDB**).
- Validações básicas de preenchimento dos campos obrigatórios.

### 🔍 Tela de Visualização
- Permite consultar os dados de um aluno já cadastrado.
- A consulta é feita com base no **CPF** digitado.
- Exibe os dados correspondentes ao CPF informado, se houver.

### ✏️ Tela de Atualização
- Permite editar os dados de um aluno existente.
- O sistema solicita o **CPF**, e se encontrado, preenche automaticamente os campos com os dados salvos.
- Após as edições, os novos dados substituem os antigos no banco de dados local.

### 🗑 Tela de Exclusão
- Solicita o **CPF** do aluno que deseja excluir.
- Caso o CPF seja encontrado, os dados são removidos do banco local.
- Há uma mensagem de confirmação para evitar exclusão acidental.

## 🔐 Identificação e Lógica de Acesso

Toda a lógica de busca, atualização e exclusão de dados é baseada no **CPF informado** pelo usuário. O CPF funciona como **chave única** no 
sistema, garantindo que cada cadastro seja identificado de forma exclusiva.

## 💽 Armazenamento

O app utiliza o **TinyDB**, componente de armazenamento local oferecido pelo Kodular, que mantém os dados mesmo após o fechamento do aplicativo.

## 🧱 Tecnologias Utilizadas

- **Kodular Creator** – plataforma para desenvolvimento de aplicativos Android sem código.
- **TinyDB** – banco de dados local.
- **Componentes visuais e lógicos em blocos**.

## 🚀 Como Usar

1. Acesse o [Kodular Creator](https://creator.kodular.io/).
2. Faça o upload do arquivo `Trabalho2.aia` disponível neste repositório.
3. Compile o projeto para gerar o `.apk`.
4. Instale o aplicativo em um dispositivo Android para testar.

## 📷 Capturas de Tela
<img width="413" height="705" alt="image" src="https://github.com/user-attachments/assets/e8ac3fd5-1d7b-4fe3-92ec-fb5f5e8ae6ac" />


## 📚 Sobre a Disciplina

**Desenvolvimento Sem Código** é uma disciplina prática voltada para introduzir os alunos a ferramentas de desenvolvimento de aplicativos por meio de 
interfaces gráficas, sem a necessidade de escrever código-fonte tradicional. Ideal para prototipagem rápida e aplicações educacionais.

---

