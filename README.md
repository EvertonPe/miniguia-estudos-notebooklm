# 🎲 Miniguia de Estudos: RPG de Mesa com NotebookLM

## 📝 Contexto e Objetivos
Este repositório foi criado para o desafio de aprendizagem ativa da DIO. O objetivo principal é utilizar o **NotebookLM** como uma ferramenta de curadoria, síntese e estudo aprofundado sobre o universo dos **RPGs de Mesa (Role-Playing Games)**, focando na produção de conteúdo e sistemas do cenário brasileiro.

### Objetivos de Estudos:
1. Compreender a estrutura de criação de cenários e regras no cenário nacional.
2. Dominar técnicas de improvisação e condução de jogo (Mestrado) utilizando ferramentas digitais.
3. Consolidar um glossário de termos essenciais para novos jogadores.

---

## 📚 Curadoria de Fontes (Conteúdo Brasileiro)
As fontes abaixo são abertas, gratuitas e foram utilizadas para alimentar a base de conhecimento do NotebookLM:

1. **Tormenta20 - Guia de Introdução (Jambô Editora)**
   * *O que é:* O maior RPG do Brasil. Este guia traz as regras básicas de teste, atributos e o conceito do jogo.
   * *Link:* https://jamboeditora.com.br/wp-content/uploads/2026/06/RT20-28.pdf
2. **Artigo: "O RPG na Educação Brasileira" (SciELO / Periódicos)**
   * *O que é:* Um olhar acadêmico nacional sobre como o RPG estimula a escrita, matemática e cooperação.
   * *Link:* https://www.scielo.br/j/tce/a/LC5fr3xYHZv3mzVDP6tsHVx/?format=pdf&lang=pt
3. **Sistemas Independentes Nacionais (Ex: Mighty Blade)**
   * *O que é:* Um RPG de fantasia medieval 100% brasileiro e gratuito. O manual básico em PDF é perfeito para análise de sistemas mais leves.
   * *Link:* https://coisinhaverde.com.br/mightyblade/files/guiadetebryn.pdf

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Aqui está o registro de como conversei com a IA dentro do NotebookLM para extrair o melhor conhecimento, enfrentando alucinações e refinando os resultados.

### Prompt 1: O Teste Inicial (Resultado Genérico)
* **O que perguntei:** `Quais são as regras básicas do RPG de acordo com as fontes?`
* **Resposta da IA:** Deu uma resposta genérica citando Dungeons & Dragons (D&D), ignorando que eu tinha subido o PDF de Tormenta20 e Mighty Blade.
* **Cicatriz/Ajuste:** Percebi que o NotebookLM precisa de direcionamento estrito baseado nas fontes carregadas para não "olhar" para o conhecimento geral da internet.

### Prompt 2: O Refinamento (Resultado Nota 10)
* **O que perguntei:** `Baseando-se estritamente nos guias de Tormenta20 e Mighty Blade que fiz upload, crie uma tabela comparativa mostrando: 1) Como é feito um teste de atributo em cada sistema; 2) Qual o dado principal utilizado.`
* **Resposta da IA:** Perfeita. Identificou que Tormenta20 usa $1d20 + modificadores$ contra uma dificuldade, enquanto Mighty Blade usa $3d6$.
* **Lição aprendida:** Sempre use termos como "baseando-se nas fontes carregadas" ou "cite o documento X".

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📌 Resumos Estruturados

#### 1. A Estrutura do Jogo
O RPG de mesa se divide em duas frentes: o **Mestre/Narrador** (que cria o mundo, os desafios e controla os coadjuvantes) e os **Jogadores** (que controlam os protagonistas da história). O sucesso das ações dramáticas é decidido através da soma de atributos do personagem, bônus de treinamento e o resultado de uma rolagem de dados.

#### 2. O Cenário Nacional
O Brasil possui um mercado maduro de RPG. Enquanto os sistemas internacionais focam muito em regras complexas de combate tático, o design de jogos brasileiro (como visto em sistemas independentes) costuma valorizar a acessibilidade de regras e a riqueza cultural na narrativa.

### 🗂️ Glossário de Conceitos Aprendidos
* **NPC / PNJ:** *Non-Player Character* (Personagem Não Jogável). Todos os personagens controlados pelo Mestre (vendedores, vilões, reis).
* **XP (Experience Points):** Pontos de experiência acumulados ao superar desafios, usados para evoluir o nível do personagem.
* **Homebrew:** Conteúdo modificado ou criado do zero por fãs (regras, raças, classes) que não faz parte do livro oficial.
* **Rolagem Aberta / Crítico:** Quando o dado tira o seu valor máximo (ex: 20 em um dado de 20 faces), gerando um sucesso automático ou dano multiplicado.

### 🔄 Prompts Reutilizáveis para Revisão
Copie e cole estes prompts no seu NotebookLM sempre que quiser revisar este assunto no futuro:

* `Gere 3 perguntas de múltipla escolha sobre o sistema de combate das fontes para testar meu conhecimento.`
* `Atue como um Mestre de RPG veterano. Com base nos textos de narrativa que enviei, crie um gancho de aventura de suspense que se passe em uma vila medieval brasileira.`
* `Explique o conceito de "Dificuldade de Teste (CD)" para um jogador que nunca jogou RPG na vida, usando uma analogia simples do dia a dia.`
