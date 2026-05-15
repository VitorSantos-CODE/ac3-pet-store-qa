# Pet Store

Projeto de testes automatizados com Selenium para o sistema de cadastro de produtos da Pet Store.
Trabalho desenvolvido para a disciplina de Quality Assurance.

## Sobre o projeto

Esse projeto implementa testes automatizados usando Selenium para validar o formulario de cadastro de produtos de uma Pet Store. O sistema permite cadastrar, editar, excluir e pesquisar produtos, e os testes cobrem todos esses fluxos.

A pagina testada foi criada com HTML/CSS/JavaScript puro e simula um sistema real de cadastro. Os testes rodam no Google Colab usando o `google-colab-selenium`.

## Estrutura do repositorio

```
ac3-pet-store-qa/
|-- notebooks/
|   |-- AC3-PET-STORE.ipynb      # notebook principal com todos os testes
|-- tests/
|   |-- test_cadastro.py         # testes unitarios separados (referencia)
|-- docs/
|   |-- plano_de_testes.md       # plano de testes detalhado
|   |-- casos_de_teste.md        # casos de teste documentados
|-- assets/
|   |-- (prints dos testes)
|-- requirements.txt
|-- .gitignore
|-- README.md
```

## Como rodar

1. Abra o arquivo `notebooks/AC3-PET-STORE.ipynb` no Google Colab
2. Execute todas as celulas em ordem
3. Os testes vao rodar automaticamente

Ou clone o repositorio e execute no Colab:

```
https://colab.research.google.com/github/VitorSantos-CODE/ac3-pet-store-qa/blob/main/notebooks/AC3-PET-STORE.ipynb
```

## Tecnologias usadas

- Python 3
- Selenium WebDriver
- Google Colab Selenium
- HTML/CSS/JavaScript (pagina de teste)

## Testes implementados

- Cadastro de produto com dados validos
- Cadastro com campos vazios (validacao)
- Cadastro com ID duplicado
- Cadastro com valor negativo
- Cadastro com estoque negativo
- Pesquisa de produto por nome/ID
- Edicao de produto existente
- Exclusao de produto

## Aluno

● Giovani Ribeiro Lima RA: 94107
● Vitor Edmilson Duarte Santos - 104811
● Pedro Henrique Cervinski Uchoa - 96914
