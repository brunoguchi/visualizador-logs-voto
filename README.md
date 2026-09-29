## Visualizador de logs + Dashboard
- Baixe os dados ControleProcessamentoIntegracao, exporte em CSV do jeito que sai da tabela, inclua os headers.
- Abra `visualizador-logs-voto.html` no navegador e arraste o CSV. Os `*.csv` ficam fora do git (contêm dados reais).

### Busca
Termos separados por espaço (E). `"frase exata"`, `-termo` exclui, `/regex/`, e campos `ident: tipo: integ: msg: payload: url: ep: status: http:`.
Ex.: `erro ident:1050948 -debug`, `payload:kunnr`, `status:erro http:503`. Na aba Eventos cada termo precisa aparecer em algum log do evento.
"Lista de IDs…" filtra por vários identificadores de uma vez e avisa quais não apareceram.