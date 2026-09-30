# Sistema Operacional da Josi

Conjunto de documentos que configura os assistentes de IA da Josiele Barros.

A ideia é simples: **todo assistente sabe quem a Josi é, mas cada um só cuida da sua área.**
Nada de sete IAs opinando sobre tudo ao mesmo tempo.

## Como o sistema é montado

Cada assistente = **3 camadas**:

| Camada | Arquivo | Muda com que frequência |
|---|---|---|
| 1. Contexto Mestre | `00-contexto-mestre.md` | Raramente (quando a vida muda) |
| 2. Regras Universais | `01-regras-universais.md` | Raramente (quando um comportamento irrita) |
| 3. Especialização | `assistentes/0X-*.md` | Quando a função mudar |

Mais um documento vivo, compartilhado:

| Arquivo | Para quê | Atualizar |
|---|---|---|
| `02-painel-de-frentes.md` | Estado atual de cada frente (status, dinheiro, horas) | **Toda semana** |

E os protocolos, que qualquer assistente pode executar:

| Arquivo | Quando usar |
|---|---|
| `protocolos/despejo-de-caos.md` | Cabeça cheia, tudo misturado |
| `protocolos/filtro-de-ideias.md` | Apareceu uma ideia nova |
| `protocolos/revisao-semanal.md` | Uma vez por semana, 30 min |

## Como instalar (Claude Projects, ChatGPT Projects ou similar)

Para cada assistente, crie um Projeto separado:

1. **Instruções do projeto** → cole o conteúdo de `assistentes/0X-*.md`.
2. **Arquivos/conhecimento do projeto** → suba `00-contexto-mestre.md`, `01-regras-universais.md`, `02-painel-de-frentes.md` e a pasta `protocolos/`.
3. Quando o painel for atualizado, substitua o arquivo nos projetos que o usam.

## Ordem de ativação (não ative os sete de uma vez)

Criar sete assistentes antes de usar um é exatamente o padrão que este sistema existe para cortar.

| Fase | Assistentes | Por quê |
|---|---|---|
| **Agora** | 02 CFO · 03 Operações · 05 Arquiteto de Ofertas | Caixa, caos operacional e venda são os gargalos declarados. |
| **Em 2–3 semanas** | 01 CEO | Só depois de o painel ter dados reais para ele decidir em cima. |
| **Quando houver demanda concreta** | 04 Conteúdo · 06 Mestrado · 07 Cultural | Ativar quando a tarefa aparecer, não antes. |

Critério para ativar um novo: você usou os atuais por pelo menos 2 semanas e sentiu falta real de outro.

## Os sete assistentes

| # | Assistente | Pergunta que responde |
|---|---|---|
| 01 | CEO / Estrategista | "O que eu faço, o que eu corto e o que fica para depois?" |
| 02 | CFO | "Quanto dinheiro eu tenho de verdade e o que isso permite?" |
| 03 | Gestor de Operações | "O que precisa acontecer hoje, com quem e até quando?" |
| 04 | Estrategista de Conteúdo | "O que eu publico e o que isso leva a vender?" |
| 05 | Arquiteto de Ofertas | "Como isso que eu sei vira algo que alguém compra?" |
| 06 | Assistente do Mestrado | "O que meu argumento ainda não sustenta?" |
| 07 | Gestor Cultural | "Esse projeto cabe, se paga e cumpre o prazo?" |

## Manutenção

- O Contexto Mestre deve caber em ~1 página. Se crescer, está virando diário.
- Detalhe específico de área vai na especialização, não no Mestre.
- Se um assistente repetir um comportamento irritante, corrija a regra — não discuta com ele toda vez.
