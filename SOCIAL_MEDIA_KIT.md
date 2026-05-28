# 📱 GTK Gold Token — Social Media Kit
**goldbank.com.br | @goldbank_gtk**

---

## INSTAGRAM

### POST 1 — Lançamento (Feed)
**Imagem:** Moeda GoldBank girando sobre fundo escuro com partículas douradas
**Legenda:**
```
🪙 GTK está no ar.

Cada 1 GTK = 1 grama de ouro físico auditado.

Compre com PIX. Guarde na sua carteira.
Resgate ouro real.

O ouro sempre esteve aqui. Agora ele é seu.

👉 Link na bio para garantir sua vaga de Early Adopter.

#GTK #GoldToken #GoldBank #OuroDigital #DeFi #CriptoBrasil #PIX #Blockchain #Ethereum #OuroReal #InvestimentoInteligente #LiberdadeFinanceira
```

---

### POST 2 — Educativo "Como Funciona" (Carrossel)
**Slide 1:** "Você sabia que pode comprar ouro com PIX? 🧵"
**Slide 2:** "1 GTK = 1 grama de ouro físico ✅"
**Slide 3:** "Como funciona: PIX → USDT → Ouro → GTK na sua carteira"
**Slide 4:** "Cada barra tem número de série na blockchain 🔍"
**Slide 5:** "Taxas: 0,5% depósito | 0,75% saque"
**Slide 6:** "Mínimo: R$ 50. Máximo: ilimitado (Tier 3)"
**Slide 7:** "Resgate físico a partir de 100g 📦"
**Slide 8:** "👉 Cadastre-se em gtk.goldbank.com.br"

**Legenda:**
```
Você pode comprar ouro com 50 reais. Agora. Via PIX. 🪙

Desliza para entender como o GTK funciona →

✅ Lastreado 1:1 em ouro físico
✅ Auditoria on-chain em tempo real
✅ PIX nativo
✅ ERC-20 em qualquer carteira Ethereum

Salva esse post para mostrar pro amigo que ainda não entende cripto.

🔗 Link na bio | #GTK #GoldToken #CriptoMoeda #GoldBank
```

---

### POST 3 — Cartão Black/Gold (Feed)
**Imagem:** Foto dos dois cartões — Black na frente, Gold atrás — iluminação dramática
**Legenda:**
```
Dois cartões. Um legado. 🖤🥇

O cartão GoldBank converte seu GTK em poder de compra real.
Cada transação: você gasta BRL e acumula ouro.

💳 Gold — para holders Tier 1 e 2
🖤 Black — para institucionais. Limites ilimitados.

Cashback em ouro. Porque faz sentido.

👉 Solicite o seu em gtk.goldbank.com.br/cartao

#CartaoGoldBank #CashbackEmOuro #GTK #GoldToken #FinTech #CriptoBrasil
```

---

### POST 4 — Early Adopter FOMO (Stories — 3 slides)
**Story 1:** Fundo escuro. Texto central:
```
847 pessoas já garantiram a vaga.

Só faltam 153.
```
**Story 2:** Contador regressivo + moeda girando:
```
⏳ Lista de Early Adopter fecha em breve

🥇 Badge exclusivo
🗳 Voto na governança
💰 50 pts bônus GTK
```
**Story 3:** CTA direto:
```
👉 Arrasta pra cima
gtk.goldbank.com.br
```

---

### POST 5 — Prova Social (Feed)
**Imagem:** Quote card com fundo escuro/dourado
**Texto no card:** *"Fiz o PIX às 22h e em 2 minutos já tinha GTK na MetaMask. Isso é revolução." — Rafael M., Holder #47*

**Legenda:**
```
Quando seu banco fecha às 18h, o GTK não.

PIX funciona 24/7. A blockchain também.
Seu ouro digital nunca dorme. 🪙

#GTK #GoldToken #OuroDigital #Blockchain24h #CriptoBrasil
```

---

## TWITTER / X

### THREAD DE LANÇAMENTO
```
🧵 Lancei o GTK (Gold Token) hoje.

Cada 1 GTK = 1 grama de ouro físico auditado.
Compra com PIX. Saca por PIX. Resgata ouro físico.

Thread explicando como funciona 👇
```
```
1/ O problema:

O brasileiro não consegue comprar ouro de forma acessível.
ETF de ouro tem taxa de administração.
Ouro físico é complicado de guardar.
Stablecoin não é proteção contra inflação global.

O GTK resolve os 3.
```
```
2/ Como funciona:

→ Você envia PIX (mín. R$ 50)
→ Sistema converte BRL → USDT ao dólar spot
→ Compra ouro ao preço XAU em tempo real
→ Smart contract GTKToken emite 1 GTK por grama
→ Token cai na sua carteira Ethereum em ~2min
```
```
3/ O que garante que é real?

Cada barra de ouro tem número de série único gravado no contrato.

Qualquer pessoa pode verificar na função getReserveRatio() do Etherscan:
etherscan.io/token/[ENDEREÇO]

Se reservas < supply → mint é bloqueado automaticamente.
```
```
4/ Tecnologia:

• ERC-20 UUPS upgradeable (OpenZeppelin)
• Oracle stale-price guard (>1h bloqueia mint)
• ReentrancyGuard em todas as funções críticas
• 6 roles: MINTER, BURNER, PAUSER, UPGRADER, COMPLIANCE, CUSTODIAN
• Emergency pause sem perda de fundos
```
```
5/ KYC e compliance:

3 tiers progressivos.
Tier 1: 1.000 GTK/dia
Tier 2: 10.000 GTK/dia
Tier 3: ilimitado

Alinhado com normas COAF e Lei 14.478/2022.
Integração PIX via parceiro autorizado pelo Banco Central.
```
```
6/ Próximos passos:

Q2 2026: Mainnet + cartão GoldBank (cashback em ouro)
Q3 2026: Bridge Polygon + pool Uniswap V3
Q4 2026: API B2B + Open Finance + parceria custódia regulamentada
```
```
7/ Early Adopter:

Primeiros 1.000 holders ganham:
• Badge exclusivo no Discord
• NFT de fundador
• Voto antecipado na governança
• 50 pontos bônus no primeiro depósito

→ gtk.goldbank.com.br

Se você acredita que o Brasil merece ouro digital de verdade, RT 🪙
```

---

### TWEETS AVULSOS

**Tweet 1 — Educativo:**
```
Curiosidade: o ouro nunca perdeu valor em 5.000 anos de história.

O real perdeu 87% do poder de compra nos últimos 20 anos.

Com R$ 50 e um PIX você pode ter 1 GTK = 1 grama de ouro real na blockchain.

gtk.goldbank.com.br 🪙
```

**Tweet 2 — Técnico:**
```
Implementei o stale-price guard no GTKToken assim:

modifier validPrice() {
  require(goldPricePerGram > 0, "GTK: price not set");
  require(block.timestamp - lastPriceUpdate <= 1 hours, "GTK: stale price");
  _;
}

Se o oracle não atualizar em 1h, mint é impossível.
Nenhum token emitido sem preço válido.
```

**Tweet 3 — FOMO:**
```
847 pessoas já estão na lista de Early Adopter do GTK.

Só 153 vagas restando.

Quem entrar primeiro vota na governança, ganha badge exclusivo e 50 pts de bônus.

→ gtk.goldbank.com.br/waitlist
```

**Tweet 4 — Comparação:**
```
Guardar dinheiro na poupança:
→ Rende 0,5%/mês
→ Perde para inflação
→ Controlado pelo banco

Guardar em GTK:
→ Segue o ouro (proteção histórica)
→ Verificável on-chain
→ Você controla a chave

Faça as contas.
```

**Tweet 5 — Reserva:**
```
A transparência do GTK é literal:

totalGoldReserves >= totalSupply()

Se isso for false, nenhum novo GTK pode ser emitido.
O contrato bloqueia o próprio criador.

Código é lei. Verifica no Etherscan.
```

---

## TIKTOK / REELS — SCRIPTS

### VÍDEO 1 — "Comprei ouro com PIX às 22h" (30s)
**Gancho (0–3s):** [câmera no celular, PIX sendo gerado]
*"Às 22h de quinta-feira, comprei ouro. Sem abrir banco. Sem pagar taxa absurda."*

**Desenvolvimento (3–20s):**
*"Eu uso o GTK — um token onde 1 GTK = 1 grama de ouro físico. Mandei PIX de R$ 200, em 2 minutos apareceu na minha MetaMask. Qualquer pessoa pode verificar o ouro que está por trás de cada token na blockchain."*

**CTA (20–30s):**
*"Mínimo de R$ 50. Link na bio. Primeiros 1.000 users ganham badge de early adopter."*
[mostra tela do app, GTK caindo na carteira]

---

### VÍDEO 2 — "Por que o brasileiro não consegue proteger patrimônio" (45s)
**Gancho:** *"Você sabia que o real perdeu 87% do poder de compra nos últimos 20 anos?"*

**Desenvolvimento:**
- Mostra gráfico real vs ouro
- *"Enquanto isso, o ouro manteve valor por 5.000 anos."*
- *"O problema é que ouro físico é difícil de guardar. ETF tem taxa de administração. E stablecoin não é proteção global."*
- *"O GTK resolve isso. É ouro na blockchain. Compra com PIX, resgate ouro físico se quiser."*

**CTA:** *"Comentei como fiz abaixo. Acessa gtk.goldbank.com.br"*

---

### VÍDEO 3 — "O cartão que te paga em ouro" (20s)
**Gancho:** *"Imagina um cartão que a cada compra te dá ouro de volta."*

*"O cartão GoldBank faz exatamente isso. Cada transação debita GTK convertido em BRL, e parte volta pra você como cashback em ouro. Esse mês acumulei 12 gramas só de cashback."*

**CTA:** *"Solicita o teu no link da bio."*

---

## HASHTAGS MASTER LIST

**Primárias:**
`#GTK #GoldToken #GoldBank #OuroDigital #OuroNaBlockchain`

**Secundárias:**
`#CriptoBrasil #DeFi #Blockchain #Ethereum #ERC20 #Web3Brasil`

**Temáticas:**
`#InvestimentoInteligente #ProtecaoPatrimonal #LiberdadeFinanceira #PIX #OuroReal`

**Trending (usar com moderação):**
`#Cripto #Bitcoin #Altcoin #DeFi #NFT #Web3`

---

## IDENTIDADE VISUAL — BRIEFING PARA DESIGNER

**Paleta:** Preto `#07090F` | Ouro `#FFD700` | Azul `#0D1120` | Branco `#E8ECF4`
**Fontes:** Inter 800/900 para títulos | Inter 400/500 para corpo
**Estilo:** Dark luxury — como Rolex ou cartão Black. Sóbrio, poderoso, confiável.
**Tom:** Revolucionário mas seguro. "Seu banco não quer que você saiba disso" sem ser sensacionalista.
**Assets disponíveis:** `logo.png` (hexágono 3D dourado), `card-gold.png`, `card-black.png`
**Coin:** Circular, fundo azul cobalto, $ dourado, leões, texto "GOLDBANK" — usar como hero visual

---

*Gerado por Claude para o projeto GTK Gold Token — GoldBank 2026*
