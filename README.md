# EXP.A04-2026
# 📦 Sistema de Gestão de Stock (Python)

Este projeto é um sistema simples de gestão de stock desenvolvido em Python, executado via linha de comandos. Permite adicionar materiais, consultar quantidades, atualizar stock e visualizar o inventário completo.

---

## 🚀 Funcionalidades

* ➕ **Adicionar Material**

  * Permite inserir um novo material no stock com uma quantidade inicial.
  * Evita duplicação de materiais já existentes.

* 🔍 **Consultar Stock**

  * Consulta a quantidade disponível de um material específico.

* 🔄 **Atualizar Stock**

  * Adiciona ou remove unidades de um material existente.
  * Valida se existe quantidade suficiente antes de remover.

* 📋 **Exibir Stock Geral**

  * Mostra todos os materiais e respetivas quantidades.

* ❌ **Sair**

  * Encerra o programa.

---

## 🧠 Estrutura do Código

O sistema é composto pelas seguintes funções:

* `adicionar_material(stock)`
  Adiciona um novo material ao dicionário `stock`.

* `consultar_stock(stock)`
  Consulta a quantidade de um material.

* `atualizar_stock(stock)`
  Atualiza a quantidade (adicionar/remover).

* `exibir_stock(stock)`
  Mostra o estado completo do stock.

* `main()`
  Controla o menu principal e a interação com o utilizador.

---

## 🛠️ Como Executar

1. Certifica-te de que tens o Python instalado (versão 3.x).
2. Guarda o código num ficheiro, por exemplo:

   ```
   stock.py
   ```
3. Executa no terminal:

   ```
   python stock.py
   ```

---

## 💾 Estrutura de Dados

O stock é armazenado num dicionário Python:

```python
stock = {
    "material": quantidade
}
```

Exemplo:

```python
stock = {
    "parafuso": 50,
    "martelo": 10
}
```

---

## ⚠️ Validações Implementadas

* Não permite adicionar materiais duplicados.
* Impede remoção de stock superior ao disponível.
* Verifica se o material existe antes de operações.

---

## 📌 Possíveis Melhorias

* Guardar o stock em ficheiro (JSON ou CSV)
* Interface gráfica (GUI)
* Sistema de login
* Relatórios de stock
* Histórico de operações

---

## 👨‍💻 Autor

Projeto desenvolvido para fins educativos.

---
