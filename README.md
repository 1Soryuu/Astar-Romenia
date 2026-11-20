# 🧠 Busca A* em Python — Mapa da Romênia

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-Versionamento-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repositório-181717?style=for-the-badge&logo=github&logoColor=white)

## 📖 Sobre o Projeto

Este repositório apresenta a implementação do algoritmo de busca **A* (A-Estrela)** utilizando a linguagem Python, desenvolvido como atividade acadêmica da disciplina de **Engenharia de Software — FATEC**.

O projeto tem como objetivo encontrar o caminho de menor custo entre as cidades de **Arad e Bucareste**, utilizando o mapa rodoviário da Romênia como exemplo prático.

O desenvolvimento é dividido em seis fases, permitindo compreender progressivamente as estruturas de dados, os cálculos heurísticos e o funcionamento do algoritmo.

## 🎯 Objetivos

- Compreender o funcionamento do algoritmo A*.
- Aplicar conceitos de grafos e estruturas de dados.
- Trabalhar com dicionários, listas, tuplas e funções em Python.
- Implementar cálculos de custo e heurísticas.
- Utilizar Git e GitHub para versionamento.
- Desenvolver o algoritmo de forma incremental.

## ⚙️ Funcionamento do Algoritmo

O algoritmo A* utiliza uma função de avaliação para selecionar os caminhos mais promissores até o destino.

A função é definida por:

**f(n) = g(n) + h(n)**

Onde:

- **g(n):** custo real acumulado desde a origem até o nó atual.
- **h(n):** estimativa do custo restante até o destino.
- **f(n):** custo total estimado do caminho.

O algoritmo mantém uma fronteira de nós disponíveis e seleciona aquele com o menor valor de `f(n)`.

## 🗺️ Resultado Esperado

Para o percurso entre Arad e Bucareste, o caminho de menor custo apresentado no material é:

**Arad → Sibiu → Rimnicu Vilcea → Pitesti → Bucharest**

**Distância total: 418 km**

Esse resultado é utilizado como referência para verificar o funcionamento da implementação.

## 📂 Estrutura do Projeto

```text
astar-romenia/
│
├── README.md
├── .gitignore
│
├── mapa.py
├── fase1_explorar.py
├── fase2_caminhos.py
├── fase3_fronteira.py
├── fase4_expandir.py
├── fase5_busca.py
│
└── a_estrela.py
```

## 🚀 Etapas de Desenvolvimento

| Fase | Descrição |
|---|---|
| 0 | Configuração do ambiente, Git e GitHub |
| 1 | Exploração dos dados do mapa da Romênia |
| 2 | Funções, custos de caminhos e heurísticas |
| 3 | Construção dos nós e gerenciamento da fronteira |
| 4 | Implementação da expansão de nós |
| 5 | Desenvolvimento do laço principal da busca A* |
| 6 | Integração e execução do algoritmo completo |

Cada fase possui seu próprio arquivo Python, permitindo acompanhar a evolução do projeto.

## 🛠️ Tecnologias Utilizadas

- **Python 3:** implementação do algoritmo.
- **Git:** controle de versões.
- **GitHub:** hospedagem do código-fonte.
- **Visual Studio Code:** ambiente de desenvolvimento.
- **UML:** representação dos fluxos e estruturas do programa.

## 💻 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/1Soryuu/astar-romenia.git
```

### 2. Acesse o diretório

```bash
cd astar-romenia
```

### 3. Execute o programa principal

```bash
python a_estrela.py
```

**Observação:** a execução completa depende da implementação dos arquivos previstos nas fases do projeto.

## 📚 Conceitos Trabalhados

Durante o desenvolvimento, são abordados conceitos fundamentais da programação e da inteligência artificial:

- Grafos e representação de caminhos.
- Estruturas de dados em Python.
- Algoritmos de busca informada.
- Funções heurísticas.
- Estruturas condicionais e de repetição.
- Modularização e reutilização de código.
- Versionamento e organização de projetos.

## 📖 Referência Bibliográfica

RUSSELL, Stuart; NORVIG, Peter. **Inteligência Artificial**. 3. ed. Rio de Janeiro: Elsevier, 2013. Capítulo 3.

## 👨‍💻 Autor

**Victor Yamada Miyashiro**

Estudante de Análise e Desenvolvimento de Sistemas — FATEC.

GitHub: [@1Soryuu](https://github.com/1Soryuu)

---

*Projeto desenvolvido para fins acadêmicos e de aprendizagem em Engenharia de Software.*
