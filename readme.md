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

🎯 Projeto de Prompt Engineering: Assistente de Personal Trainer
📝 Introdução
Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

💪 Biotipos Corporais
A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

# Imagem	Biotipo	Descrição

Ectomorfo	Corpo mais magro, dificuldade para ganhar peso e massa muscular.
Mesomorfo	Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
Endomorfo	Corpo com tendência a acumular gordura, dificuldade em perder peso.
Nota: Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

📅 Dias Disponíveis para Treino
A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

# Imagem	Dias por Semana	Tipo de Treino Sugerido

1 dia	Treino Full Body (trabalho de todo o corpo em uma única sessão).
3 dias	Treino ABC (dividido em três dias, cada um focado em grupos musculares diferentes).
5 dias	Treino ABCDE (dividido em cinco dias, com foco mais específico em cada grupo muscular).
🏋️ Tipos de Exercícios
A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

# Imagem	Tipo de Treino	Descrição
- Funcional	Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
- Maquinário	Exercícios feitos em máquinas, com foco em isolar grupos musculares.
- Peso Livre	Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
- Cardio	Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
- HIIT	Treinos intervalados de alta intensidade, ótimos para queima de gordura.
- Calistenia	Exercícios que utilizam o peso do corpo, como flexões e barras, para desenvolver força e resistência.
- Yoga	Exercícios que focam na flexibilidade, força e equilíbrio, com ênfase em posturas e respiração.
- Alongamento	Exercícios que visam melhorar a flexibilidade e a amplitude de movimento dos músculos e articulações.

# 🛠️ Regras de Negócio

Identifique seu biotipo corporal consultando a seção de biotipos.
Determine quantos dias por semana você pode treinar e escolha o tipo de treino mais adequado.
Selecione o tipo de exercício que prefere realizar e que se encaixa melhor nos seus objetivos.
Use o prompt do assistente para gerar um plano de treino personalizado.

# 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de engenharia de prompt:

Fundamentos de Engenharia de Prompt
Boas práticas de prompt

🎯 Prompt de Resposta Proposto
Objetivo: Criar um plano de treino personalizado com base nas informações fornecidas pelo usuário.

# Informações necessárias do usuário:

Biotipo Corporal: Ectomorfo, Mesomorfo, Endomorfo.
Dias Disponíveis para Treino: 1 dia, 3 dias, 5 dias.
Tipo de Exercício Preferido: Funcional, Maquinário, Peso Livre, Cardio, HIIT, Calistenia, Yoga, Alongamento.

# Instruções para o Assistente:

Receber Informações: Solicite ao usuário que forneça seu biotipo corporal, o número de dias disponíveis para treinar por semana e o tipo de exercício preferido.
Gerar Plano de Treino: Com base nas informações fornecidas, crie um plano de treino detalhado e personalizado.
Para o biotipo corporal: Ajuste o plano de acordo com as necessidades específicas (e.g., um ectomorfo pode precisar de mais foco em levantamento de pesos, enquanto um endomorfo pode precisar de mais exercícios de cardio).
Para os dias disponíveis: Ajuste o volume e a divisão do treino de acordo com o número de dias que o usuário pode treinar.
Para o tipo de exercício preferido: Inclua uma variedade de exercícios que se alinhem com as preferências do usuário.

## Exemplo de Entrada e Saída:

*Entrada:*

 - Biotipo Corporal: Endomorfo
 - Dias Disponíveis para Treino: 3
 - Tipo de Exercício Preferido: Calistenia
  
 *Saída: Como um Endomorfo com 3 dias disponíveis para treinar e preferência por Calistenia, seu plano de treino será:*

- Dia 1: Calistenia focada na parte superior do corpo (e.g., flexões, barras).
- Dia 2: Calistenia focada na parte inferior do corpo (e.g., agachamentos, elevações de panturrilha).
- Dia 3: Sessão combinada de Calistenia com Alongamento | (e.g., uma mistura de exercícios de calistenia e alongamentos para aumentar a flexibilidade e prevenir lesões).

*Entrada:*

- Biotipo Corporal: Mesomorfo
- Dias Disponíveis para Treino: 5
- Tipo de Exercício Preferido: Yoga

*Saída: Como um Mesomorfo com 5 dias disponíveis para treinar e preferência por Yoga, seu plano de treino será:*

- Dia 1: Yoga focada em flexibilidade e relaxamento.
- Dia 2: Yoga com ênfase em força e equilíbrio.
- Dia 3: Sessão de Yoga combinada com Alongamento.
- Dia 4: Yoga para melhorar a postura e respiração.
- Dia 5: Sessão completa de Yoga com foco em integração e prática de posturas avançadas.

# Boas Práticas de Engenharia de Prompt Aplicadas:

1. Clareza: O prompt é claro quanto ao objetivo e às informações necessárias para criar um plano de treino personalizado.
2. Especificidade: Especifica as categorias de biotipo, dias disponíveis e tipos de exercícios, incluindo as novas opções de calistenia, yoga e alongamento.
3. Contextualização: Fornece contexto sobre como cada fator afeta o plano de treino e exemplos concretos para ilustrar o que é esperado.
4. Iteração: Permite ajustes no plano de treino com base nas especificidades fornecidas pelo usuário, melhorando a precisão e relevância da resposta.
