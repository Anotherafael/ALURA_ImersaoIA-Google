## Alura: Imersão IA 2ª Edição

**Tema:** Recomendação de Filme.

Este projeto, desenvolvido para o desafio da Imersão IA da Alura em parceria com o Google, demonstra as capacidades do modelo de linguagem Gemini-1.0-Pro em um contexto de recomendação de filme com base em um input textual do usuário. 

## Materiais

- [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- [Google AI Studio](https://aistudio.google.com/)
- [Python-dotenv](https://pypi.org/project/python-dotenv/)

## Funcionalidades 

O projeto abrange os seguintes aspectos do Gemini-1.0-Pro:
- Embedding: Demonstra como gerar representações vetoriais de texto usando a função embedding do Gemini-1.0-Pro.
- Geração de Conteúdo: Explora a função generate_content para gerar texto coerente e criativo a partir de prompts específicos.

## Pré-requisitos

- API Key do [Google AI Studio](https://aistudio.google.com/): É necessário ter uma API Key para ter acesso à API do Gemini.
- Instalar o [Python](https://www.python.org/) ou acessar pelo [Google Colab](https://colab.google/)
- Instalar as bibliotecas no arquivo requirements.txt usando o comando 

    ```pip install -r requirements.txt.``` 


## Notas

- Por motivos de tempo de execução, o modelo atual foi limitado a 100 filmes. Mas, se quiserem fazer o embedding dos 4.800 filmes... Feel free to do so 😊.