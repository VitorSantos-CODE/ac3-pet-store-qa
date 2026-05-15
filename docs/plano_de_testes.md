# Plano de Testes - Sistema Pet Store

## 1. Introducao

Este documento descreve o plano de testes para o sistema de cadastro de produtos da Pet Store.

**Projeto:** AC3 - Qualidade de Software  
**Aluno:** Vitor Santos  
**Semestre:** 5 semestre - ADS  

---

## 2. Escopo

O sistema testado e um formulario web de cadastro de produtos que permite:

- Cadastrar novos produtos (nome, ID, valor, estoque)
- Editar produtos ja cadastrados
- Excluir produtos
- Pesquisar produtos por nome ou ID

---

## 3. Objetivos

- Garantir que o cadastro aceita apenas dados validos
- Verificar que campos obrigatorios sao validados
- Confirmar que IDs duplicados sao rejeitados
- Testar os fluxos de edicao e exclusao
- Validar a funcionalidade de pesquisa

---

## 4. Tecnica utilizada

Testes automatizados com Selenium WebDriver rodando no Google Colab.

---

## 5. Criterios de aceite

- Todos os testes positivos devem retornar mensagem de sucesso
- Todos os testes negativos devem retornar mensagem de erro adequada
- Nenhum dado invalido deve ser aceito pelo sistema
