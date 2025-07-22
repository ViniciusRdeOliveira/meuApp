# Projeto Magic XPA - Sistema de Cadastros

**Desenvolvido por:** Vinicius Ribeiro de Oliveira  
**Email:** vinicius.r.oliveira@outlook.com.br  
**Telefone:** (51) 98943-3755  
**Localização:** Gravataí/RS - Brasil

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido utilizando **Magic XPA**, com base no treinamento realizado na empresa **Adderi**, localizada em São Leopoldo/RS.

O objetivo do sistema é criar um ambiente funcional para:

- Cadastro e edição de **Clientes**
- Cadastro e edição de **Pedidos**
- Cadastro e edição de **Fornecedores**
- Cadastro e edição de **Cidades**
- Cadastro e edição de **Países**

Este projeto serve como base para aplicações empresariais de gestão de dados, demonstrando conceitos práticos de desenvolvimento com Magic XPA.

---

*Projeto de caráter educacional e demonstrativo.*

## Regras de Negócio

### Edição de Clientes

- Se o **salário** for **maior que 5000**:
  - O cliente é promovido a **Cliente Ouro**
  - A **data e hora atual** são registradas
  - O **crédito** é atualizado para: `salário × 3`

- Se o **salário** for **maior que 2000** e **até 4999**:
  - O **crédito** será calculado como: `salário × 2`

- Se o **salário** for **menor que 2000**:
  - O **crédito** será igual ao valor do **salário**

- Menus **Clientes**,**Pedidos**,**Produtos**, **Fornecedores** e **Países e Cidades** permitem emissão de relatório.