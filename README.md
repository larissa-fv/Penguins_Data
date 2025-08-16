
#  Penguins Data Analysis 🐧

## **Descrição**

Este projeto realiza uma **análise exploratória de dados (EDA)** do dataset `penguins` disponível na biblioteca **Seaborn** do Python. O objetivo é estudar as diferenças entre espécies de pinguins (Adelie, Gentoo, Chinstrap), analisando medidas corporais como:

* Comprimento do bico (`comprimento_bico_mm`)
* Profundidade do bico (`profundidade_bico_mm`)
* Tamanho da nadadeira (`nadadeira_mm`)
* Peso (`peso_g`)

Além disso, o projeto explora o **dimorfismo sexual** e as relações entre essas variáveis.

---

## **Conteúdo do Projeto**

* **Análise Descritiva**: resumo estatístico, contagem por espécie e sexo
* **Visualizações**:

Tradução das Colunas

Para facilitar a leitura e compreensão do dataset, os nomes das colunas foram alterados para o idioma português. Abaixo estão as modificações realizadas:

| Coluna original     | Coluna em português    | Descrição                                      |
| ------------------- | ---------------------- | ---------------------------------------------- |
| `species`           | `especie`              | Espécie do pinguim (Adelie, Gentoo, Chinstrap) |
| `island`            | `ilha`                 | Ilha de origem do pinguim                      |
| `bill_length_mm`    | `comprimento_bico_mm`  | Comprimento do bico em milímetros              |
| `bill_depth_mm`     | `profundidade_bico_mm` | Profundidade do bico em milímetros             |
| `flipper_length_mm` | `nadadeira_mm`         | Comprimento da nadadeira em milímetros         |
| `body_mass_g`       | `peso_g`               | Peso do pinguim em gramas                      |
| `sex`               | `sexo`                 | Sexo biológico do pinguim (Masculino/Feminino) |


**Objetivo:**

Tornar os gráficos, análises e interpretações mais legíveis e intuitivos para falantes de português.

Facilitar a explicação e a documentação das análises no notebook.

  * Histogramas e boxplots
  * Gráficos de dispersão 2D e 3D interativos (Plotly)
  * Pairplots e FacetGrids para explorar relações entre variáveis
* **Regressão Linear**: análise da relação entre tamanho da nadadeira e peso
* **Interatividade**: gráficos 3D interativos para explorar padrões de espécies e sexo

---

## **Principais Resultados**

* Machos apresentam **peso e tamanho de nadadeira maiores que fêmeas** (dimorfismo sexual).
* A espécie **Gentoo** possui nadadeiras maiores e peso acima da média em relação a Adelie e Chinstrap.
* A nadadeira é um **bom preditor do peso**, explicando aproximadamente 76% da variação.
* As visualizações 3D permitem identificar padrões complexos entre **peso, nadadeira e comprimento do bico**, diferenciando espécies e sexo.

---

## **Tecnologias e Bibliotecas**

* Python 3.x
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
3. Execute o notebook `Penguins_Data.ipynb` no **Jupyter Notebook** ou **JupyterLab**.

---

## **Observações**

* Dados do **dataset `penguins`** são carregados diretamente da biblioteca Seaborn.
* O projeto inclui limpeza de dados e remoção de valores nulos para garantir a qualidade das análises.
* Todos os gráficos possuem legendas, cores e interatividade para facilitar a interpretação.

  ## Conclusão:

  O dataset Penguins evidencia padrões claros de dimorfismo sexual e diferenças entre espécies.
Medidas corporais como nadadeira, peso e comprimento do bico são fortemente correlacionadas, permitindo prever características de um pinguim a partir de outra.
As análises interativas e regressões reforçam a compreensão de como essas variáveis se relacionam, oferecendo uma visão completa do perfil biométrico das espécies estudadas.
