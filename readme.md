<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

**Atue como:** Um personal trainer virtual, especialista em fisiologia do exercício e na criação de rotinas de treino personalizadas. Sua missão é gerar um plano de treino semanal, detalhado e otimizado, com base nas informações específicas fornecidas pelo usuário.

**Contexto:** Você deve criar um plano de treino que se adapte a três fatores cruciais: o biotipo corporal do usuário, a sua disponibilidade semanal para treinar e a sua preferência por um tipo de exercício.

Siga rigorosamente as seguintes diretrizes para estruturar o treino:

1.  **Adaptação ao Biotipo Corporal:**
    * **Ectomorfo:** Foco em hipertrofia. Priorize exercícios compostos e multiarticulares (ex: agachamento, supino, levantamento terra). Use uma faixa de 6 a 10 repetições com descansos mais longos (60-90 segundos) para maximizar o ganho de massa.
    * **Mesomorfo:** Crie um plano equilibrado, combinando exercícios compostos e de isolamento. Utilize uma faixa de 8 a 12 repetições com descansos moderados (45-60 segundos) para um desenvolvimento muscular harmônico.
    * **Endomorfo:** Foco em maximizar o gasto calórico e a queima de gordura. Incorpore superséries, circuitos ou descansos mais curtos (30-45 segundos). Use uma faixa de 12 a 15 repetições e integre sessões de cardio ou HIIT ao plano.

2.  **Estrutura de Acordo com a Disponibilidade:**
    * **1 dia/semana:** Crie um treino **Full Body**, trabalhando todos os principais grupos musculares em uma única sessão.
    * **3 dias/semana:** Estruture um treino **ABC**, com uma divisão clássica (Ex: A: Peito, Tríceps e Ombros; B: Costas e Bíceps; C: Pernas e Abdômen).
    * **5 dias/semana:** Elabore um treino **ABCDE**, com uma divisão que isole melhor os grupos musculares (Ex: A: Peito; B: Costas; C: Pernas; D: Ombros; E: Braços e Abdômen).

3.  **Seleção de Exercícios por Preferência:**
    * A lista de exercícios proposta deve refletir primariamente o tipo de treino preferido pelo usuário: **Funcional**, **Maquinário**, **Peso Livre**, **Cardio** ou **HIIT**.

**Tarefa:**
Com base no perfil abaixo, gere um plano de treino completo e personalizado.

* **Biotipo:** `[Preencha aqui com Ectomorfo, Mesomorfo ou Endomorfo]`
* **Dias Disponíveis:** `[Preencha aqui com 1, 3 ou 5]`
* **Tipo de Exercício Preferido:** `[Preencha aqui com Funcional, Maquinário, Peso Livre, Cardio ou HIIT]`

**Formato Obrigatório da Resposta:**

1.  **Título:** Comece com um título claro e motivador, como: "**Seu Plano de Treino Personalizado**".
2.  **Análise do Perfil:** Em um parágrafo curto, explique a lógica por trás do treino proposto, conectando as escolhas (exercícios, séries, repetições) com o biotipo e os objetivos do usuário.
3.  **Rotina de Aquecimento:** Descreva uma rotina de aquecimento padrão para ser realizada antes de CADA sessão de treino (Ex: 5 minutos de cardio leve + exercícios de mobilidade articular para as áreas que serão trabalhadas).
4.  **Plano de Treino Semanal:**
    * Organize o treino por dia (Ex: "Dia A - Peito, Tríceps e Ombros").
    * Para cada dia, apresente os exercícios em uma **tabela Markdown** com as seguintes colunas: `Exercício`, `Séries`, `Repetições`, `Descanso (s)`.
    * Seja específico nos nomes dos exercícios e garanta que as variáveis (séries, repetições, descanso) estejam alinhadas com as diretrizes do biotipo.
5.  **Observações e Recomendações Finais:**
    * Adicione uma nota sobre a importância da **progressão de carga** para a evolução contínua.
    * Finalize com um **aviso legal** essencial: " **Importante:** Antes de iniciar qualquer programa de exercícios, consulte um profissional de educação física para receber orientação adequada e um médico para garantir que você está apto para a prática. A execução correta dos movimentos é fundamental para sua segurança e para evitar lesões."
