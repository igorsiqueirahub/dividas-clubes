# Dívidas dos clubes das Séries A e B

Página interativa para embed (iframe) com os atrasos e a dívida total dos 40 clubes
das Séries A e B. Fonte dos dados: ANRESF – Painel de Solvência
(https://www.anresf.org.br/pilares-do-ssf/solvencia-e-dividas-em-atraso/painel-de-solvencia).

## Como embedar

Copie o conteúdo de [`embed.html`](embed.html) para o código-fonte da sua página.
Para abrir direto em "Só curto prazo", use [`embed-curto-prazo.html`](embed-curto-prazo.html).
Ranking da dívida com transferências de atletas na Série A: [`transferencias.html`](transferencias.html), embed em [`embed-transferencias.html`](embed-transferencias.html).
Impostos e dívidas trabalhistas na Série A, com a lista de impostos em atraso: [`tributos.html`](tributos.html), embed em [`embed-tributos.html`](embed-tributos.html).
Ranking dos tipos de dívida na Série A (soma dos 20 clubes): [`composicao.html`](composicao.html), embed em [`embed-composicao.html`](embed-composicao.html).
Os seis clubes da Série A sem atrasos em 2026, item por item (salários, transferências e impostos): [`em-dia.html`](em-dia.html), embed em [`embed-em-dia.html`](embed-em-dia.html).
O script ajusta a altura do iframe e, quando o leitor muda de aba ou abre um clube,
rola a página de volta ao início do painel (importante no celular).

Parâmetros (opcionais): `?tema=neutro` (visual azul-petróleo no lugar do vermelho),
`?embed=1` (aceito por compatibilidade; mostra a página inteira), `&fundo=branco|transparente`, `&cabecalho=1`, `&sobre=1`.
Aba e série no `#`: `#aba=atrasos&serie=A`, `#aba=divida&serie=B`, `#aba=divida&serie=A&medida=c` (só curto prazo), `#aba=atrasos&serie=A&clube=Flamengo`.

