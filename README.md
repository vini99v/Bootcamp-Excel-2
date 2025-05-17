# 📊 IR Tracker Excel

**Organizador Inteligente para Declaração de Imposto de Renda**

Ferramenta em Microsoft Excel desenvolvida para auxiliar na coleta, organização e conferência de dados utilizados na declaração de Imposto de Renda de Pessoa Física (IRPF). Permite centralizar informações ao longo do ano de forma validada, com uma interface amigável, menus interativos e recursos de automação.

---

## 🧭 Sumário

1. [Descrição do Projeto](#descrição-do-projeto)  
2. [Recursos Principais](#recursos-principais)  
3. [Estrutura da Planilha](#estrutura-da-planilha)  
4. [Fluxo de Navegação](#fluxo-de-navegação)  
5. [Validações Automáticas](#validações-automáticas)  
6. [Funcionalidades Extras](#funcionalidades-extras)  
7. [Como Usar](#como-usar)  
8. [Requisitos Técnicos](#requisitos-técnicos)  
9. [Licença](#licença)

---

## 📝 Descrição do Projeto

Esta planilha tem como objetivo facilitar o processo de organização de dados para o Imposto de Renda, permitindo que o contribuinte mantenha ao longo do ano todas as informações necessárias para a declaração, com validações, painéis de controle e automações simples.

A proposta é eliminar o uso de anotações soltas, reduzir erros de preenchimento e acelerar o processo de declaração.

---

## 🧰 Recursos Principais

- Registro de dados financeiros, patrimoniais e pessoais;
- Interface de navegação com menus interativos (VBA);
- Validações automáticas de entrada;
- Painel resumo para revisão e conferência de informações;
- Links rápidos para programas e orientações da Receita Federal.

---

## 🗂️ Estrutura da Planilha

| Aba                    | Função                                                                 |
|------------------------|------------------------------------------------------------------------|
| **Início**             | Menu principal, instruções gerais e botões de navegação                |
| **Dados Pessoais**     | CPF, endereço, dependentes, tipo de declaração                         |
| **Rendimentos**        | Tributáveis, isentos, exclusivos, exterior                             |
| **Despesas Dedutíveis**| Educação, saúde, previdência, pensão alimentícia                       |
| **Bens e Direitos**    | Imóveis, veículos, aplicações financeiras                              |
| **Dívidas e Ônus**     | Financiamentos, empréstimos                                            |
| **Resumo Geral**       | Totalizadores e alertas de inconsistência                              |
| **Ajuda e Links**      | Links úteis, FAQ e sites da Receita Federal                            |

---

## 🔁 Fluxo de Navegação

1. Abrir a planilha e ir até a aba **Início**;
2. Selecionar a seção desejada por meio dos botões interativos;
3. Preencher os dados com base nas instruções fornecidas em cada aba;
4. Consultar a aba **Resumo Geral** para checar consistência dos dados;
5. Acessar **Ajuda e Links** para auxílio ou preenchimento no programa oficial da Receita.

---

## ✅ Validações Automáticas

- CPF: verificação de formato com máscara `000.000.000-00`;
- CNPJ: exigência de 14 dígitos numéricos válidos;
- Datas: impedimento de datas futuras ou inválidas;
- Categorias com listas suspensas padronizadas;
- Preenchimento obrigatório com destaques em vermelho;
- Alerta de inconsistência no **Resumo Geral** se somas estiverem erradas.

---

## 🧩 Funcionalidades Extras

- Botões com VBA para navegação entre abas;
- Limpeza automática de dados para novo uso;
- Exportação em PDF das seções preenchidas;
- Links úteis:
  - [Programa IRPF](https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda)
  - [Perguntão IRPF](https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/perguntao-irpf)
  - [Cálculo do IR Online](https://www.calculador.com.br/calculo/imposto-de-renda-pessoa-fisica)

---

## 🧑‍💻 Como Usar

1. Baixe o arquivo `IR_Tracker_Excel.xlsm`;
2. Abra no Excel e **habilite as macros**;
3. Acesse a aba **Início** e clique no botão da seção desejada;
4. Preencha os dados de acordo com as instruções;
5. Consulte a aba **Resumo Geral** para verificação final;
6. Utilize os dados para preencher o programa oficial da Receita.

---

## 💻 Requisitos Técnicos

- Microsoft Excel 2016 ou superior;
- Macros habilitadas (arquivo `.xlsm`);
- Permissão de execução de conteúdo externo (caso use links).

---

## 📄 Licença

Distribuído sob a Licença MIT.  
Você pode usar, modificar e redistribuir esta ferramenta livremente, desde que preserve os créditos do autor original.

---

