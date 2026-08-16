<div align="center">
  
# 💸 App de Organização de Finanças Pessoais com Vibe Coding

Laboratório educacional sobre criação de conteúdo multimodal com inteligência artificial generativa, explorando texto, imagem, áudio e vídeo.

![Lovable](https://img.shields.io/badge/Lovable-VibeCoding-8A2BE2?style=for-the-badge)
![Copilot Web](https://img.shields.io/badge/Copilot-PRD-10A37F?style=for-the-badge\&logo=openai\&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-Documentação-000000?style=for-the-badge\&logo=markdown\&logoColor=white)
![DIO](https://img.shields.io/badge/DIO-Desafio_Educacional-E94D5F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Documentação_em_evolução-yellow?style=for-the-badge)

</div>

---
## 📌 Sobre o projeto

Este repositório reúne estudos e propostas de conteúdo desenvolvidos durante o laboratório **App de Organização de Finanças Pessoais com Vibe Coding**, da Digital Innovation One.

A atividade explora a **criação de soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> A idéia não é **construir o código**! O foco está em **usar a IA como parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue.

Segue meu PRD:

```txt
O ponto principal é mudar o posicionamento de **finanças pessoais individuais** para **gestão financeira compartilhada do casal**, mantendo a experiência conversacional como diferencial.

# Contexto

Quero criar um aplicativo de **Organização de Finanças Pessoais para Casais** que funcione por meio de conversas com os usuários.

A ideia é facilitar o controle financeiro do casal de forma simples, natural e colaborativa, permitindo que ambos registrem gastos, acompanhem receitas, organizem objetivos e tomem decisões financeiras juntos, sem depender de formulários manuais ou planilhas complexas.

O aplicativo terá uma experiência baseada em conversas, na qual cada pessoa poderá informar suas movimentações financeiras utilizando linguagem natural, como:

> “Gastei R$ 85 no supermercado.”

> “O Mateus pagou R$ 120 de gasolina.”

> “Recebi meu salário hoje.”

> “Quanto ainda podemos gastar este mês?”

A partir dessas informações, o aplicativo deverá organizar automaticamente os dados e apresentar uma visão financeira conjunta do casal.

# Problema

Muitos casais têm dificuldade para organizar as finanças porque o controle financeiro tradicional exige planilhas, lançamentos manuais e acompanhamento constante.

Além disso, quando as finanças são compartilhadas, surgem desafios adicionais:

* Falta de transparência sobre os gastos;
* Dificuldade para dividir despesas;
* Falta de clareza sobre quanto cada pessoa contribuiu;
* Desorganização entre contas individuais e despesas do casal;
* Dificuldade para estabelecer objetivos financeiros em conjunto;
* Falta de comunicação sobre dinheiro;
* Desconhecimento de quanto o casal realmente pode gastar.

O aplicativo busca resolver esses problemas oferecendo uma experiência simples, conversacional e focada na **organização financeira conjunta do casal**.

# Público-Alvo

Casais que desejam organizar melhor sua vida financeira, principalmente:

* Casais que moram juntos;
* Casais que compartilham despesas;
* Casais que estão começando a organizar as finanças;
* Pessoas que têm dificuldade em utilizar planilhas ou aplicativos financeiros tradicionais;
* Casais que desejam economizar para objetivos em conjunto;
* Casais que querem acompanhar quanto cada pessoa recebe, gasta e contribui para as despesas.

O foco inicial será em **iniciantes em organização financeira**, priorizando simplicidade e facilidade de uso.

# Proposta de Valor

O aplicativo será um **assistente financeiro conversacional para casais**.

Em vez de preencher diversos campos, o usuário simplesmente conversa com o aplicativo.

O sistema transforma a conversa em informações financeiras organizadas, permitindo que o casal tenha uma visão clara de sua situação financeira.

A proposta pode ser resumida como:

**“Converse com seu dinheiro. Organize sua vida financeira a dois.”**

# Funcionalidades-Chave

## 1. Registro de gastos por conversa

O usuário poderá registrar receitas e despesas utilizando linguagem natural.

Exemplos:

* “Gastei R$ 50 no almoço.”
* “Paguei R$ 1.800 de aluguel.”
* “Recebi R$ 3.500 de salário.”
* “A Bianca pagou R$ 200 de supermercado.”
* “Nós gastamos R$ 150 no jantar.”

A IA deverá identificar automaticamente:

* Valor;
* Tipo da movimentação;
* Categoria;
* Data;
* Pessoa responsável pelo pagamento;
* Se a despesa é individual ou compartilhada.

## 2. Classificação automática

O aplicativo deverá categorizar automaticamente as movimentações.

Exemplos de categorias:

* Moradia;
* Alimentação;
* Transporte;
* Saúde;
* Lazer;
* Assinaturas;
* Educação;
* Compras;
* Contas;
* Investimentos;
* Outros.

O usuário poderá corrigir ou personalizar as categorias.

## 3. Finanças individuais e compartilhadas

O sistema deverá diferenciar:

**Despesas individuais**

* Gastos pessoais de cada integrante.

**Despesas do casal**

* Aluguel;
* Energia;
* Internet;
* Supermercado;
* Viagens;
* Restaurantes;
* Outros gastos compartilhados.

Isso permitirá visualizar tanto a situação individual quanto a situação financeira conjunta.

## 4. Divisão de despesas

O aplicativo poderá acompanhar quanto cada pessoa pagou e quanto deveria contribuir.

Exemplo:

> “Este mês vocês tiveram R$ 3.000 em despesas compartilhadas. Bianca pagou R$ 1.800 e Mateus R$ 1.200.”

O sistema poderá mostrar a diferença e facilitar o acerto entre o casal.

## 5. Metas financeiras do casal

O casal poderá criar objetivos conjuntos, como:

* Reserva de emergência;
* Viagem;
* Comprar um carro;
* Comprar uma casa;
* Casamento;
* Quitar dívidas;
* Investimentos;
* Outros objetivos.

O aplicativo deverá acompanhar o progresso da meta e informar quanto ainda falta.

## 6. Agente Financeiro

O aplicativo contará com um **Agente Financeiro**, responsável por analisar os dados financeiros e conversar com o casal.

Exemplos:

> “Vocês gastaram 18% a mais com restaurantes este mês. Querem que eu sugira uma meta para reduzir esse gasto?”

> “Vocês já economizaram R$ 800 para a viagem. Mantendo esse ritmo, alcançarão a meta em aproximadamente X meses.”

> “As despesas compartilhadas aumentaram neste mês. Querem analisar onde ocorreu o maior aumento?”

O agente deverá atuar de forma educativa, evitando julgamentos e incentivando decisões financeiras conscientes.

## 7. Relatórios simples

O casal poderá visualizar informações como:

* Receitas do mês;
* Despesas do mês;
* Saldo disponível;
* Gastos por categoria;
* Gastos individuais;
* Gastos compartilhados;
* Participação de cada integrante;
* Evolução das metas;
* Comparação entre meses.

Os relatórios deverão utilizar gráficos simples e linguagem acessível.

# Principais Telas do MVP

## 1. Onboarding

Cadastro inicial do casal:

* Nome dos integrantes;
* Renda aproximada;
* Objetivos financeiros;
* Forma de divisão das despesas;
* Data de início do controle financeiro.

## 2. Tela inicial / Dashboard

Visão resumida da situação financeira:

**Receitas**
R$ X

**Despesas**
R$ X

**Saldo**
R$ X

**Despesas compartilhadas**
R$ X

**Meta atual**
X% concluída

Também deverá existir acesso rápido ao chat.

## 3. Chat Financeiro

Será a principal tela do aplicativo.

O casal poderá conversar diretamente com o Agente Financeiro para:

* Registrar gastos;
* Registrar receitas;
* Consultar informações;
* Fazer perguntas;
* Criar metas;
* Analisar gastos;
* Receber recomendações.

## 4. Movimentações

Lista de todas as receitas e despesas registradas.

Filtros:

* Pessoa;
* Categoria;
* Período;
* Individual/compartilhado;
* Receita/despesa.

## 5. Metas

Tela dedicada aos objetivos financeiros do casal.

Cada meta deverá apresentar:

* Valor desejado;
* Valor acumulado;
* Percentual concluído;
* Prazo;
* Evolução.

## 6. Relatórios

Dashboard simplificado com:

* Gastos por categoria;
* Evolução mensal;
* Gastos individuais;
* Gastos compartilhados;
* Receitas x despesas;
* Evolução das metas.

## 7. Configurações do casal

Permitir:

* Gerenciar integrantes;
* Personalizar categorias;
* Definir regras de divisão;
* Alterar metas;
* Configurar notificações;
* Ajustar preferências financeiras.

# Recursos Necessários para o MVP

## Backend

* Banco de dados para usuários e transações;
* Autenticação;
* Estrutura de contas compartilhadas;
* API para movimentações;
* Sistema de metas;
* Motor de categorização;
* Histórico de conversas.

## Inteligência Artificial

A IA deverá:

* Interpretar linguagem natural;
* Identificar valores e datas;
* Classificar transações;
* Identificar quem realizou o gasto;
* Diferenciar despesas individuais e compartilhadas;
* Responder perguntas financeiras com base nos dados do casal;
* Gerar recomendações personalizadas.

## Frontend

* Aplicativo mobile ou aplicação web responsiva;
* Chat como elemento central;
* Dashboard financeiro;
* Gráficos;
* Tela de movimentações;
* Tela de metas;
* Configurações.

# MVP — O que realmente precisa existir na primeira versão

Para validar a ideia, o primeiro MVP não precisa ter todas as funcionalidades.

A versão inicial pode conter apenas:

1. Cadastro de duas pessoas;
2. Chat financeiro;
3. Registro de receitas e despesas por linguagem natural;
4. Classificação automática;
5. Identificação de quem realizou o gasto;
6. Diferenciação entre gasto individual e compartilhado;
7. Dashboard mensal;
8. Meta financeira simples;
9. Perguntas básicas ao Agente Financeiro.

O objetivo do MVP será descobrir se os casais realmente preferem **conversar com um assistente para controlar suas finanças** em vez de preencher formulários.

# Validação Inicial

A validação deverá começar antes do desenvolvimento completo.

## Etapa 1 — Entrevistas

Conversar com aproximadamente 10 a 20 casais e entender:

* Como atualmente controlam o dinheiro;
* Se utilizam planilhas;
* Se utilizam aplicativos financeiros;
* Como dividem as despesas;
* Quais são suas maiores dificuldades;
* Como tomam decisões financeiras;
* Quais informações gostariam de consultar rapidamente.

## Etapa 2 — Protótipo

Criar um protótipo simples demonstrando a experiência:

**Usuário:**
“Gastei R$ 120 no supermercado.”

**Aplicativo:**
“Registrei R$ 120 em Alimentação como despesa compartilhada. Você pagou. Está correto?”

**Usuário:**
“Sim.”

**Aplicativo:**
“Pronto! As despesas compartilhadas de vocês neste mês estão em R$ 1.240.”

## Etapa 3 — Teste com casais

Selecionar alguns casais para utilizar o protótipo durante algumas semanas.

Medir:

* Quantidade de registros realizados;
* Frequência de uso;
* Quantidade de correções feitas;
* Perguntas realizadas ao Agente Financeiro;
* Uso das metas;
* Retenção dos usuários;
* Percepção de facilidade.

## Etapa 4 — Validar a principal hipótese

A principal hipótese do produto será:

**“Casais conseguem organizar suas finanças com mais frequência e menos esforço quando podem registrar e consultar informações financeiras por meio de uma conversa.”**

Se os usuários demonstrarem preferência pelo modelo conversacional e continuarem utilizando o aplicativo, será possível evoluir para funcionalidades mais avançadas.

# Diferencial do Produto

O principal diferencial não será apenas registrar despesas.

Será criar uma experiência de **gestão financeira a dois**, combinando:

**Conversação + Inteligência Artificial + Finanças Compartilhadas + Metas + Recomendações.**

O aplicativo deverá funcionar como uma espécie de **“terceiro elemento financeiro do casal”**, ajudando os dois a enxergar a situação financeira com clareza, organizar os gastos e tomar decisões em conjunto.

# Visão de Futuro

Após validar o MVP, o aplicativo poderá evoluir para:

* Integração bancária;
* Open Finance;
* Reconhecimento automático de transações;
* Divisão inteligente de despesas;
* Previsão de gastos;
* Planejamento financeiro mensal;
* Alertas personalizados;
* Análise de assinaturas;
* Detecção de gastos fora do padrão;
* Simulações financeiras;
* Planejamento de grandes objetivos;
* Score de saúde financeira do casal;
* Gamificação de economia;
* Recomendações financeiras cada vez mais personalizadas.

A visão de longo prazo é transformar o aplicativo em um **assistente financeiro inteligente para a vida a dois**, tornando a organização financeira mais simples, conversacional e acessível.

```

Foi usadoo Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable, lapidando o texto até que ele fique claro, direto e reflita exatamente a intenção.

> [!TIP]
> O PRD/Prompt pode ser pensado como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

Durante essa etapa, foi orientado a IA para três entregas principais:
1. Agente Financeiro: comportamento humanizado casual, tom de voz suave, de um consultor financeiro pessoal, alinhado ao público eu meu esposo com objetivo de compartilhar nossas finanças
2. Fluxo de Telas: foi solicitado à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicitado um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

### 2. Entregando o Desafio na DIO
 
No README do repositório, consta:

-  **prompt final** (PRD);  
- 🖼️ Prints das interações com a IA;

### Lovable – Criação do app 

<a href="https://ibb.co/B2xS4SVy"><img src="https://i.ibb.co/jk21V1vy/Captura-de-tela-de-2026-08-14-15-37-01.png" alt="Captura-de-tela-de-2026-08-14-15-37-01" border="0"></a>
<a href="https://ibb.co/1GtJCNnb"><img src="https://i.ibb.co/YBFT5SWb/Captura-de-tela-de-2026-08-14-15-40-28.png" alt="Captura-de-tela-de-2026-08-14-15-40-28" border="0"></a>
<a href="https://ibb.co/m5hRhzh0"><img src="https://i.ibb.co/HTGKGgGC/Captura-de-tela-de-2026-08-14-15-40-58.png" alt="Captura-de-tela-de-2026-08-14-15-40-58" border="0"></a>
<a href="https://ibb.co/ccF3PF2q"><img src="https://i.ibb.co/99TgJTyP/Captura-de-tela-de-2026-08-14-15-41-46.png" alt="Captura-de-tela-de-2026-08-14-15-41-46" border="0"></a>
<a href="https://ibb.co/dwVRK4Zm"><img src="https://i.ibb.co/bMCkd5tb/Captura-de-tela-de-2026-08-14-15-42-23.png" alt="Captura-de-tela-de-2026-08-14-15-42-23" border="0"></a>
<a href="https://ibb.co/PG9bmHrZ"><img src="https://i.ibb.co/5hnzMH1W/Captura-de-tela-de-2026-08-16-12-08-01.png" alt="Captura-de-tela-de-2026-08-16-12-08-01" border="0"></a>
<a href="https://ibb.co/hxhv0GWq"><img src="https://i.ibb.co/GfBjmZ2h/Captura-de-tela-de-2026-08-16-12-07-05.png" alt="Captura de tela de 2026 08 16 12 07 05" border="0"></a>
<a href="https://ibb.co/jvKPdw5P"><img src="https://i.ibb.co/C5d3q9t3/Captura-de-tela-de-2026-08-16-12-06-52.png" alt="Captura-de-tela-de-2026-08-16-12-06-52" border="0"></a>
<a href="https://ibb.co/HprD6XCm"><img src="https://i.ibb.co/Pz5ZKtMB/Captura-de-tela-de-2026-08-16-12-06-37.png" alt="Captura-de-tela-de-2026-08-16-12-06-37" border="0"></a>
<a href="https://ibb.co/2rhBYVL"><img src="https://i.ibb.co/Cy8FsCX/Captura-de-tela-de-2026-08-16-12-06-12.png" alt="Captura-de-tela-de-2026-08-16-12-06-12" border="0"></a>

*Plataforma usada para transformar a ideia na criação do site.*

Um resumo do que o  **App de Finanças Pessoais em casal** faz:

  
🩷 "Sem planilhas, sem formulários. Vocês contam o que gastaram em uma frase e o app organiza tudo: categorias, quem pagou, o que é do casal e quanto ainda dá para gastar."

Aqui está o link de acesso ao protótipo funcional: [https://tandem-trifle-tracker.lovable.app/]
  
- Uma breve **reflexão sobre o processo**:
1. O que funcionou bem?
 A IA ajudou a transformar uma ideia inicial em uma proposta mais estruturada, organizando o problema, o público-alvo, as funcionalidades e as principais telas do aplicativo. A conversa também facilitou a identificação do diferencial do projeto: um aplicativo voltado especificamente para finanças de casal, utilizando uma experiência de conversa em vez de formulários e planilhas.
---

2. O que não funcionou como esperado?
 Algumas sugestões iniciais ficaram muito genéricas e voltadas para organização financeira individual. Foi necessário explicar melhor que o foco seria a gestão financeira compartilhada do casal, incluindo divisão de despesas, contribuições de cada pessoa e metas conjuntas. Isso mostrou que uma ideia precisa ser bem contextualizada para que a IA consiga entregar respostas mais alinhadas ao objetivo.
---

3. O que aprendi sobre conversar com IAs?
 Aprendi que quanto mais claro e específico for o contexto fornecido, melhores são os resultados. A IA funciona melhor como uma parceira de construção: é possível apresentar uma ideia inicial, analisar as sugestões, corrigir o que não faz sentido e continuar refinando o projeto. Também percebi que é importante não aceitar a primeira resposta automaticamente, mas questionar, corrigir e orientar a IA para chegar a uma solução mais adequada.


## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.

## 👨‍💻 Autor

Desenvolvido por **Bianca — biancaunitcont**.

[![GitHub](https://img.shields.io/badge/GitHub-ONestoDev-181717?style=for-the-badge\&logo=github)](https://github.com/biancaunitcont)

---
