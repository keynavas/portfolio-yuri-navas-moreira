# 🛡️ Algoritmo de Auditoria de Dados

## 📝 Descrição do Projeto
Este projeto foi desenvolvido como parte da disciplina de **Lógica de Programação**. O objetivo é criar um sistema de **Auditoria de Vendas Semanais** que utiliza conceitos de Ciência de Dados e Programação em Python para detectar anomalias financeiras e garantir a consistência de registros.

O sistema analisa entradas de vendas, calcula médias e identifica "Outliers" (discrepâncias) que podem indicar erros ou fraudes, utilizando regras de escopo global e local.

## 🚀 Tecnologias Utilizadas
* **Linguagem:** Python 3.10
* **Conceitos:** Escopo de Variáveis (Global/Local), Casting de Dados, Lógica Condicional e F-Strings.

## 📊 Fundamentos da Auditoria (Parte 1)
Como parte da investigação prévia ao código, o sistema aborda:
* **Discrepância (Outliers):** Compreensão de como valores extremos distorcem a média aritmética.
* **Normalização:** A estratégia de filtrar valores discrepantes para obter uma visão real dos dados.
* **Margem de Tolerância:** Definição de limites financeiros para disparar alertas de revisão.

## ⚙️ Regras de Negócio
1. **Limite de Segurança:** Uma variável global define o teto para vendas comuns (R$ 10.000,00).
2. **Quarentena:** Ativada se a média das vendas ultrapassar o limite de segurança.
3. **Revisão Manual:** Sugerida se qualquer venda individual for 5x maior que a média calculada.

## 🔧 Como Executar
1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
