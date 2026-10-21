# Dívidas dos clubes das Séries A e B

Página interativa para embed (iframe) com os atrasos e a dívida total dos 40 clubes
das Séries A e B. Fonte dos dados: ANRESF – Painel de Solvência
(https://www.anresf.org.br/pilares-do-ssf/solvencia-e-dividas-em-atraso/painel-de-solvencia).

## Como embedar

Copie o conteúdo de [`embed.html`](embed.html) para o código-fonte da sua página.
O script ajusta a altura do iframe e, quando o leitor muda de aba ou abre um clube,
rola a página de volta ao início do painel (importante no celular).

Parâmetros: `?embed=1` (só abas e gráficos), `&fundo=branco|transparente`,
`&tema=vermelho` (vermelho, preto e branco, cantos retos, fonte Figtree),
`&titulo=0` (esconde o título compacto do embed), `&cabecalho=1` (cabeçalho completo), `&sobre=1`. Aba e série no `#`: `#aba=atrasos&serie=A`,
`#aba=divida&serie=B`, `#aba=atrasos&serie=A&clube=Flamengo`.

Exemplo de embed numa página de portal: [`teste-portal.html`](teste-portal.html).
