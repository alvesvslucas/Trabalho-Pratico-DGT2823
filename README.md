## 📘 Trabalho Prático — Tecnologias para Desenvolvimento de Soluções de Big Data

**Disciplina:** DGT2823  
**Instituição:** Polo Parangaba - Fortaleza CE
**Aluno:** Lucas Alves Vieira da Silva
**Professor/Tutor:** Maiara Heil

---

### 🎯 Objetivo do Projeto

Este projeto tem como objetivo demonstrar a utilização da linguagem **Python** e da biblioteca **Pandas** para:

- Leitura de arquivos CSV;
- Criação de subconjuntos de dados;
- Configuração de parâmetros de visualização;
- Exibição de amostras do dataset;
- Obtenção de informações gerais sobre os dados;
- Limpeza e tratamento de dados para posterior análise em aplicações de Big Data.

---

### 📂 Arquivos do Repositório

| Arquivo               | Descrição                                                               |
| --------------------- | ----------------------------------------------------------------------- |
| `dados_academia.csv`  | Conjunto de dados fornecido para o trabalho                             |
| `trabalho_bigdata.py` | Script Python contendo as microatividades e o trabalho prático completo |
| `README.md`           | Documento explicativo do projeto (este arquivo)                         |

---

### 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas**
- Ambiente sugerido: Jupyter Notebook, Google Colab ou execução local via terminal

---

### ▶️ Como Executar o Projeto

#### 1. Clonar o repositório

```bash
git clone https://github.com/alvesvslucas/Trabalho-Pratico-DGT2823.git
cd Trabalho-Pratico-DGT2823
```

#### 2. Instalar a biblioteca necessária

```bash
python -m pip install pandas
```

#### 3. Executar o script Python

```bash
python trabalho_bigdata.py
```

---

Execute na raiz: o script abre `dados_academia.csv` por caminho relativo, com separador `;`. A versão de Pandas não está fixada em um manifesto de dependências.

### 📊 Descrição do Dataset

O dataset refere-se ao registro de atividades físicas, contendo as colunas:

- `ID`
- `Duration`
- `Date`
- `Pulse`
- `Maxpulse`
- `Calories`

---

### ✅ Procedimentos Realizados

| Atividade                       | Descrição                                        |
| ------------------------------- | ------------------------------------------------ |
| Leitura do arquivo CSV          | Importação do dataset via Pandas                 |
| Criação de subconjunto de dados | Seleção de colunas específicas                   |
| Configuração de visualização    | Ajuste de linhas exibidas (max_rows)             |
| Amostragem                      | Exibição das primeiras e últimas linhas          |
| Informações do dataset          | Uso dos métodos `info()`, `describe()`           |
| Tratamento de valores nulos     | Preenchimento e remoção de dados inválidos       |
| Correção de datas               | Conversão para formato `datetime` e normalização |
| Remoção de registros inválidos  | Exclusão de linhas com datas não tratáveis       |

---

### 📑 Saída e validação

O script imprime os dados e suas etapas de tratamento no terminal; não salva um CSV de saída. Aplica preenchimento de `Calories`, conversão de `Date` e remoção de datas nulas.

A correção de datas deve ser conferida na saída: valores convertidos para `NaT` podem perder o texto original antes da tentativa de corrigir `20201226`. Esta revisão documental não executou o script nem confirmou os resultados do tratamento.

---

### 📚 Referências

- Documentação oficial Pandas: https://pandas.pydata.org/
- Documentação Python: https://docs.python.org/
- Dataset base retirado de material fornecido na disciplina

---

### 📝 Observações

Este projeto foi desenvolvido para fins acadêmicos, cumprindo integralmente o roteiro solicitado na disciplina.

---

### 📎 Licença

Este repositório é de uso acadêmico. Todos os direitos reservados ao autor.
