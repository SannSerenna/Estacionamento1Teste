
# EM CONSTRUÇÃO!
# 🚗 Sistema de Estacionamento - Desafio DIO .NET

Este projeto foi desenvolvido como parte do **Desafio de Projeto** do módulo de Fundamentos da trilha .NET da [Digital Innovation One (DIO)](https://www.dio.me). O objetivo é construir um sistema simples para gerenciar veículos em um estacionamento, utilizando conceitos básicos de programação orientada a objetos com C#.

---

## 📘 Descrição

O sistema permite:

- Cadastrar veículos que chegam ao estacionamento.
- Remover veículos, calculando o valor total a ser pago.
- Listar todos os veículos atualmente estacionados.

---

## 🧱 Estrutura do Projeto

### 🔹 Classe `Estacionamento`

A classe principal do sistema, responsável pela lógica de negócio.

#### Atributos:

- `precoInicial`: valor fixo cobrado ao estacionar.
- `precoPorHora`: valor cobrado por hora de permanência.
- `veiculos`: lista de placas dos veículos estacionados.

#### Métodos:

- `AdicionarVeiculo()`: adiciona uma placa à lista de veículos.
- `RemoverVeiculo()`: calcula o valor total com base nas horas e remove a placa.
- `ListarVeiculos()`: exibe todas as placas dos veículos estacionados.

---

### 🔹 Arquivo `Program.cs`

Contém o menu interativo que permite ao usuário utilizar o sistema via terminal.

#### Funcionalidades:

```text
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar
