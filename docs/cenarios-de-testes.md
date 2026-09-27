# Cenários de Teste — SauceDemo

## 1. Login

| ID     | Cenário                                    |
| ------ | ------------------------------------------ |
| CT-001 | Realizar login com usuário e senha válidos |
| CT-002 | Realizar login com senha inválida          |
| CT-003 | Realizar login com usuário inválido        |
| CT-004 | Tentar realizar login com os campos vazios |
| CT-005 | Realizar login com usuário bloqueado       |

## 2. Produtos

| ID     | Cenário                                 |
| ------ | --------------------------------------- |
| CT-006 | Verificar exibição da lista de produtos |
| CT-007 | Verificar detalhes de um produto        |
| CT-008 | Adicionar produto ao carrinho           |
| CT-009 | Remover produto                         |
| CT-010 | Ordenar produtos por preço crescente    |
| CT-011 | Ordenar produtos por preço decrescente  |
| CT-012 | Ordenar produtos por nome A-Z           |
| CT-013 | Ordenar produtos por nome Z-A           |

## 3. Carrinho

| ID     | Cenário                                     |
| ------ | ------------------------------------------- |
| CT-014 | Acessar o carrinho                          |
| CT-015 | Verificar produto adicionado ao carrinho    |
| CT-016 | Remover produto do carrinho                 |
| CT-017 | Continuar comprando após acessar o carrinho |
| CT-018 | Avançar do carrinho para o checkout         |

## 4. Checkout

| ID     | Cenário                                               |
| ------ | ----------------------------------------------------- |
| CT-019 | Realizar checkout com dados válidos                   |
| CT-020 | Tentar checkout sem informar o nome                   |
| CT-021 | Tentar checkout sem informar o sobrenome              |
| CT-022 | Tentar checkout sem informar o CEP                    |
| CT-023 | Verificar informações do resumo da compra             |
| CT-024 | Finalizar uma compra                                  |
| CT-025 | Retornar à página de produtos após finalizar a compra |

## Resumo

**Total de cenários:** 25

**Módulos:**

* Login: 5
* Produtos: 8
* Carrinho: 5
* Checkout: 7
