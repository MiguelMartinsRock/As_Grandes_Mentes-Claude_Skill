# Skill das Grandes Mentes — Claude Code

> 150 especialistas. 50 categorias. 1 comando.

A skill que transforma o Claude num conselho particular com os maiores nomes do mercado digital. Você faz uma pergunta. A skill identifica o tema, apresenta as abordagens disponíveis e convoca os especialistas certos para aquela situação específica.

---

## O que é

**As Grandes Mentes** é uma skill para o Claude Code. Ao instalar o arquivo `SKILL.md` no seu Claude, você passa a ter acesso a um conselho estratégico de 150 referências mundiais — Hormozi, Chris Voss, Seth Godin, Andrew Ng, Russell Brunson, Donald Miller e mais 144 — organizados em 50 categorias de negócio digital, cada uma com 4 modos de abordagem.

Não é IA genérica. É um conselho que seleciona o especialista certo, para o problema certo, na abordagem certa — e ainda lembra do seu negócio.

---

## Estrutura do Repositório

```
As_Grandes_Mentes-Claude_Skill/
├── Saidas/
│   ├── SKILL.md        ← Skill principal (instale este arquivo)
│   ├── CONTEXTO.md     ← Criado automaticamente pelo /instalar
│   └── HISTORICO.md    ← Histórico de decisões salvas
├── landing-page/
│   └── index.html      ← Landing page do produto
└── O que sou/
    └── PROJETO.md      ← Contexto completo do projeto para novas sessões
```

---

## Como Instalar

### Pré-requisito
Claude Code com assinatura ativa (a partir de $20/mês na Anthropic).

### Passo 1 — Baixe o arquivo da skill
Faça o download do arquivo `Saidas/SKILL.md` deste repositório.

### Passo 2 — Salve em uma pasta no seu computador
Exemplo: `C:\Users\SeuNome\Documents\Claude Skills\SKILL.md`

### Passo 3 — Referencie no seu CLAUDE.md global
Abra (ou crie) o arquivo `~/.claude/CLAUDE.md` e adicione:

```markdown
## Skill: As Grandes Mentes

Quando o usuário disser "pergunte às grandes mentes", "/instalar", "/confronto" ou "/auditoria",
leia e aplique a skill em: [CAMINHO COMPLETO DO ARQUIVO SKILL.md]
```

### Passo 4 — Instale a skill no Claude
Abra o Claude Code e digite:

```
/instalar
```

A skill fará 6 perguntas sobre o seu negócio e salvará o contexto. Pronto.

---

## Comandos

| Comando | O que faz |
|---------|-----------|
| `/instalar` | Onboarding: aprende sobre o seu negócio e salva o contexto para todas as sessões futuras |
| `pergunte às grandes mentes` | Fluxo principal: identifica a categoria → apresenta 4 modos → convoca os especialistas certos |
| `/confronto` | Dois especialistas com visões opostas debatem sua decisão. Um árbitro resolve. |
| `/auditoria` | Diagnóstico completo do negócio nos 10 blocos e 50 categorias, com prioridades ranqueadas |

---

## As 50 Categorias

### Vendas e Persuasão
1. Prospecção
2. Oferta Irresistível
3. Copy de Vendas
4. Funis de Venda
5. Precificação
6. Vendas Consultivas
7. Negociação
8. Persuasão e Influência
9. Copywriting para Redes Sociais

### Marketing e Crescimento
10. Marketing de Conteúdo
11. Mídias Sociais e Atenção
12. SEO e Tráfego Orgânico
13. Tráfego Pago
14. Email Marketing
15. Automação de Marketing
16. Influencer Marketing e UGC
17. Growth e Crescimento

### Marca e Posicionamento
18. Branding e Identidade de Marca
19. Posicionamento de Mercado
20. Personal Branding
21. Storytelling e Apresentação
22. Marca como Ícone Cultural

### Produto e Tecnologia
23. Produto e UX
24. Design e Experiência
25. E-commerce e Lojas Digitais
26. SaaS e Produtos Digitais
27. Dados e Analytics

### Inteligência Artificial
28. IA Aplicada a Negócios
29. Automação com IA
30. Prompt Engineering e IA Generativa
31. Agentes de IA e Workflows
32. IA para Vendas e Marketing
33. Futuro do Trabalho com IA

### Criação e Audiência
34. Creator Economy e Infoprodutos
35. Lançamento de Produto
36. Comunidades e Memberships
37. Podcast e Áudio Marketing
38. Video Marketing e YouTube
39. Afiliados e Parcerias

### Estratégia e Escala
40. Estratégia Competitiva
41. Escala de Negócio
42. Agências e Serviços Criativos
43. Alavancagem e Liberdade Financeira

### Operações e Finanças
44. Finanças para Empreendedores
45. Produtividade e Foco
46. Liderança e Cultura
47. Retenção e Atendimento ao Cliente

### Psicologia e Comportamento
48. Psicologia do Consumidor
49. Mindset Empreendedor

### Tendências
50. Ética em IA e Responsabilidade Digital

---

## Como Funciona o Fluxo Principal

```
Usuário: "pergunte às grandes mentes sobre minha oferta"

1. Skill detecta → Categoria #2: Oferta Irresistível

2. Skill apresenta os 4 modos:
   › Grand Slam Offer
   › High Ticket
   › Low Ticket + Upsell
   › Eliminação de Objeções

3. Usuário escolhe o modo

4. Skill convoca os especialistas mapeados para aquele modo
   (ex: Alex Hormozi + Dan Kennedy para Grand Slam Offer)

5. Resposta profunda com frameworks aplicados ao contexto real

6. Pergunta se quer salvar no HISTORICO.md
```

---

## Sistema de Arquivos

| Arquivo | Função |
|---------|--------|
| `SKILL.md` | Skill principal com todas as 50 categorias |
| `CONTEXTO.md` | Perfil do negócio salvo pelo `/instalar` |
| `HISTORICO.md` | Registro de todas as decisões tomadas com a skill |

O `HISTORICO.md` nunca é sobrescrito — cada decisão é adicionada ao final com data, categoria, especialistas e plano de ação.

---

## Landing Page

A landing page do produto está em `landing-page/index.html` e está deployada em:

**[as-grandes-mentes.vercel.app](https://as-grandes-mentes.vercel.app)**

Para atualizar o link de pagamento, substitua `SEU_LINK_KIRVANO_AQUI` no `index.html` e faça um novo deploy:

```bash
cd landing-page
vercel --prod
```

---

## Sobre

Criado por **Miguel Gautier** · [Gautier IA](https://gautier.ia)

Skill construída para empreendedores digitais, solopreneurs, donos de agências e criadores que usam o Claude Code e querem tomar decisões estratégicas com o nível de profundidade que antes exigia R$50.000 em consultoria.
