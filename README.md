# Classificação das Instituições da Iniciação Científica Júnior (ICJ)

Este repositório apresenta o processo de classificação das instituições participantes da **Iniciação Científica Júnior (ICJ)** entre 2010 e 2023, com base em dados do CNPq e informações institucionais do Cadastro Nacional de Instituições de Educação Superior (e-MEC).

---

## 📁 Arquivos do Repositório

- **`ICJ_Instituicao_Ano_bolsistas_2010_2023.xlsx`**  
  Arquivo final com o banco de dados consolidado da ICJ. Contém registros por ano, instituição, número de bolsistas, valores investidos e variáveis adicionais para análise.

- **`CATEGORIAS_INSTITUICOES.xlsx`**  
  Planilha desenvolvida manualmente com a classificação detalhada de cada instituição, com base no Cadastro e-MEC e categorias próprias para instituições que não constam no sistema.

- **`ICJ_Classificacao_Instituicoes.ipynb`**  
  Notebook contendo todo o processo de tratamento e junção das bases, bem como a padronização dos nomes e criação das classificações institucionais.

---

## 🔎 Objetivo

Esta sistematização visa:

- Identificar o perfil das instituições beneficiadas com bolsas da ICJ.
- Permitir análises mais refinadas por tipo de instituição (IES, escola pública, fundações, ONGs, etc.).
- Subsidiar discussões sobre políticas públicas de fomento à iniciação científica e popularização da ciência.

---

## 🧩 Metodologia

### Fontes utilizadas
- Dados da ICJ (CNPq)
- Cadastro e-MEC
- Complementação manual para instituições não identificadas

### Etapas
1. Padronização dos nomes das instituições (remoção de acentos, caixa alta)
2. Junção com o banco do e-MEC via nome padronizado
3. Complementação manual das instituições que não constam no e-MEC
4. Classificação final com colunas:
   - `Classificacao_Instituicao`
   - `CATEGORIA`
   - `CATEGORIA_ADMINISTRATIVA`
   - `ORGANIZACAO_ACADEMICA` (quando aplicável)

---

## 👨‍🎓 Autor

**Tiago Ribeiro dos Anjos**  
Doutorando em Ciência, Tecnologia e Sociedade – UFSCar  
[tiagoribeiroanjos@gmail.com](mailto:tiagoribeiroanjos@gmail.com)

---

## 📘 Licença

Este repositório está licenciado sob os termos da [MIT License](LICENSE).

