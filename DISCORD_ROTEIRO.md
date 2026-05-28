# 🟡 GTK Gold Token — Roteiro Completo do Discord
**goldbank.com.br | discord.gg/goldbank**

---

## 1. ESTRUTURA DO SERVIDOR

### CATEGORIAS E CANAIS (ordem exata)

```
📌 BOAS-VINDAS
   ├── 📋 #regras              → Regras + links importantes (read-only)
   ├── 🎙️ #anuncios            → Apenas admins postam (read-only)
   ├── 💎 #sobre-gtk           → O que é o GTK, links do site, whitepaper
   └── 🚀 #como-comecar        → Guia passo a passo: KYC → PIX → Carteira

🪙 OURO & MERCADO
   ├── 📈 #preco-do-ouro       → Bot atualiza preço XAU/USD a cada hora
   ├── 📊 #gtk-stats           → Bot: total supply, reservas, holders
   ├── 💬 #analises            → Membros compartilham análises de mercado
   └── 📰 #noticias-gold       → Bot: RSS de notícias sobre ouro e DeFi

💬 COMUNIDADE
   ├── 🗣️ #geral               → Papo geral da comunidade
   ├── 🇧🇷 #brasil              → Conteúdo específico Brasil: PIX, BRL, regulação
   ├── 🤝 #apresentacoes       → Novos membros se apresentam
   └── 🎉 #celebracoes         → Primeiros GTKs, marcos pessoais

🏦 SUPORTE
   ├── ❓ #faq                 → Respostas automáticas para perguntas frequentes
   ├── 🆘 #suporte-tecnico     → Problemas com KYC, PIX, carteira
   ├── 🎟️ #abrir-ticket        → Bot cria tickets privados (não postar dados)
   └── 📚 #documentacao        → Links: API docs, Etherscan, contratos

⛓️ BLOCKCHAIN
   ├── 🔗 #smart-contracts     → Discussão técnica dos contratos GTK
   ├── 🧑‍💻 #desenvolvedores     → API, integrações, SDK
   ├── 🏛️ #governanca          → Propostas de voto GTKGovernance
   └── 🔍 #on-chain-explorer   → Bot: últimas transações GTK no Etherscan

🏅 HOLDERS VIP
   ├── 🏆 #early-adopters      → Exclusivo primeiros 1.000 holders
   ├── 👑 #tier3-institucional → Exclusivo Tier 3 KYC
   └── 🗳️ #votacao             → Propostas ativas de governança

🎙️ VOZ
   ├── 🔊 Sala Geral
   ├── 📡 AMA com Equipe
   └── 🎓 Workshop GTK
```

---

## 2. ROLES (CARGOS)

| Role | Cor | Quem recebe | Permissões extras |
|------|-----|-------------|-------------------|
| 👑 **Admin** | Vermelho | Fundadores | Tudo |
| 🛡️ **Moderador** | Laranja | Equipe | Banir, mover, silenciar |
| 💼 **Equipe GTK** | Dourado | Funcionários | Postar em #anuncios |
| 🏅 **Early Adopter** | Amarelo-ouro | 1ºs 1.000 holders | #early-adopters |
| 🥇 **Holder Tier 3** | Dourado brilhante | KYC Tier 3 | #tier3-institucional |
| 🥈 **Holder Tier 2** | Prata | KYC Tier 2 | — |
| 🥉 **Holder Tier 1** | Bronze | KYC Tier 1 | — |
| ✅ **Verificado** | Verde | Passou no bot de verificação | Acesso geral |
| 🆕 **Novo Membro** | Cinza | Default ao entrar | Apenas #boas-vindas |

**Automação de roles:** Usar o bot **Colossus** ou **Guild.xyz** para verificar on-chain:
- Wallet conectada → role "Verificado"
- Saldo ≥ 1 GTK → role "Holder Tier X" automaticamente
- Primeiros 1.000 → role "Early Adopter"

---

## 3. MENSAGEM DE BOAS-VINDAS (bot automático)

```
🪙 **Bem-vindo(a) ao GTK Gold Token, @{username}!**

Você acaba de entrar na maior comunidade de ouro digital do Brasil.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

🥇 **O que é GTK?**
Cada 1 GTK = 1 grama de ouro físico auditado.
Compre com PIX. Guarde na sua carteira. Resgate ouro real.

📋 **Primeiros passos:**
1️⃣ Leia as #regras e reaja com ✅ para liberar o acesso
2️⃣ Veja #sobre-gtk para entender o protocolo
3️⃣ Siga o guia em #como-comecar
4️⃣ Se apresente em #apresentacoes

🔗 **Links importantes:**
🌐 Site: https://gtk.goldbank.com.br
📱 App: https://app.goldbank.com.br
📄 Whitepaper: https://gtk.goldbank.com.br/whitepaper
🔍 Contrato: https://etherscan.io/token/[GTK_ADDRESS]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
💬 Dúvidas? Abra um ticket em #abrir-ticket
```

---

## 4. REGRAS DO SERVIDOR (#regras)

```
# 📋 REGRAS DA COMUNIDADE GTK

Reaja com ✅ abaixo para confirmar que leu e liberar o acesso ao servidor.

━━━━━━━━━━━━━━━━━━━━━━━━

**1. RESPEITO ACIMA DE TUDO**
Trate todos com respeito. Sem ataques pessoais, discriminação ou linguagem ofensiva.

**2. SEM SPAM**
Não envie mensagens repetidas, floods, ou conteúdo irrelevante ao canal.

**3. SEM SHILLING**
Proibido divulgar outros projetos, tokens ou serviços sem autorização da equipe.

**4. SEGURANÇA**
⚠️ NUNCA compartilhe sua seed phrase, chave privada ou dados do KYC.
Nenhum membro da equipe vai pedir isso via DM.

**5. GOLPES E PHISHING**
Qualquer tentativa de golpe resulta em ban imediato e permanente.
Se receber DM suspeita, reporte em #suporte-tecnico.

**6. CANAIS ESPECÍFICOS**
Use cada canal para o seu propósito. Análises em #analises, suporte em #suporte-tecnico.

**7. IDIOMA**
Português preferencial. Inglês permitido em #desenvolvedores.

**8. NÃO É CONSELHO FINANCEIRO**
Nada aqui é aconselhamento de investimento. Faça sua própria pesquisa (DYOR).

━━━━━━━━━━━━━━━━━━━━━━━━
✅ **Reaja abaixo para confirmar que leu as regras.**
```

---

## 5. TEMPLATES DE ANÚNCIOS

### 🚀 Anúncio de Lançamento (Mainnet)

```
@everyone

🪙 **GTK ESTÁ LIVE NA MAINNET ETHEREUM**

Hoje é um dia histórico para o ouro digital brasileiro.

Após meses de desenvolvimento, auditorias e testes na Sepolia,
o **Gold Token (GTK)** está oficialmente deployado na Ethereum Mainnet.

━━━━━━━━━━━━━━━━━━━━━━━━

🔗 **Contrato:** `0x[GTK_ADDRESS]`
🔍 **Etherscan:** https://etherscan.io/token/[GTK_ADDRESS]
💰 **Comprar GTK:** https://app.goldbank.com.br

━━━━━━━━━━━━━━━━━━━━━━━━

🥇 **Os primeiros 1.000 holders ganham Early Adopter Badge**
⚡ **Como comprar:** KYC → PIX → GTK na sua carteira

**Cada 1 GTK = 1g de ouro físico auditado. Para sempre.**

🟡 Seja um pioneiro. Seja um holder.
```

### 📊 Update Semanal (toda segunda-feira)

```
📊 **GTK WEEKLY UPDATE — Semana [N]**

━━━━━━━━━━━━━━━━━━━━━━━━

📈 **Ouro essa semana**
• XAU/USD: $[PRECO] ([VARIACAO]%)
• GTK/BRL: R$ [PRECO_BRL]

🏦 **Métricas do Protocolo**
• Total Supply: [SUPPLY] GTK
• Reservas: [RESERVAS]g (100% lastreado ✅)
• Holders ativos: [HOLDERS]
• Volume semanal: R$ [VOLUME]

✅ **Concluído essa semana**
• [item 1]
• [item 2]

🔧 **Em desenvolvimento**
• [item 1]
• [item 2]

🗓️ **Próxima semana**
• [item 1]

━━━━━━━━━━━━━━━━━━━━━━━━
💬 Discussão em #analises | Suporte em #abrir-ticket
```

### 🎙️ Convite para AMA

```
@here

🎙️ **AMA — Pergunte qualquer coisa para a equipe GTK**

📅 **Data:** [DIA], [DATA] às [HORA] (horário de Brasília)
📍 **Onde:** Canal de voz 📡 AMA com Equipe

━━━━━━━━━━━━━━━━━━━━━━━━

**Tópicos confirmados:**
✦ Status do deploy mainnet
✦ Roadmap Q3 2026: Polygon + Uniswap
✦ Cartão GoldBank: previsão de lançamento
✦ Governança DAO: como vou votar?
✦ Perguntas abertas da comunidade

━━━━━━━━━━━━━━━━━━━━━━━━

💬 **Envie sua pergunta com antecedência em #governanca**
🔔 Ative notificações para não perder!
```

### 🏅 Boas-vindas Early Adopter

```
🎉 **NOVO EARLY ADOPTER: @{username}**

Parabéns! Você é um dos [N]/1.000 pioneiros do GTK.

🏅 Role **Early Adopter** desbloqueado!
🔓 Acesso ao canal #early-adopters
🗳️ Voto antecipado em propostas de governança
🎁 NFT de fundador (em breve)

Bem-vindo(a) à história do ouro digital brasileiro. 🪙
```

---

## 6. BOTS RECOMENDADOS

| Bot | Função | Como usar |
|-----|---------|-----------|
| **MEE6** | Boas-vindas, XP, moderação automática | Mensagem de boas-vindas + automod spam |
| **Carl-bot** | Reaction roles (regras), tickets | Role "Verificado" via reação ✅ |
| **Guild.xyz** | Verificação on-chain de holders | Conecta wallet → recebe role automático |
| **Colossus** | Snapshot voting (governança) | Propostas GTKGovernance no Discord |
| **GoldFeed Bot** | Preço XAU ao vivo | Atualiza #preco-do-ouro a cada hora |

### Configurar GoldFeed Bot (preço do ouro)
```
Comando: /set channel #preco-do-ouro
         /set interval 60min
         /set pairs XAU/USD GTK/BRL ETH/USD
         /set style embed
```

---

## 7. FLUXO DE ONBOARDING (passo a passo para novos membros)

```
NOVO MEMBRO ENTRA
      ↓
Bot envia DM de boas-vindas + link #regras
      ↓
Membro reage ✅ em #regras
      ↓
Carl-bot adiciona role "Verificado"
Acesso liberado para todos os canais públicos
      ↓
Membro vai em #como-comecar → segue guia KYC
      ↓
Membro faz KYC no app.goldbank.com.br
      ↓
Conecta carteira no Guild.xyz
      ↓
Se saldo ≥ 1 GTK → role "Holder Tier X" automático
      ↓
Se está entre os 1.000 primeiros → role "Early Adopter"
      ↓
Acesso a canais VIP desbloqueado
```

---

## 8. ESTRATÉGIA DE ENGAJAMENTO (primeiros 90 dias)

### Semana 1–2: Lançamento
- [ ] Anúncio de mainnet com @everyone
- [ ] Missão: 100 membros no Discord antes do fim da semana
- [ ] AMA de lançamento ao vivo com fundadores
- [ ] Giveaway: 1 GTK (= 1g ouro) para 5 membros que indicarem amigos

### Semana 3–4: Ativação
- [ ] Primeira votação de governança (escolher próxima rede: Polygon ou Arbitrum)
- [ ] Challenge: compartilhe seu "momento GTK" (screenshot do primeiro compra)
- [ ] Workshop: "Como usar GTK com MetaMask" — canal de voz

### Mês 2: Crescimento
- [ ] Programa de embaixadores: top 10 membros mais ativos viram Embaixadores GTK
- [ ] Update semanal toda segunda com métricas do protocolo
- [ ] Thread mensal: "Perguntas da comunidade → respostas da equipe"

### Mês 3: Comunidade Autônoma
- [ ] Primeiras propostas da comunidade via GTKGovernance
- [ ] Canal #analises com curadoria de conteúdo semanal
- [ ] Parceria com influenciadores de cripto e finanças brasileiros

---

## 9. CANAL #sobre-gtk (mensagem fixada)

```
# 🪙 O que é o GTK (Gold Token)?

**GTK é o primeiro token brasileiro lastreado 1:1 em ouro físico auditado.**

Cada 1 GTK representa exatamente 1 grama de ouro físico armazenado em cofres certificados.
Nenhum GTK existe sem o ouro físico correspondente — verificável por qualquer pessoa na blockchain.

━━━━━━━━━━━━━━━━━━━━━━━━

**🔑 Como funciona:**
1. Você envia PIX → sistema converte BRL em USDT → compra ouro ao preço spot
2. Smart contract GTKToken emite os GTK correspondentes para sua carteira
3. Você pode guardar, transferir, sacar como BRL via PIX, ou resgatar ouro físico (mín. 100g)

**📊 Dados do Protocolo:**
• Padrão: ERC-20 (UUPS upgradeable)
• Rede: Ethereum Mainnet
• Taxa depósito: 0,5% | Taxa saque: 0,75%
• Depósito mínimo: R$ 50,00
• Resgate físico: mínimo 100g

**🔗 Links:**
• 🌐 Site: https://gtk.goldbank.com.br
• 📱 App: https://app.goldbank.com.br
• 🔍 Contrato: https://etherscan.io/token/[ENDEREÇO]
• 📄 Docs: https://gtk.goldbank.com.br/docs
• 🐙 GitHub: https://github.com/goldbank/gtk

**⚠️ Aviso:** Investimentos em criptoativos envolvem risco. DYOR.
```

---

## 10. CHECKLIST DE SETUP DO SERVIDOR

- [ ] Criar servidor no Discord com nome "GTK Gold Token"
- [ ] Upload do ícone do servidor (moeda GoldBank)
- [ ] Upload do banner (site/landing page como banner)
- [ ] Criar todas as categorias e canais na ordem acima
- [ ] Configurar roles e cores
- [ ] Instalar MEE6 → configurar mensagem de boas-vindas
- [ ] Instalar Carl-bot → configurar reaction role em #regras
- [ ] Instalar Guild.xyz → conectar contrato GTKToken na mainnet
- [ ] Configurar bot de preço do ouro em #preco-do-ouro
- [ ] Postar mensagem fixa em cada canal principal
- [ ] Postar regras em #regras e adicionar reação ✅
- [ ] Testar fluxo completo com conta de teste
- [ ] Publicar link de convite no site (discord.gg/goldbank)
- [ ] Primeiro AMA agendado

---

*Gerado por Claude para o projeto GTK Gold Token — GoldBank 2026*
