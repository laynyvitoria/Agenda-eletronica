# 📚 Agenda Eletrônica

**Agenda Eletrônica** é uma aplicação desenvolvida em C para o gerenciamento de contatos pessoais. O programa permite a inserção, visualização e armazenamento de dados de contatos em um arquivo binário (`dados.dat`), oferecendo uma solução prática para a organização de informações.

## 🎯 Objetivo

Este projeto é voltado para a conclusão da disciplina de **Programação Computacional** do curso de **Engenharia de Computação** da **Universidade Federal do Ceará - Campus Sobral**. 🏆

## 🔧 Funcionalidades

- **Cadastro de Contatos:** Adicione contatos com informações detalhadas:
  - 🧑 Nome Completo
  - 📞 Números de Telefones:
    - 📞 Fixo
    - 📱 Celular1
    - 📱 Celular2
  - 📧 E-mail
  - 🏠 Endereço:
    - 🛣️ Rua
    - 🏠 Número
    - 🏠 Complemento
    - 🏘️ Bairro
    - 🌆 Cidade/Estado
  - 💍 Estado Civil (Solteiro, Casado, Separado, Viúvo)
  
- **Armazenamento em Arquivo:** Dados são salvos em um arquivo binário para persistência. 📁

- **Carregamento e Exibição:** Dados são carregados e exibidos sempre que o programa é iniciado. 🔄

- **Opções de Atualização:** Adicione novos contatos ou visualize os já existentes. ✍️

## 📊 Estrutura de Dados

A estrutura de dados usada no programa é:

```c
typedef struct {
    char nome[51];
    char telefoneFixo[15];
    char telefoneCelular1[15];
    char telefoneCelular2[15];
    char email[51];
    char rua[51];
    int numero;
    char complemento[51];
    char bairro[51];
    char cidadeEstado[51];
    char estadoCivil[10];
} Contato;
