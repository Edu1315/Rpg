# Rpg

# Pipeline de Ingestão de Big Data com MongoDB

## Objetivo
Este projeto implementa um pipeline de ingestão de dados em **MongoDB**, utilizando Python e a biblioteca `pymongo`.  
A solução foi desenvolvida como parte da avaliação final da disciplina de Desenvolvimento com linguagens disruptivas I.


---

## Tecnologias Utilizadas
- Python 3.x
- MongoDB Atlas
- Biblioteca `pymongo`,`pandas`, `numpy`, `matplotlib`, `seaborn`
- Google Colab

---

## Pipeline de Ingestão
1. **Fonte de dados**: Arquivo `RPG.csv` contendo registros em formato CSV.
2. **Ingestão**: Pelo colab, lê os dados CSV, converte para JSON e insere na coleção `personagens` no MongoDB.
3. **Armazenamento**: Dados persistidos no MongoDB.
4. **Consulta**: Operações de leitura e criação de gráficos.
5. **Saída esperada**: Dados tratados e gráficos para análise.

Fluxo resumido:  
**Fonte → Ingestão → MongoDB → Consultas → Resultados**

---

## Instruções de Execução

1. Baixar arquivo csv em: https://www.kaggle.com/datasets/jjasser/rpg-character-attributes-dataset/data
2. Criar uma pasta no Google drive com o nome RPG-Dataset e fazer upload do arquivo csv.
3. Abrir um novo notebbok no colab com o nome RPG-Dataset e colocar o arquivo .ipynb disponibilizado no projeto.
4. Agora é só seguir a ordem de códigos já definidos no arquivo .ipynb.


### 1. Clonar o repositório
```bash
git clone https://github.com/Edu1315/Rpg.git
