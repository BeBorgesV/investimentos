# Plano de Aportes

App de bolso para o aporte mensal: diz quanto comprar de Tesouro IPCA+ 2032, IVVB11 e BOVA11 para manter a carteira em 40/30/30, sem vender nada.

- Abra pelo GitHub Pages e, no iPhone, use Compartilhar → Adicionar à Tela de Início.
- Abas: Carteira (o que você tem e o saldo), Comprar (o que comprar agora e confirmar as compras), Notícias (boletim do mês) e Guia.
- Ao confirmar uma compra, as cotas entram na carteira e o valor sai do saldo. Dá para desfazer a última movimentação.
- A carteira e as movimentações ficam guardadas só no aparelho (localStorage). Nada pessoal vai para este repositório.
- `boletim.json` é atualizado pelo Claude todo dia 1º com Selic, IPCA, Tesouro IPCA+, Ibovespa, dólar, S&P 500, preços das cotas e as notícias do mês.

Ferramenta educativa. Não é recomendação de investimento.
