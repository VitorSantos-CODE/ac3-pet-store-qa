# Casos de Teste - Pet Store

## CT-001: Cadastro com dados validos

**Pre-condicao:** Sistema aberto, sem produtos cadastrados  
**Entrada:** Nome="Areia pa kh", ID="7", Valor="19.90", Estoque="500"  
**Acao:** Preencher campos e clicar em Enviar  
**Resultado esperado:** Mensagem de sucesso com os dados do produto  
**Status:** PASSOU

---

## CT-002: Cadastro com campos vazios

**Pre-condicao:** Sistema aberto  
**Entrada:** Todos os campos vazios  
**Acao:** Clicar em Enviar sem preencher nada  
**Resultado esperado:** Mensagem de erro "todos os campos sao obrigatorios"  
**Status:** PASSOU

---

## CT-003: Cadastro com ID duplicado

**Pre-condicao:** Produto com ID="12" ja cadastrado  
**Entrada:** Tentar cadastrar outro produto com ID="12"  
**Acao:** Preencher campos com ID repetido e clicar em Enviar  
**Resultado esperado:** Mensagem de erro informando ID ja cadastrado  
**Status:** PASSOU

---

## CT-004: Cadastro com valor negativo

**Pre-condicao:** Sistema aberto  
**Entrada:** Nome="Produto Negativo", ID="88", Valor="-50", Estoque="10"  
**Acao:** Preencher campos com valor negativo e clicar em Enviar  
**Resultado esperado:** Mensagem de erro "o valor deve ser maior que zero"  
**Status:** PASSOU

---

## CT-005: Cadastro com estoque negativo

**Pre-condicao:** Sistema aberto  
**Entrada:** Nome="Produto Invalido", ID="30", Valor="10.00", Estoque="-5"  
**Acao:** Preencher campos com estoque negativo e clicar em Enviar  
**Resultado esperado:** Mensagem de erro "o estoque nao pode ser negativo"  
**Status:** PASSOU

---

## CT-006: Pesquisa de produto

**Pre-condicao:** Produtos A e B cadastrados  
**Entrada:** Campo de pesquisa = "Produto B"  
**Acao:** Digitar no campo de pesquisa  
**Resultado esperado:** Apenas Produto B visivel na lista  
**Status:** PASSOU

---

## CT-007: Edicao de produto

**Pre-condicao:** Produto "Produto Teste" com ID="123" cadastrado  
**Acao:** Clicar em Editar, alterar nome/valor/estoque, confirmar  
**Resultado esperado:** Mensagem de sucesso e dados atualizados na lista  
**Status:** PASSOU

---

## CT-008: Exclusao de produto

**Pre-condicao:** Produto "Produto Teste" com ID="123" cadastrado  
**Acao:** Clicar em Excluir e confirmar  
**Resultado esperado:** Produto removido da lista, mensagem de lista vazia  
**Status:** PASSOU
