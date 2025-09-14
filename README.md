# Calculadora de IMC - JSF

Este projeto foi desenvolvido como atividade da disciplina **Programação de Servidores Web**, do curso superior de **Tecnologia em Sistemas para Internet**, ministrada pelo professor **Gustavo Maruyama**, 5º semestre, no **Instituto Federal de Educação, Ciência e Tecnologia de Mato Grosso do Sul – Câmpus Coxim**.

## Descrição

Aplicativo web para cálculo e classificação do **Índice de Massa Corporal (IMC)**, desenvolvido com **JavaServer Faces (JSF)**, **Maven** e **Payara 6**. O usuário insere peso e altura e recebe o IMC calculado com a classificação correspondente.

## Tecnologias utilizadas

* Java 11
* Jakarta EE 10 (JSF 3)
* Maven
* Payara 6
* XHTML

## Estrutura do projeto

```
CalculadoraIMCJSF/
 ├─ src/
 │   └─ main/
 │       ├─ java/
 │       │    └─ bean/ImcBean.java
 │       ├─ resources/
 │       └─ webapp/
 │            ├─ index.xhtml
 │            ├─ resultado.xhtml
 │            └─ WEB-INF/web.xml
 └─ target/
```

## Funcionalidades

* Recebe **peso** e **altura** do usuário
* Calcula o **IMC**
* Exibe a **classificação do IMC** conforme tabela oficial
* Permite **voltar** à tela inicial

## Como executar

1. Abrir o projeto no **NetBeans**
2. Rodar o projeto com o servidor **Payara 6**
3. Acessar no navegador: `http://localhost:8080/CalculadoraIMCJSF/index.xhtml`

## Observações

* O projeto utiliza **ManagedBean SessionScoped** para manter os dados entre páginas.
* O formulário e a navegação são feitos com **JSF 3 (XHTML)**.
* O Maven gerencia todas as dependências do Jakarta EE 10.

## Conclusão

A atividade permitiu entender na prática o funcionamento do **JSF**, a importância do **escopo dos beans**, e como desenvolver uma aplicação web dinâmica em Java, integrando **front-end e back-end** de forma organizada e eficiente.
