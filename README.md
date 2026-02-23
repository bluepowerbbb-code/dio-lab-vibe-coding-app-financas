# 💸 App de Finanças Conversacionais

PRD Atual

---

## 📌 Visão Geral

Aplicativo de organização de finanças pessoais por conversa natural, acessível e seguro.  
Funciona como um consultor financeiro digital, educativo e empático.

---

## 🎯 Problema

Apps financeiros tradicionais exigem formulários complexos, pressupõem conhecimento financeiro e têm baixa acessibilidade.  
Como consequência, usuários iniciantes, idosos e pessoas com baixa familiaridade digital desistem rapidamente.

---

## 🎯 Objetivos

- Reduzir esforço de registro financeiro  
- Permitir múltiplas formas de entrada (texto, voz, imagem)  
- Garantir acessibilidade (Design Universal)  
- Oferecer orientação financeira clara e contínua  

---

## 👥 Público-Alvo

- **Primário:** pessoas iniciantes em controle financeiro  
- **Secundário:** idosos, pessoas com deficiência e usuários com baixa familiaridade digital  

---

## 🧩 Funcionalidades MVP

- Registro de transações por texto, voz, câmera ou copiar/colar  
- Consultor financeiro conversacional com IA  
- Metas financeiras sugeridas e ajustáveis  
- Relatórios simples e acessíveis (texto, gráficos e leitura em voz)  

---

## 🔐 Segurança & Privacidade

- Login simples (e-mail e senha / Google)  
- Criptografia em trânsito e em repouso  
- Conformidade com LGPD  
- Dados não utilizados para publicidade  

---

## ♿ Design Universal

- Botões grandes e alto contraste  
- Fonte ajustável  
- Compatibilidade com leitores de tela  
- Feedback visual e sonoro  
- Tolerância a erros e confirmações claras  

---

## 📈 Validação do MVP

- Tempo médio para registrar um gasto  
- Percentual de registros automáticos sem correção  
- Retenção em 7 e 30 dias  
- Taxa de correções manuais  

---

## 🛣️ Roadmap Futuro

- Área de investimentos  
- Integração Open Finance  
- Modo totalmente por voz  
- Notificações inteligentes  
- Personalização avançada do consultor  

---

## 📄 PRD Inicial (Solicitado ao Lovable)

> **Observação:**  
> Esta seção documenta **o PRD exatamente como foi enviado ao Lovable no início do projeto**,  
> conforme solicitado pelo professor. Ajustes posteriores estão registrados apenas
> na seção de Interações com o Lovable.

### PRD refinado no Copilot Web Smart GPT-5.1:
### PRD Resumido – App de Finanças Conversacionais (MVP 1.1)

**Visão**  
Aplicativo de organização de finanças pessoais por conversa natural, acessível e seguro.  
Funciona como um consultor financeiro digital, educativo e empático.

**Problema**  
Apps atuais exigem formulários complexos, pressupõem conhecimento financeiro  
e têm baixa acessibilidade → usuários iniciantes e idosos desistem cedo.

**Objetivos**
- Reduzir esforço de registro
- Permitir múltiplas formas de entrada (texto, voz, imagem)
- Garantir acessibilidade (Design Universal)
- Oferecer orientação financeira clara e contínua

**Público-Alvo**
- Primário: iniciantes em controle financeiro, quem nunca manteve um app do tipo
- Secundário: idosos, pessoas com deficiência, baixa familiaridade digital

**Funcionalidades MVP**
- Registro de transações por texto, voz, câmera ou copiar/colar
- Consultor financeiro (IA conversacional)
- Metas sugeridas e ajustáveis
- Relatórios simples e acessíveis (texto, gráficos básicos, leitura em voz)

**Segurança & Privacidade**
- Login simples (magic link/social), biometria opcional
- Criptografia em trânsito e em repouso
- LGPD, consentimento explícito, dados não usados para publicidade

**Design Universal**
- Botões grandes, alto contraste, fonte ajustável
- Compatível com leitores de tela (TalkBack/VoiceOver)
- Feedback visual e sonoro
- Tolerância a erros e confirmações fáceis

**Validação do MVP**
- Tempo médio para registrar gasto
- % de registros automáticos sem correção
- Retenção em 7 e 30 dias
- Taxa de correções manuais

**Roadmap Futuro**
- Área de investimentos
- Integração Open Finance
- Modo totalmente por voz
- Notificações inteligentes
- Personalização avançada do consultor

---

# 🤖 Interações com o Lovable

## 1️⃣ Criação inicial do App

**Aluno (prompt):**  
Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirement Document):

PRD Resumido – App de Finanças Conversacionais (MVP 1.1)

---

**Lovable (resposta):**  
Que projeto incrível! O PRD é bem detalhado. Antes de montar o plano, preciso entender melhor algumas prioridades para o MVP.

---

## 2️⃣ Definições do MVP

**Lovable (perguntas):**

- Quais formas de entrada de transações você quer priorizar?  
- Qual idioma principal da interface e do consultor IA?  
- Qual estilo visual você prefere?  
- Sobre autenticação, o que implementar no MVP?  

---

**Aluno (respostas):**

- Entrada de dados: Texto + voz + câmera  
- Idioma: Bilíngue PT/EN  
- Estilo visual: Amigável e colorido  
- Autenticação: Login simples (magic link ou social)  

---

**Lovable (confirmação):**

Entrada de dados: Texto + voz + câmera  
Idioma: Bilíngue PT/EN  
Design: Amigável e colorido  
Login: Autenticação simples  

---

## 3️⃣ Plataforma e Câmera

**Lovable (pergunta):**  
Qual plataforma você quer focar no MVP?

**Aluno (resposta):**  
Web + PWA instalável  

---

### Funcionalidade: Entrada por Câmera – Comprovantes

Esta funcionalidade permite que o usuário utilize a câmera do celular para registrar despesas a partir de comprovantes, com a opção de leitura automática por IA ou apenas anexação da imagem.

- Modo híbrido com ou sem IA  
- Anexo visual como fallback  
- Fluxo simples e editável  
- Funciona mesmo se a IA falhar  
- OCR fora do escopo do MVP  

---

## 4️⃣ Categorização

**Lovable (pergunta):**  
Como as transações devem ser categorizadas?

**Aluno (resposta):**  
Ambos (categorias padrão + sugestão por IA)

---

## 5️⃣ Planejamento Técnico (Plan)

**Lovable (Plan):**  
FinChat – App de Finanças Pessoais Conversacional

*(Plano completo conforme implementado no Lovable)*

---

**Status:**  
✅ Plan approved

---

## 6️⃣ Execução do Projeto

### Step 1 – Setup inicial

**Lovable:**  
Vou começar pelo Step 1: tema, PWA, acessibilidade e i18n.

**Resultado:**  
- Design system criado  
- i18n PT-BR / EN  
- Acessibilidade configurada  
- PWA funcional  
- Estrutura de páginas criada  

---

### Step 2 e 3 – Autenticação e Banco de Dados

**Lovable:**  
Vou implementar autenticação e banco com RLS.

**Resultado:**  
- Tabelas criadas com Row Level Security  
- Storage para comprovantes  
- Autenticação funcional  

---

### Step 4 – Chat com IA

**Lovable:**  
Vou implementar o chat financeiro com IA.

**Resultado:**  
- Chat com streaming  
- Registro automático de transações  
- Persistência no banco  

---

## 7️⃣ Redesign e Relatórios (Batching)

**Aluno (prompt):**  
Adicionar em uma única iteração:
- Relatórios completos  
- Resumo financeiro no topo  
- Redesign branco e minimalista  

**Lovable (resposta):**  
Vou implementar tudo de forma integrada.

**Resultado:**  
- Relatórios com gráficos e filtros  
- Resumo financeiro visível  
- Design branco e minimalista  

---

## 8️⃣ Voz e Câmera no MVP

**Aluno (prompt):**  
Adicionar entrada por voz e câmera sem OCR no MVP.

**Lovable (resultado):**  
- Botão de microfone (speech-to-text)  
- Botão de câmera com upload e preview  

---

## 9️⃣ Correções Estruturais

**Aluno (direcionamento):**  
Banco de dados definido como única fonte da verdade.  
O chat deve operar apenas via funções CRUD no banco.

**Lovable (resultado):**  
- update_transaction e delete_transaction implementados  
- Relatórios sincronizados via realtime  

---

## 🔟 Correções Adicionais (Batching – Sem Novas Features)

**Aluno (batching prompt – 3 fixes):**

Batching 3 fixes (no new features):

- Goals screen (already exists but empty)  
  - Bind existing goals data to the UI  
  - Render goal list with progress  
  - Update in real time when goals are created/updated via chat  
  - If no goals exist, show empty state with CTA  

- Authentication simplification for MVP  
  - Align auth with the reference implementation  
  - Email + password login  
  - Keep Google login if already enabled  
  - Magic link removed or deferred post-MVP  
  - Reduces auth complexity and security configuration issues  
  - “Leaked password protection” warning accepted at platform level  

- Camera / receipt image layout fix  
  - Image preview constrained to dedicated container  
  - Safe areas and bottom navigation respected  
  - Save button always visible  
  - Proper z-index and spacing  

**Lovable (resultado):**

Três correções aplicadas:
- **GoalsPage:** metas carregadas do banco, progresso visual, realtime e empty state com CTA  
- **Auth:** magic link substituído por e-mail + senha; Google OAuth mantido  
- **Camera/Preview:** z-index ajustado, container corrigido e navegação não sobreposta  

---

## 🔗 Resultado Final

Aplicação publicada:  
https://kind-finance-pal.lovable.app

---

## 🧩 Resumo das Funcionalidades

O **App de Finanças Conversacionais** é uma aplicação **Web/PWA** que permite ao usuário organizar suas finanças pessoais por meio de **conversa natural com IA**, com foco em **acessibilidade**, **simplicidade** e **orientação financeira contínua**.

---

### 🔐 Autenticação e Onboarding
- Login simples por **e-mail e senha** ou **Google**
- Onboarding conversacional para entender renda, objetivos e preferências
- Configuração de idioma (**PT-BR / EN**) e opções de acessibilidade

---

### 💬 Interface Conversacional (Chat Financeiro)
- Chat como interface principal do aplicativo
- Registro de receitas e despesas por linguagem natural  
  _Exemplo:_ “Gastei 45 reais no mercado hoje”
- Interpretação automática pela IA com confirmação antes de salvar
- Histórico de conversas persistido no banco de dados

---

### ✍️ Registro de Transações Multimodal
- **Texto:** digitação natural ou copiar/colar extratos
- **Voz:** botão de microfone com transcrição automática (speech-to-text)
- **Câmera:**
  - Captura de comprovantes (nota fiscal / recibo)
  - Imagem salva como anexo visual da transação
  - OCR planejado para versões futuras (fora do escopo do MVP)

---

### 🗂️ Categorização Inteligente
- Categorias padrão (Alimentação, Transporte, Moradia, Saúde, etc.)
- Sugestão automática de categoria pela IA
- Possibilidade de edição ou criação de novas categorias
- Banco de dados como **fonte única da verdade** (chat e UI sincronizados)

---

### 🎯 Metas Financeiras
- Criação de metas por conversa natural  
  _Exemplo:_ “Quero juntar R$ 5.000 até dezembro”
- Metas persistidas automaticamente no banco
- Progresso atualizado em tempo real
- Visualização com barra de progresso e *empty state* com CTA

---

### 📊 Relatórios e Resumo Financeiro
- Resumo financeiro no topo (receitas, despesas e saldo)
- Relatórios com:
  - Gráfico de pizza (despesas por categoria)
  - Gráfico de barras (evolução mensal)
  - Extrato detalhado em tabela
- Filtros por período e categoria
- Atualização automática a cada alteração no banco de dados

---

### ♿ Acessibilidade e Design Universal
- Interface mobile-first com botões grandes
- Alto contraste e tamanhos de fonte ajustáveis
- Compatibilidade com leitores de tela
- Feedback visual e sonoro
- Confirmações claras antes de ações importantes
- Design branco e minimalista no MVP final

---

### 📱 PWA (Progressive Web App)
- Aplicação instalável na tela inicial do dispositivo
- Funcionamento offline básico (visualização de dados recentes)
- Manifesto, ícones e splash screen configurados

---

### 🔒 Segurança e Privacidade
- Criptografia em trânsito (HTTPS)
- Controle de acesso por usuário (Row Level Security)
- Storage privado para comprovantes com URLs assinadas
- Consentimento explícito e conformidade com LGPD
- Dados não utilizados para publicidade

---

### 🧠 Diferencial do Projeto
O projeto aplica o conceito de **Vibe Coding**, utilizando a IA como **coautora do produto**, participando ativamente da definição, implementação e evolução das funcionalidades, sempre com o banco de dados como fonte única da verdade.



---



# 💭 Reflexão sobre o Processo

## O que funcionou bem?

- Estratégia de **batching**, agrupando várias alterações em um único prompt, essencial devido ao limite de créditos  
- Substituição do login via magic link para **e-mail e senha**, reduzindo problemas de segurança  
- Mudança do design amigável e colorido para **estilo branco e minimalista**, trazendo:
  - Melhor legibilidade  
  - Menor carga cognitiva  
  - Aparência mais profissional  
- Escolha por **PWA (Progressive Web Application)**, permitindo:
  - Instalação sem app store  
  - Experiência próxima a aplicativo nativo  
  - Uso em desktop e mobile  
  - Funcionamento offline básico  

---

## O que não funcionou como o esperado?

Ao ficar sem créditos, o consultor financeiro continuou respondendo no chat, porém sem persistir dados no banco.  
Isso gerou inconsistência entre chat, gráficos e relatórios, sem aviso claro ao usuário.

---

## O que aprendi sobre conversar com IAs?

Apesar da interação parecer simples, resultados profissionais exigem compreensão real do problema, clareza nas instruções e validação técnica contínua.  
A IA é uma coautora poderosa, mas o raciocínio e as decisões continuam sendo responsabilidade do desenvolvedor.

---

> Projeto desenvolvido utilizando o conceito de **Vibe Coding** em colaboração com a plataforma Lovable.
