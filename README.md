# LISBON ALIVE™

Conceito e especificação de câmaras dinâmicas em tempo real para o jogo, cobrindo várias frentes da cidade e diferentes estados de jogabilidade.

## Âmbito Principal
- **Cobertura multi-zona:** Múltiplos ângulos e vistas comutáveis em diferentes pontos da cidade durante ocorrências ativas (roubos, assaltos, perseguições e conflitos urbanos).
- **Veículos em andamento:** Câmaras interiores e dinâmicas com prevenção de *clipping*, resolução de oclusão pela geometria da viatura, vibração reativa, inércia e amortecimento (*camera damping* / *spring arm*) ajustado à velocidade, curvas bruscas e colisões.
- **Interiores e saques em lojas:** Vistas no interior de estabelecimentos comerciais, bancos e lojas durante saques, com gestão de oclusão de paredes, tetos e mobiliário (*visibility/occlusion culling*, *cutaway* dinâmico ou *fade/dither*), transições fluidas (*smooth blend*) e sincronização de estado em tempo real.
- **Jogabilidade e comportamentos:** Acompanhamento não só do cenário mas também das ações, decisões e omissões dos jogadores e NPCs (o que fazem ou deixam de fazer em cada momento, furtividade, troca de armas/itens, condução, entrada/saída de espaços, reações de polícia/civis e estados de alerta ou evasão).