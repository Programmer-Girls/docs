# CHATGPT O1 RESEARCH - Roteiro do Evento – Dia Internacional das Mulheres em TI (3 horas)

**Descrição:** Evento comunitário em celebração ao Dia Internacional das Mulheres, focado em apoiar mulheres iniciando ou evoluindo na área de TI. Serão **3 blocos principais**: Introdução (apresentação e recursos no Notion), Code-Along (construção conjunta de uma página web simples) e Q&A (perguntas e respostas sobre tecnologia, carreira e programação). O ambiente deve ser acolhedor, motivador e acessível para iniciantes, encorajando a participação ativa de todas.

---

## Estrutura Geral e Cronograma do Evento

- **Bloco 1 (0:00 – 0:20)** – **Boas-vindas & Introdução:** Apresentação dos organizadores, objetivos do evento e introdução ao guia de recursos no **Notion** sobre como começar em programação e escolher áreas de atuação em TI.

- **Bloco 2 (0:20 – 1:30)** – **Code-Along (HTML/CSS):** Atividade prática *mão na massa* onde todos constroem juntos uma página web simples usando **HTML e CSS puros (vanilla)**. Passo a passo detalhado, com explicações claras e tempo para tirar dúvidas durante o processo, garantindo acessibilidade para iniciantes.

- **Intervalo (1:30 – 1:40)** – **Pausa rápida:** 5-10 minutos para descanso, alongar, beber água e processar o aprendizado antes do Q&A.

- **Bloco 3 (1:40 – 2:40)** – **Q&A (Perguntas e Respostas):** Sessão interativa para esclarecer dúvidas sobre tecnologia, carreira em TI, aprendizado de programação, etc. Moderação cuidadosa para que todas se sintam confortáveis em perguntar. Inclui fechamento e agradecimentos nos minutos finais.

*(Obs.: Os horários são estimados para um evento de até 3 horas. Podem ser ajustados conforme necessidade, mantendo-se a ordem dos blocos.)*

---

## Bloco 1: Boas-vindas e Introdução ao Notion (0:00 – 0:20)

**Objetivos:**
- Quebrar o gelo, apresentar a equipe organizadora, contextualizar o evento (Dia Internacional das Mulheres e a importância de apoiar mulheres na TI).
- Mostrar recursos úteis aos participantes (página do **Notion** com dicas de estudo e áreas de atuação).

### Atividades e Duração

1. **Boas-vindas & Contextualização (5 min)**
   - O anfitrião dá as boas-vindas a todas.
   - Destaque o propósito do evento: criar uma comunidade de apoio para mulheres iniciantes em tecnologia.
   - Mencione brevemente a importância do Dia Internacional das Mulheres como inspiração para impulsionar a presença feminina na TI.
   - Estabeleça um tom **acolhedor e motivador**.

2. **Apresentação dos Organizadores (5 min)**
   - Cada organizador(a) se apresenta rapidamente (nome, atuação/empresa, e motivação pessoal).
   - Para engajar, peça às participantes que compartilhem seu nome e uma palavra que represente o que esperam do evento.

3. **Introdução à Plataforma Notion (10 min)**
   - Apresente a página do **Notion** com informações sobre **como iniciar em programação** e **como escolher uma área de atuação em TI**.
   - Explique a estrutura do Notion:
     - Seção "Por onde começar": cursos e tutoriais básicos.
     - Seção "Áreas de Atuação": descrições curtas de áreas (Front-End, Back-End, Data Science, etc.).
     - Seção "Comunidade e Dicas": eventos, comunidades online, depoimentos.
   - Mostre como navegar e destaque 1 ou 2 recursos-chave.
   - Compartilhe o link e incentive a exploração posterior.
   - **Engajamento:** pergunte quem já teve contato com programação. Adeque a expectativa do code-along.
   - Reforce que o Notion ficará disponível após o evento como material de apoio.

4. **Transição para o Code-Along**
   - Explique brevemente o que virá a seguir: *"Agora vamos colocar a mão na massa!"*
   - Ressalte que haverá tempo para perguntas e que ninguém ficará para trás.

**Técnicas de Engajamento no Bloco 1**
- Use um tom **entusiasmado e inclusivo**.
- Valorize a participação ativa desde o começo e estabeleça um ambiente seguro.

---

## Bloco 2: Code-Along – Construindo uma Página HTML e CSS (0:20 – 1:30)

**Objetivos:**
- Ensinar na prática conceitos básicos de desenvolvimento web.
- Construir conjuntamente (ao vivo) uma página HTML e CSS simples.
- Manter alto nível de engajamento com explicações passo a passo.

### Formato

- O apresentador vai codando ao vivo e compartilhando a tela.
- Participantes codificam simultaneamente.
- Projeto proposto: **Página de apresentação pessoal simples** (HTML + CSS).

### Passo a Passo do Code-Along

1. **Setup Inicial (≈5 min)**
   - Verifique se todas têm um editor de texto ou plataforma online (CodePen, CodeSandbox).
   - Crie um arquivo `index.html`.

2. **Estrutura Básica do HTML (≈10 min)**
   - Explique cada parte do boilerplate HTML:
     ```html
     <!DOCTYPE html>
     <html lang="pt-br">
       <head>
         <meta charset="UTF-8" />
         <title>Minha Página</title>
       </head>
       <body>
         <!-- Conteúdo da página virá aqui -->
       </body>
     </html>
     ```
   - Oriente a abrir o arquivo no navegador, garantindo que todas acompanhem.

3. **Adicionando Conteúdo HTML (≈10 min)**
   - Adicione um `<h1>` (título principal).
   - Adicione um `<p>` (parágrafo) com texto sobre o evento ou apresentação pessoal.
   - (Opcional) Insira uma imagem (`<img>`). Explique atributos `src` e `alt`.
   - Peça para todos salvarem e recarregarem no navegador para verem o resultado.

4. **Introdução ao CSS (≈5 min)**
   - Crie um arquivo `style.css`.
   - No `<head>` do `index.html`, linke o CSS:
     ```html
     <link rel="stylesheet" href="style.css" />
     ```
   - Cheque se está tudo funcionando (nenhum erro de nome de arquivo).

5. **Aplicando Estilos Básicos (≈15 min)**
   - Estilize `body`:
     ```css
     body {
       font-family: Arial, sans-serif;
       background-color: #f0f0f0;
       margin: 20px;
     }
     ```
   - Estilize `h1`:
     ```css
     h1 {
       color: #5a2d82;
       text-align: center;
     }
     ```
   - Estilize `p`:
     ```css
     p {
       font-size: 1.1em;
       line-height: 1.5;
     }
     ```
   - Se tiver imagem, demonstre regras para `<img>` (centralizar, `max-width`, etc.).
   - Faça pausas para que todas possam acompanhar.

6. **Revisão do Código e Finalização (≈5 min)**
   - Recapitule o que foi construído.
   - Mostre o código completo HTML e CSS lado a lado.
   - Compartilhe os arquivos finais (GitHub, Gist, Notion, etc.).
   - Parabenize as participantes.
   - Prepare para o intervalo.

---

## Intervalo (1:30 – 1:40)

- Pausa rápida de 5 a 10 minutos.
- Oriente o horário de retorno para o Q&A.

---

## Bloco 3: Perguntas e Respostas (Q&A) e Encerramento (1:40 – 2:40)

**Objetivos:**
- Abrir espaço para dúvidas sobre o que foi abordado (HTML, CSS, Notion, etc.).
- Dar suporte sobre questões gerais de tecnologia e carreira.
- Criar um momento de troca de experiências.

### Dinâmica da Sessão

1. **Reabertura pós-intervalo (2 min)**
   - Dê as boas-vindas de volta.
   - Reforce que agora é o momento de perguntar *qualquer coisa* relacionada a TI.

2. **Quebra-gelo de Perguntas (3 min)**
   - Para aquecer, o moderador pode fazer 1 ou 2 perguntas típicas de iniciantes.
   - Organizadores respondem brevemente, mostrando abertura e informalidade.

3. **Abertura para Perguntas do Público (50+ min)**
   - Participantes podem perguntar livremente (oralmente ou via chat).
   - O moderador organiza a ordem de fala e direciona as perguntas para quem puder responder.
   - Estimule a participação, reforce que não há dúvidas bobas.
   - Mantenha respostas claras e objetivas.
   - Se a conversa se prolongar, lembre-se de administrar o tempo para dar voz a todos.

4. **Encerramento e Mensagem Final (5 min)**
   - Agradeça a todas pela presença e participação.
   - Recapitule os principais aprendizados do dia.
   - Sugira próximos passos:
     - Explorar o Notion e continuar praticando HTML/CSS.
     - Entrar em grupos/comunidades de suporte.
   - Deixe uma mensagem inspiradora pelo Dia Internacional das Mulheres, reforçando a importância de mais mulheres na tecnologia.
   - Tire uma foto conjunta (se presencial) ou capture a tela (se online), caso todas concordem.
   - Convide quem quiser ficar para um bate-papo informal depois do horário.
   - Finalize com *"Muito obrigada e até a próxima!"*.

---

## Dicas Gerais para Moderação do Q&A e Engajamento

- **Ambiente Seguro:** Reforce regras de respeito e inclusão.
- **Empatia e Paciência:** Trate cada pergunta com seriedade.
- **Envolvimento Coletivo:** Permita que outras mentoras respondam também.
- **Leitura do Clima:** Interrompa respostas muito extensas se necessário; deixe espaço para várias perguntas.
- **Tempo para Todos:** Evite que uma pessoa monopolize o microfone.
- **Feedback Final:** Se possível, colete feedback rápido no fim (um formulário ou reações).
- **Flexibilidade:** Ajuste o cronograma conforme o ritmo do grupo.

---

**Conclusão:**
Seguindo esse roteiro, o evento terá um fluxo **claro, acessível e envolvente**, oferecendo às participantes:
- **Conhecimento prático** (HTML e CSS).
- **Orientação inicial** (Notion com recursos e áreas de atuação).
- **Espaço aberto** para perguntas e compartilhamento de experiências.

O mais importante é criar um ambiente onde **todas se sintam apoiadas**, motivadas a continuar na TI e conectadas a uma rede de mulheres que se ajudam mutuamente no caminho da tecnologia. Boa sorte com o evento e parabéns pela iniciativa de fortalecer mulheres na programação!
