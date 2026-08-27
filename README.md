# ✈️ Sistema de Passagens Aéreas em Python

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![CLI](https://img.shields.io/badge/Interface-Console%20CLI-black?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)

Sistema de terminal completo para **gerenciamento, consulta, reserva e compra de passagens aéreas**, construído em **Python** utilizando estruturas de dados em memória (dicionários aninhados).

---

## 🛫 Funcionalidades

- 📝 **Cadastro de Voos:** Inclusão de código do voo, cidade de origem, cidade de destino, número de escalas, preço e capacidade de assentos disponíveis.
- 🔍 **Consultas Parametrizadas:**
  - Busca direta pelo código identificador do voo.
  - Busca de voos por cidade de origem.
  - Busca de voos por cidade de destino.
- 🎫 **Reserva e Venda de Passagens:**
  - Validação de disponibilidade de assentos em tempo real.
  - Decremento automático de vagas ao confirmar a compra.
  - Registro dos dados do passageiro vinculados ao bilhete emitido.
- 📊 **Listagem Geral:** Visualização consolidada de todos os voos ativos no sistema.

---

## 🧩 Estrutura de Dados

O sistema utiliza dicionários aninhados para associação rápida em memória ($O(1)$ para buscas por chave):

```python
voos[codigovoo] = {
    "origem": "campinas",
    "destino": "salvador",
    "escalas": 0,
    "preco": 450.00,
    "lugares_disponiveis": 30
}
```

---

## 🚀 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/lucaxaviers/sistema-passagens-python.git

# Acessar o diretório
cd sistema-passagens-python

# Executar o sistema
python SistemaPassagem.py
```

---

> **Desenvolvido por Lucas Rodrigues Xavier**  
> *Projeto acadêmico com foco em estruturas de dados e regras de negócio em Python.*
