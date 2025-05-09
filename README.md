# 🤖 Chatbot Baseado em PDFs: Química Orgânica I (DIO Challenge)

## 📚 Desafio da DIO: Criando um Chatbot Inteligente

Este projeto foi desenvolvido como parte do desafio da DIO de IA Generativa. Ele é um **chatbot interativo** que responde perguntas **com base em um conteúdo de Química Orgânica**, especificamente um PDF que revisa reações, mecanismos e princípios fundamentais. O objetivo é permitir o uso de IA para estudar conteúdos técnicos de forma automatizada e prática!

---

## 🧠 Tecnologias Utilizadas

- Python
- gpt-4o
- text-embedding-3-large
- Azure Foundry

---

## 🧾 Input Real Utilizado

### 🗂 Arquivo PDF
📄 `aReview-of-Organic-Chem-I.pdf`

> Contém: Guia completo de Química Orgânica I com mecanismos, reações (SN1, SN2, E1, E2), estabilidade de intermediários, princípios de aromaticidade, Diels-Alder e mais!

---

## 💬 Exemplos de Perguntas Respondidas

> **Q:** O que torna um carbocátion mais estável?

**A:** Carbocátions são mais estáveis quando são do tipo allylic > 3º > 2º > 1º > metil > alkenil, principalmente quando há ressonância (como no caso de estruturas allylic).

---

> **Q:** Qual a diferença entre E1 e E2?

**A:** E1 é um mecanismo em dois passos via carbocátion, favorecido por nucleófilos neutros e substratos terciários. Já o E2 ocorre em um único passo com base forte, e exige orientação trans para a eliminação.

---

## 📂 Estrutura do Projeto

```bash
📁 chatbot-pdf/
├── inputs/
│   └── prompts.txt  # Perguntas e Respostas do Bot
├── pdfs/
│   └── aReview-of-Organic-Chem-I.pdf
├── app.py                     # Lógica do chatbot
└── README.md
````

---

## 🧠 Insights e Aprendizados

* Conjugação eletrônica e estabilidade impactam reatividade química — e também influenciam a busca vetorial!
* Aprendi como organizar conteúdos densos de forma pesquisável por IA.
* O uso de PDFs técnicos é excelente para criar assistentes de estudo direcionados.

---

## 🔮 Possibilidades Futuras

* Aplicar em outros temas: Farmacologia, Microbiologia, Legislação Farmacêutica.
* Criar quizzes automáticos com base no PDF.
* Treinar um LLM pequeno com os conceitos mais recorrentes da disciplina.

---

## 📸 Prints e Demonstrações

*(Adicione imagens da interface ou da resposta do bot aqui)*

---

## 👨‍🔬 Repositório

[🔗 Clique aqui para acessar no GitHub](https://github.com/Azaphz/personal-bot-dio)

---

```
