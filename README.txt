PWA-5.4
・履歴の「レシート」「領収書」再印刷ボタンが反応しない問題を修正
・原因：hiddenクラス(display:none!important)が再印刷モーダルに残っていた
・過去GAS履歴(paymentType形式)からも正しい商品・チケット表示で再印刷
・現在の商品価格ではなく、会計当時に保存された履歴価格を使う
・GAS変更不要。GitHub Pages側のみ更新
