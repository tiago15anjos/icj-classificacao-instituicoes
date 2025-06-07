# Classificação das Instituições da Iniciação Científica Júnior (ICJ)

Este repositório apresenta o processo de classificação das instituições participantes da **Iniciação Científica Júnior (ICJ)** entre 2010 e 2023, com base em dados do CNPq (Painel de Fomento em CT&I) e informações institucionais do Cadastro Nacional de Instituições de Educação Superior (e-MEC). A sistematização integra parte da pesquisa de doutorado em desenvolvimento no Programa de Pós-graduação em Ciência, Tecnologia e Sociedade (PPGCTS/UFSCar).

---

## 🎯 Objetivo Geral

Analisar as dinâmicas de alocação de recursos para os programas de Iniciação Científica Júnior no Brasil, considerando a distribuição regional, os perfis institucionais, os valores aplicados, as modalidades de bolsas e o perfil dos bolsistas, com base nos dados do CNPq e INEP.

---

## 📁 Arquivos do Repositório

- **`ICJ_Instituicao_Ano_bolsistas_2010_2023.xlsx`**  
  Arquivo final com a base de dados consolidada da ICJ, incluindo:
  - Número de bolsas e beneficiários
  - Valores anuais (R$ e US$)
  - Modalidade, área e linha de fomento
  - Instituição, região, município e UF
  - Classificação institucional (tipo, categoria, administração)

- **`CATEGORIAS_INSTITUICOES.xlsx`**  
  Planilha criada manualmente a partir do cruzamento com o Cadastro e-MEC, com a classificação de cada instituição como:
  - IES Pública ou Privada
  - Escola da Educação Básica
  - Institutos de Pesquisa
  - ONGs e Fundações

- **`ICJ_Classificacao_Instituicoes.ipynb`**  
  Notebook com todo o processo de tratamento e padronização dos nomes institucionais, junção das bases e geração da classificação final.

---

## 🔎 Metodologia

- Extração dos dados brutos do Painel de Fomento do CNPq
- Tratamento e padronização de nomes com Python
- Cruzamento com base do e-MEC
- Classificação manual para instituições fora do sistema
- Integração de dados estatísticos (valores, bolsas, regiões)
- Exportação da base consolidada

---

## 🧩 Colunas de destaque

- `Qtd_Bolsistas_Inst`: número de bolsistas por instituição/ano
- `Valor_Rs_sum`: total de recursos aplicados
- `Modalidade`, `Área`, `Grande_Area`: detalhamento temático
- `Origem_do_Recurso`: fonte de fomento (CNPq, FAP, etc.)
- `Classificacao_Instituicao`, `CATEGORIA`, `CATEGORIA_ADMINISTRATIVA`

---

## 💡 Exemplos de Análises Possíveis

- Evolução do número de bolsas e recursos por região
- Comparação entre tipos de instituições (IFs, universidades, escolas)
- Concentração regional e institucional dos investimentos em ICJ
- Relação entre presença de IES e alocação de bolsas
- Impacto das normas regulatórias do CNPq na difusão da ICJ

---

## 🏛️ Contexto Acadêmico

Este repositório compõe parte da pesquisa intitulada:

> **Políticas Públicas de Incentivo à Iniciação Científica Júnior: Uma Análise Regional e Institucional no Brasil**  
> Autor: Tiago Ribeiro dos Anjos  
> Doutorando em Ciência, Tecnologia e Sociedade – UFSCar  
> Orientação: Profa. Dra. Maria Teresa Miceli Kerbauy  
> Supervisão no exterior: Prof. Dr. Creso Sá (University of Toronto)

A pesquisa é financiada pela CAPES, no âmbito do Programa de Doutorado Sanduíche no Exterior (PDSE), edital n. 26/2024.

---

## 📘 Licença

Este repositório está licenciado sob os termos da [MIT License](LICENSE).

---

## ✉️ Contato

Para dúvidas ou colaborações:
**Tiago Ribeiro dos Anjos**  
📧 [tiagoribeiroanjos@gmail.com](mailto:tiagoribeiroanjos@gmail.com)
