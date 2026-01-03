# Teoria do Risco e Atuária - UFPR

Este repositório contém trabalhos práticos desenvolvidos para a disciplina de Teoria do Risco. As análises focam na aplicação de modelos estocásticos para resolver problemas do mercado de seguros e previdência, utilizando distribuições como Poisson, Gama e Exponencial.

---

## 🛠️ Conteúdo Técnico

Os projetos estão divididos em dois grandes pilares da análise de risco:

### 1. Cálculo de Prêmios (Trabalho 2)
Implementação de diferentes princípios para precificação de seguros, garantindo que o prêmio carregado seja suficiente para cobrir sinistros e incertezas:
* **Princípio do Valor Esperado:** Adição de um carregamento de segurança ($\theta$) sobre a esperança do sinistro.
* **Princípio da Variância e Desvio Padrão:** Ajuste do prêmio com base na volatilidade dos dados.
* **Princípio Exponencial:** Utilização de funções de utilidade para precificação sob aversão ao risco.



### 2. Teoria do Arruinamento (Trabalho 3)
Estudo da solvência de uma seguradora ao longo do tempo:
* **Coeficiente de Ajustamento:** Cálculo do parâmetro fundamental para determinar a estabilidade do fundo de reserva.
* **Probabilidade de Arruinamento ($\psi(u)$):** Estimativa da probabilidade de as indenizações superarem as reservas iniciais somadas aos prêmios recebidos.
* **Simulação de Reservas:** Análise do impacto do capital inicial ($u$) na segurança da operação.

---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Modelagem:** Uso intensivo de funções de densidade e momentos estatísticos para distribuições de cauda pesada.
* **Relatórios:** Documentação técnica produzida em R Markdown com a resolução teórica e prática dos problemas.

---

## 📂 Estrutura de Arquivos

* `TeoriaRisco2.Rmd / .pdf`: Focado em princípios de cálculo de prêmios.
* `TeoriaRisco3.Rmd / .pdf`: Focado em modelos de arruinamento e solvência.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
