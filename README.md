# Mapa de Empatia

Este projeto é uma ferramenta interativa desenvolvida para auxiliar alunos do curso **Técnico em Informática para Internet** nas etapas de Imersão e Definição da Unidade Curricular de Projeto de Inovação.

O objetivo é facilitar a criação de artefatos de **Design Thinking**, permitindo que o usuário mapeie a persona de forma visual e exporte o resultado como uma imagem (.png) para apresentações e portfólios.

## 🛠️ Tecnologias Utilizadas

* **HTML5/CSS3:** Estruturação e estilização responsiva.
* **JavaScript (Vanilla):** Lógica de manipulação de dados e interface.
* **html2canvas:** Biblioteca utilizada para converter o elemento DOM em uma imagem de alta qualidade.

## 🚀 Como usar

1. Clone ou baixe o repositório e abra `index.html` em um navegador.
2. Preencha os quadrantes superiores com base nas observações de campo (Imersão).
3. Identifique os obstáculos (Dores) e as metas (Ganhos) do seu usuário.
4. Clique no botão **"Salvar como Imagem"**.

---
Desenvolvido para apoio às aulas de Informática para Internet - SENAI.


## Estrutura e dependências

A interface, os estilos e a lógica estão em `index.html`. O html2canvas 1.4.1 é carregado por CDN; é necessário acesso à internet para carregar a biblioteca de exportação. Exporte o resultado antes de fechar ou recarregar a página, pois os campos não têm salvamento automático.

## Ferramentas relacionadas

- [Lean Canvas](https://github.com/romulogonzaga/lean-canvas): organize o modelo de negócio.
- [Project Model Canvas](https://github.com/romulogonzaga/project-model-canvas): planeje a execução do projeto.
