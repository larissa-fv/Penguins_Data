
# 🐧 Penguins Data Analysis

---

## **Descrição**

Este projeto realiza uma **análise exploratória de dados** do dataset `penguins` disponível na biblioteca **Seaborn** do Python. O objetivo é investigar diferenças morfológicas entre as espécies de pinguins (**Adelie, Gentoo, Chinstrap**) e explorar relações entre suas medidas corporais, incluindo:

* Comprimento do bico (`comprimento_bico_mm`)
* Profundidade do bico (`profundidade_bico_mm`)
* Comprimento da nadadeira (`nadadeira_mm`)
* Peso (`peso_g`)

Além disso, o projeto aborda o **dimorfismo sexual** e as interações entre variáveis morfológicas.

---

## **Tradução das Colunas**

Para tornar o dataset mais legível, os nomes das colunas foram **traduzidos para português**, mantendo a consistência e clareza nos gráficos e análises:

| Coluna original     | Coluna em português    | Descrição                                      |
| ------------------- | ---------------------- | ---------------------------------------------- |
| `species`           | `especie`              | Espécie do pinguim (Adelie, Gentoo, Chinstrap) |
| `island`            | `ilha`                 | Ilha de origem do pinguim                      |
| `bill_length_mm`    | `comprimento_bico_mm`  | Comprimento do bico em milímetros              |
| `bill_depth_mm`     | `profundidade_bico_mm` | Profundidade do bico em milímetros             |
| `flipper_length_mm` | `nadadeira_mm`         | Comprimento da nadadeira em milímetros         |
| `body_mass_g`       | `peso_g`               | Peso do pinguim em gramas                      |
| `sex`               | `sexo`                 | Sexo biológico do pinguim (Masculino/Feminino) |

**Objetivos desta modificação:**

* Facilitar interpretação de gráficos e análises em português.
* Permitir documentação mais clara e didática no notebook.

---

## **Conteúdo do Projeto**

* **Análise Descritiva:** resumo estatístico, contagem por espécie e sexo.
* **Visualizações:**

  * Histogramas e boxplots
  * Gráficos de dispersão 2D e 3D interativos (Plotly)
  * Pairplots e FacetGrids para explorar relações entre variáveis [ainda será implementado]
* **Regressão Linear:** avaliação da relação entre tamanho da nadadeira e peso.
* **Análises Interativas:** exploração de padrões entre espécies e sexo em gráficos 3D.

---

## **Principais Resultados**

* Machos apresentam **peso e tamanho de nadadeira superiores às fêmeas**, evidenciando **dimorfismo sexual**.
* A espécie **Gentoo** se destaca com **nadadeiras maiores e peso acima da média**, em comparação com Adelie e Chinstrap.
* O tamanho da nadadeira é um **preditor significativo do peso** (R² ≈ 0.76).
* Gráficos 3D interativos permitem identificar padrões complexos entre **peso, nadadeira e comprimento do bico**, diferenciando espécies e sexo.

---

## **Tecnologias e Bibliotecas**

* Python 3.12.6
* Pandas
* Seaborn
* Plotly
* Statsmodels
* Matplotlib

---

## **Como Executar**

1. Clone o repositório:

```bash
git clone https://github.com/larissa-fv/Penguins_Data.git
```

2. Instale as dependências:

```bash
pip install pandas seaborn plotly statsmodels matplotlib
```

3. Abra e execute o notebook `Penguins_Data.ipynb` no **Jupyter Notebook** ou **JupyterLab**.

---

## **Observações**

* O dataset `penguins` é carregado diretamente da biblioteca Seaborn.
* Foi realizada **limpeza de dados** e remoção de valores nulos para garantir a qualidade da análise.
* Todos os gráficos possuem **legendas, cores e interatividade** para facilitar interpretação.

---

## **Conclusão**

O dataset evidencia padrões claros de **dimorfismo sexual** e **diferenças entre espécies**.
Medidas corporais como nadadeira, peso e comprimento do bico são fortemente correlacionadas, permitindo prever características de um pinguim a partir de outra.
As análises exploratórias, visualizações interativas e regressões reforçam a compreensão do perfil biométrico das espécies estudadas, fornecendo insights consistentes para estudos comparativos de morfologia de pinguins.

Link para visualização dos graficos interativos: https://colab.research.google.com/drive/1F6X5Hvnm3vA94Jj8nUJuYHzzgzidciUG?usp=sharing
---

