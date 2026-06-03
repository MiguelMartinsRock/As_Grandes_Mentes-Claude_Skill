# As Grandes Mentes — Contexto Completo do Projeto

> Leia este arquivo no início de qualquer nova sessão para ter contexto total do projeto.

---

## O que é este projeto

**As Grandes Mentes** é uma skill para Claude Code — um produto digital que transforma o Claude em um conselho estratégico de 150 especialistas mundiais, organizados em 50 categorias de negócio digital.

O usuário ativa a skill com um comando e recebe orientação estratégica profunda baseada nos frameworks reais de referências como Alex Hormozi, Chris Voss, Seth Godin, Andrew Ng, entre outros.

**Não é um curso. Não é um chatbot genérico.** É um conselho particular que responde com profundidade de quem pagaria R$50.000 em consultoria.

---

## Onde ficam os arquivos

| Arquivo | Caminho |
|---------|---------|
| Skill principal | `c:\Miguel\Claude Code\Skill GM - To sell\Saidas\SKILL.md` |
| Contexto do usuário | `c:\Miguel\Claude Code\Skill GM - To sell\Saidas\CONTEXTO.md` |
| Histórico de decisões | `c:\Miguel\Claude Code\Skill GM - To sell\Saidas\HISTORICO.md` |
| Pasta de gestão do projeto | `c:\Miguel\Claude Code\Skill GM - To sell\` |
| Entregáveis | `c:\Miguel\Claude Code\Skill GM - To sell\Saidas\` |
| Este arquivo | `c:\Miguel\Claude Code\Skill GM - To sell\O que sou\` |

---

## Estrutura da Skill

### Comandos disponíveis

| Comando | Função |
|---------|--------|
| `/instalar` | Onboarding: faz 6 perguntas sobre o negócio, salva em `CONTEXTO.md` |
| `pergunte às grandes mentes` | Fluxo principal: detecta categoria → apresenta modos → convoca especialistas |
| `/confronto` | Dois especialistas com visões opostas debatem uma decisão |
| `/auditoria` | Diagnóstico completo do negócio nos 10 blocos e 50 categorias |

### Fluxo principal
1. Carrega `CONTEXTO.md` (perfil do negócio do usuário)
2. Identifica automaticamente a categoria (exibe: "Categoria localizada: #X — Nome")
3. Apresenta 4 modos de abordagem para o usuário escolher
4. Convoca 2–3 especialistas mapeados para aquele modo
5. Responde com profundidade + plano de ação de 3 passos
6. Oferece salvar a decisão no `HISTORICO.md`

### As 50 categorias (10 blocos)

| Bloco | Categorias |
|-------|-----------|
| Vendas e Persuasão | 1. Prospecção · 2. Oferta Irresistível · 3. Copy de Vendas · 4. Funis · 5. Precificação · 6. Vendas Consultivas · 7. Negociação · 8. Persuasão · 9. Copy para Redes |
| Marketing e Crescimento | 10. Conteúdo · 11. Mídias Sociais · 12. SEO · 13. Tráfego Pago · 14. Email · 15. Automação · 16. Influencer/UGC · 17. Growth |
| Marca e Posicionamento | 18. Branding · 19. Posicionamento · 20. Personal Branding · 21. Storytelling · 22. Marca como Ícone |
| Produto e Tecnologia | 23. Produto e UX · 24. Design · 25. E-commerce · 26. SaaS · 27. Dados e Analytics |
| Inteligência Artificial | 28. IA em Negócios · 29. Automação com IA · 30. Prompt Engineering · 31. Agentes de IA · 32. IA para Vendas · 33. Futuro do Trabalho |
| Criação e Audiência | 34. Creator Economy · 35. Lançamento · 36. Comunidades · 37. Podcast · 38. YouTube · 39. Afiliados |
| Estratégia e Escala | 40. Estratégia Competitiva · 41. Escala · 42. Agências · 43. Alavancagem |
| Operações e Finanças | 44. Finanças · 45. Produtividade · 46. Liderança · 47. Retenção |
| Psicologia e Comportamento | 48. Psicologia do Consumidor · 49. Mindset |
| Tendências | 50. Ética em IA |

---

## Posicionamento do Produto

**Promessa central:**
> "Tome a melhor decisão estratégica do seu negócio em menos de 5 minutos — usando os mesmos frameworks que empresas pagam R$50.000 em consultoria para ter acesso."

**Público-alvo:** Empreendedores digitais, solopreneurs, donos de agências, criadores de infoprodutos — qualquer pessoa que usa Claude Code e quer tomar decisões melhores mais rápido.

**Diferencial:** Não é IA genérica. É um conselho especializado que seleciona os especialistas certos para o contexto certo, no modo de abordagem certo.

---

## Oferta (em construção)

### O que o comprador recebe
- Skill principal (SKILL.md) — 50 categorias, 150 especialistas, 4 modos por categoria
- PDF: Os 150 Especialistas (resumo de cada um) *(a criar)*
- Biblioteca de 50 prompts prontos — um por categoria *(a criar)*
- Vídeo de instalação (10min) *(a criar)*
- Atualizações futuras inclusas

### Estrutura de preço (planejada)
- Lançamento: R$97 (primeiras 50 cópias)
- Preço após lançamento: R$297
- Reason why: coleta de 50 depoimentos para prova social

### Garantia planejada
30 dias. Se não tomar uma decisão melhor do que tomaria sozinho, reembolso total.

---

## Status do Produto

| Item | Status |
|------|--------|
| SKILL.md (skill principal) | ✅ Concluído |
| CONTEXTO.md (template) | ✅ Concluído |
| HISTORICO.md (template) | ✅ Concluído |
| Comando /instalar | ✅ Documentado na skill |
| Comando /confronto | ✅ Documentado na skill |
| Comando /auditoria | ✅ Documentado na skill |
| Salvamento automático | ✅ Documentado na skill |
| PDF: Os 150 Especialistas | ⏳ A criar |
| Biblioteca de 50 prompts | ⏳ A criar |
| Vídeo de instalação | ⏳ A criar |
| Copy de vendas | ⏳ A criar |
| Página de vendas | ⏳ A criar |

---

## Histórico de Decisões do Projeto

### Sessão de criação (2026-06-01)
- Expandido de 31 para 50 categorias
- Expandido de 2 para 3 especialistas por categoria
- Adicionados 6 categorias de IA (28–33)
- Adicionados 4 modos de abordagem por categoria
- Criado fluxo interativo: skill pergunta contexto → apresenta modos → convoca especialistas
- Criado sistema de arquivos: SKILL.md + CONTEXTO.md + HISTORICO.md
- Criados comandos: /instalar, /confronto, /auditoria
- Criado sistema de salvamento automático de decisões

---

## Como trabalhar neste projeto em nova sessão

1. Leia este arquivo (`PROJETO.md`)
2. Leia o `SKILL.md` atual para entender o estado da skill
3. Consulte a pasta `Saidas\` para ver entregáveis já criados
4. Pergunte ao usuário o que quer trabalhar hoje
