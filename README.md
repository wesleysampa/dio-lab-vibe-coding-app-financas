<div align="center">

# 💰 ConversaFin!

### App de Organização de Finanças Pessoais com IA

[![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen?style=for-the-badge)](https://github.com/wesleysampa/dio-lab-vibe-coding-app-financas)
[![Lovable](https://img.shields.io/badge/feito%20com-Lovable-FF6B6B?style=for-the-badge)](https://lovable.dev)
[![DIO](https://img.shields.io/badge/Desafio-DIO%20Vibe%20Coding-blue?style=for-the-badge)](https://web.dio.me)
[![Deploy](https://img.shields.io/badge/Acessar%20App-ConversaFin-green?style=for-the-badge&logo=vercel&logoColor=white)](https://conversa-fin-buddy.lovable.app/login)

> 🗣️ Um aplicativo que elimina formulários e planilhas.
> Organize suas finanças apenas **conversando** em linguagem natural.

🔗 **Acesse o app publicado:** [conversa-fin-buddy.lovable.app](https://conversa-fin-buddy.lovable.app/login)

</div>

## 📖 Índice

- [🎯 Prompt Final (PRD)](#-prompt-final-prd)
- [🖼️ Imagens das Interações com a IA](#️-imagens-das-interações-com-a-ia)
- [💡 Resumo do Conceito do App](#-resumo-do-conceito-do-app)
- [🧠 Reflexão sobre o Processo](#-reflexão-sobre-o-processo)

---

## 🎯 Prompt Final (PRD)

O **PRD (Product Requirements Document)** abaixo foi o prompt principal utilizado com a IA (**Lovable**) para gerar o conceito e as telas do aplicativo.

<details>
<summary><strong>📄 Clique para expandir o PRD completo</strong></summary>

```text
# PRD - App para Organizacao de Financas Pessoais ConversaFin!

## 1. Contexto e Visao Geral
O produto e um aplicativo de organizacao de financas pessoais focado em simplicidade, operado por meio de conversas em linguagem natural. Ele elimina a necessidade de formularios manuais extensos ou planilhas complexas. O objetivo e tornar a gestao financeira acessivel, simples e engajadora para todos os usuarios.

## 2. Problema
- Aplicativos tradicionais exigem entrada manual excessiva e burocratica.
- Falta de personalizacao e experiencia engessada.
- Usuarios iniciantes desistem rapidamente do controle financeiro por conta da complexidade.

## 3. Publico-Alvo
- Pessoas que desejam comecar a organizar suas financas de forma pratica e sem complicacao.
- Principalmente iniciantes que buscam simplicidade, orientacao visual e pouca burocracia.

## 4. Funcionalidades-Chave (Escopo do MVP)

### 0. Autenticacao de Usuario
- Tela de login e cadastro com e-mail e senha.
- Cada usuario possui seus proprios dados financeiros.
- Sessao persistente e opcao de logout no header.
- Dados isolados por usuario, garantindo privacidade.

### 1. Registro via Chat
- Insercao de gastos e receitas em linguagem natural por texto (exemplo: "Gastei R$ 50 no mercado", "Recebi meu salario de R$ 3000").
- Interpretacao dinamica dos valores e intencao do usuario.

### 2. Classificacao e Criacao Automatica de Categorias
- Identificacao e categorizacao automatica das transacoes sem esforco manual.
- Logica de Autocadastro: caso a categoria nao exista, o app cria automaticamente e vincula a transacao.

### 3. Metas Financeiras
- Criacao e acompanhamento visual de objetivos de economia (exemplo: "Economizar R$ 500 para emergencia").
- Indicadores de progresso simples e diretos.

### 4. Agente Financeiro
- Recomendacoes personalizadas e dicas automaticas de economia enviadas no proprio fluxo de conversa com base nos gastos registrados.

### 5. Relatorios Simples
- Visualizacoes acessiveis e personalizadas (cards de resumo de receitas, despesas e saldo, alem de relatorios visuais simplificados).

### 6. Design Universal
- Interface projetada para oferecer uma otima experiencia para o maximo de usuarios possivel, independentemente de idade, nivel de habilidade digital ou necessidades especificas.
- Elementos com alto contraste, fontes legiveis, botoes amplos e suporte a navegacao intuitiva.

## 5. Diretrizes de Design, Layout e Paleta de Cores

### Paleta de Cores
- Cor Primaria: Verde Esmeralda (#22C55E).
- Fundo Geral: Cinza Claro Neutro (#F8FAFC).
- Cards: Branco (#FFFFFF) com bordas suaves em cinza (#E2E8F0).
- Receita: Verde (#22C55E).
- Despesa: Vermelho (#EF4444).
- Texto Principal: Grafite (#1E293B).

### Estrutura Visual
1. Tela de Login: formulario com e-mail e senha, botao de entrar e link para cadastro.
2. Dashboard Integrado: header com titulo e saudacao, 3 cards de resumo, chat e painel de metas.
3. Tela de Relatorios: cards filtrados por periodo, graficos e extrato.

## 6. Entregavel da IA (Estrutura do MVP)

### Telas e Componentes
- Tela de Autenticacao (Login e Cadastro).
- Chat de Interacao Conversacional.
- Dashboard Misto (Cards de Metricas + Painel de Metas).
- Tela de Relatorios Visuais Simplificados.

### Recursos Tecnicos
- Autenticacao de usuarios com e-mail e senha.
- Persistencia de dados por usuario.
- Processamento de Linguagem Natural (NLP).
- Motor de categorizacao automatica com adicao dinamica de categorias.
- Acessibilidade e usabilidade universal (WCAG 2.1 AA).

## 7. Plano de Validacao Inicial
- Testes com grupo piloto focado em usuarios iniciantes e perfis variados.
- Coleta de feedback sobre a clareza da conversa, utilidade das recomendacoes e acessibilidade do layout.
```

</details>

---

## 🖼️ Imagens das Interações com a IA

### 🔐 Tela de Login

<p align="center">
  <img src="login.png" alt="Tela de login do ConversaFin" width="900">
</p>

Tela inicial onde o usuário faz login ou cria uma conta com e-mail e senha.

---

### 📊 Dashboard Principal

<p align="center">
  <img src="dashboard.png" alt="Dashboard com cards de resumo, chat e metas" width="900">
</p>

Após o login, o usuário visualiza seus cards de resumo (**Receitas**, **Despesas** e **Saldo Total**), o chat do **Assistente Financeiro** e o painel **Minhas Metas**.

---

### 💬 Interação no Chat com a IA

<p align="center">
  <img src="chat.png" alt="Interação com o Assistente Financeiro" width="900">
</p>

Usuário registra gastos e receitas via linguagem natural. A IA interpreta, categoriza e responde com dicas de economia personalizadas.

---

### 📈 Tela de Relatórios

<p align="center">
  <img src="relatorios.png" alt="Relatórios visuais simplificados" width="900">
</p>

Cards de resumo filtrados por período, gráfico de despesas por categoria, comparação entre receitas e despesas e extrato de transações.

---

## 💡 Resumo do Conceito do App

O **ConversaFin** é um aplicativo de organização de finanças pessoais focado em **simplicidade**. Em vez de formulários manuais ou planilhas complexas, o usuário interage com o sistema por meio de **conversas em linguagem natural**.

### ✨ Principais recursos

| Recurso | Descrição |
|---------|-----------|
| 🔐 **Autenticação** | Login e cadastro com e-mail e senha |
| 💬 **Registro via Chat** | Gastos e receitas em linguagem natural |
| 🏷️ **Categorização Automática** | A IA identifica e cria categorias dinamicamente |
| 🎯 **Metas Financeiras** | Criação e acompanhamento visual com barra de progresso |
| 🤖 **Agente Financeiro** | Dicas personalizadas de economia no fluxo da conversa |
| 📊 **Relatórios** | Gráficos e extrato com filtros por período |
| ♿ **Design Universal** | Alto contraste, fontes legíveis e navegação intuitiva |

O aplicativo possui **autenticação de usuário**, garantindo que cada pessoa tenha seus próprios dados financeiros isolados. Após o login, o usuário pode registrar gastos e receitas por chat, criar metas financeiras, receber dicas automáticas de economia e visualizar relatórios simples com filtros por período.

O design foi pensado para ser **universal**: alto contraste, fontes legíveis, botões amplos e navegação intuitiva, garantindo boa experiência para o maior número possível de usuários.

---

## 🧠 Reflexão sobre o Processo

### ✅ O que funcionou bem?

- O **PRD detalhado**, usado como primeiro prompt no Lovable, gerou uma estrutura de interface próxima do resultado esperado, com dashboard, chat e painel de metas.
- A descrição clara das **cores, do layout e das funcionalidades** no PRD reduziu a necessidade de correções posteriores.
- O uso do **Design Universal** como requisito desde o início garantiu uma interface consistente e acessível.
- A integração nativa do **Lovable com o Supabase** facilitou a implementação da autenticação e do banco de dados.

### ⚠️ O que não funcionou como o esperado?

- O **primeiro prompt** não cobriu todos os detalhes das funcionalidades. Foi necessário iterar com prompts adicionais.
- A compreensão de **frases informais**, sem valores explícitos em reais, exigiu refinamento das instruções dadas à IA.
- Algumas funcionalidades, como a **exclusão de metas**, o **botão de zerar dados** e a **persistência do histórico do chat**, precisaram ser solicitadas separadamente.
- Ajustes finos na **autenticação** (redirecionamento e persistência de sessão) exigiram prompts específicos.

### 📚 O que aprendi sobre conversar com IAs?

- 🎯 **Contexto é fundamental.** Um prompt de sistema claro, com regras e exemplos, é mais eficaz do que vários comandos soltos.
- 🔄 **A iteração é parte natural do processo.** O primeiro prompt raramente gera o resultado final; testar e refinar é essencial.
- 📝 **Exemplos concretos** de entrada e saída ajudam a IA a entender o comportamento esperado melhor do que descrições abstratas.
- 🚧 **Definir limites para a IA** (o que ela não deve fazer) evita respostas incorretas ou inventadas.
- 💡 **O Vibe Coding, na prática, é uma habilidade de conversa.** Quanto melhor a descrição, mais próximo o resultado.

---

<div align="center">

### 🎓 Projeto desenvolvido para o Lab **DIO - Vibe Coding**

Feito com 💚 por **Wesley Sampa** usando **Lovable AI**

⭐ Se este projeto te ajudou, dê uma estrela no repositório!

</div>
