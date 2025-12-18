# 🐾 PetCare System - Sistema de Gestão para Clínicas Veterinárias em Java

## Visão Geral

O **PetCare System** é uma solução desktop desenvolvida em Java para automatizar e gerenciar o fluxo operacional de clínicas veterinárias. O sistema centraliza desde o cadastro de tutores e pacientes (pets) até o controle clínico detalhado, incluindo gestão de vacinas e faturamento automático.

O objetivo do projeto é demonstrar a aplicação prática de conceitos sólidos de Engenharia de Software e Programação Orientada a Objetos (POO) para resolver problemas reais de negócio.

## Funcionalidades em Destaque

* **Gestão de Prontuários:** Sistema completo de histórico médico, permitindo o registro e consulta de diagnósticos, tratamentos e evolução clínica dos animais.
* **Cartão de Vacinas Inteligente:** Módulo dedicado ao controle imunológico, com monitoramento de datas de aplicação e cálculo automático de vencimentos/retornos.
* **Sistema de Cobrança Automatizado:** Integração financeira que calcula o valor total do atendimento somando consultas (baseado na especialidade do veterinário) e vacinas aplicadas no dia.
* **Interface Gráfica Fluida (GUI):** Interface construída com **Java Swing** utilizando o gerenciador de layout `CardLayout`, proporcionando uma navegação intuitiva e rápida entre as telas sem a abertura de múltiplas janelas (Single Window Application).

## Arquitetura e Design

O projeto foi estruturado seguindo os pilares da **Programação Orientada a Objetos (POO)**:

* **Herança:** Utilizada para modelar a hierarquia de usuários e funcionários.
* Exemplo: A classe `Veterinario` estende `Funcionario`, herdando atributos comuns e adicionando especificidades como CRMV e Especialidade.
* Exemplo: A classe `Tutor` estende `Pessoa`.


* **Encapsulamento:** Todos os atributos das classes de modelo (`Animal`, `Consulta`, `Agendamento`) são privados e acessados via métodos getters e setters, garantindo a integridade dos dados.
* **Polimorfismo:** Aplicado no tratamento genérico de listas e na manipulação de objetos derivados.
* **Organização:** O código é separado em pacotes lógicos (`vet.clinic`), distinguindo claramente as classes de modelo, as telas (Views) e a lógica de controle (`Sistema`).

## Tecnologias Utilizadas

* **Linguagem:** Java (JDK 8+)
* **Interface Gráfica:** Swing (JFrame, JPanel, CardLayout)
* **Manipulação de Datas:** Java Time API (`LocalDate`, `LocalDateTime`, `DateTimeFormatter`) para precisão em agendamentos e vencimentos.
* **IDE:** NetBeans

## 📸 Screenshots

* *Tela de Menu Principal*

* *Cadastro de Animais*

* *Prontuário Médico*


## ▶️ Como Executar o Projeto

1. **Clone o repositório:**
```bash
git clone git@github.com:sCesar-dev/Veterinary-clinic.git

```


2. **Abra o projeto:** Importe a pasta do projeto na sua IDE de preferência (recomendado: NetBeans ou IntelliJ IDEA).
3. **Execute:** Localize a classe principal `Main.java` no pacote `src/vet/clinic` e execute o arquivo.

---

Desenvolvido por **Samuel Cesar, Isabel Souza e Caio Lopes**
[LinkedIn](https://www.linkedin.com/in/samuel-cesar-193275219/) | [Curriculo](https://drive.google.com/drive/folders/18tICYCLwsoPX-RiXlsOtCtOEBoI_dBR2?usp=sharing)
