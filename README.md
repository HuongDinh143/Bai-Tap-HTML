# 商品情報一覧

**概要**

販売業者向けの商品管理画面である。

ボディー説明
|ID|	名称|	タイトル|	テキスト|	データ型|	エンティティ|	項目|	位置|	サイズ	|イベント|	備考|
|:----|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|EL1	|ボディーパーツ①	|-	|-	|-|	-|	-|	-	|-	|-	|-|
|EL1-1	|画面タイトル|	-	|商品一覧|	ボタン|	ProductInfo|	-	|左|	画面設計書参照|	EVO|	-|
|EL2	|ボディーパーツ②|	-|	-|	-|	-|	-|	-|	-|	-	|ボタングループ|
|EL2-1	|削除ボタン|	削除|	削除|	ボタン	|-	|-	|左	|画面設計書参照|	EV1|	-|
|EL2-2	|エクスポートボタン	|エクスポート	|エクスポート	|ボタン	|-	|-	|左	|画面設計書参照	|EV2	|-|
|EL2-3	|新規登録ボタン	|新規登録	|新規登録	|ボタン	|-	|-	|右	|画面設計書参照	|EV3	|-|
|EL2-4	|検索ボタン	|検索	|検索	|ボタン	|-	|-	|右	|画面設計書参照	|EV4	|-|
|EL3	|ボディーパーツ②	|-	|-	|-	|-	|-	|-	|-	|-	|商品リスト表示|
|EL3-1	|全商品選択	|□	|-	|チェックボックス	|-	|-	|左	|画面設計書参照	|EV5	|-|
|EL3-2	|商品コード表示	|商品コード↑↓	|商品コード	|テキスト	|ProductInfo	|product_code	|中央	|画面設計書参照	|-|
|EL3-3	|商品コードによる並べ替え|	商品コード↑↓	|↑↓|	-	|ProductInfo	|product_code	|中央	|画面設計書参照	|EV6	|-|
|EL3-4	|商品名表示	|商品名↑↓	|商品名	|テキスト	|ProductInfo	|product_name	|中央	|画面設計書参照	|-	|-|
|EL3-5	|商品名による並び替え	|商品名↑↓	|↑↓	|-	|ProductInfo	|product_name	|中央	|画面設計書参照	|EV7	|-|
|EL3-6	|ブランド名表示	|ブランド名↑↓	|ブランド名	|テキスト	|ProductInfo	|brand_name	|中央	|画面設計書参照	|-	|-|
|EL3-7	|ブランド名による並び替え	|ブランド名↑↓	|↑↓	|-	|ProductInfo	|brand_name	|中央	|画面設計書参照	|EV8	|-|
|EL3-8	|仕入れ価格表示	|仕入れ価格↑↓	|仕入れ価格	|数値	|ProductInfo	|purchase_price	|中央	|画面設計書参照	|-	|-|
|EL3-9	|仕入れ価格による並び替え	|仕入れ価格↑↓	|↑↓	|-	|ProductInfo	|purchase_price	|中央	|画面設計書参照	|EV9	|-|
|EL3-10	|販売価格表示	|販売価格↑↓	|販売価格	|数値	|ProductInfo	|selling_price	|中央	|画面設計書参照	|-	|販売価格の降順を商品表示の初期値に設定|
|EL3-11	|販売価格による並び替え	|販売価格↑↓	|↑↓	|-	|ProductInfo	|selling_price	|中央	|画面設計書参照	|EV-10	|-|
|EL3-12	|入庫日表示	|入庫日↑↓	|入庫日	|日付/時間	|ProductInfo	|receipt_date	|中央	|画面設計書参照	|-	|-|
|EL3-13	|入庫日による並び替え	|入庫日↑↓	|↑↓	|-	|ProductInfo	|receipt_date	|中央	|画面設計書参照	|EV11	|-|
|EL3-14	|在庫数表示	|在庫数↑↓	|在庫数	|数値	|ProductInfo	|stock_number	|中央	|画面設計書参照	|-	|-|
|EL3-15	|入庫数による並び替え	|在庫数↑↓	|↑↓	|-	|ProductInfo	|stock_number	|中央	|画面設計書参照	|EV12	|-|
|EL3-16	|商品サイズ表示	|サイズ(cm)奥行x幅x高さ	|サイズ(cm)奥行x幅x高さ	|数値	|ProductInfo	|product_size	|中央	|画面設計書参照	|-	|-|
|EL3-17	|仮押さえの商品数表示	|仮押さえ	|仮押さえ	|数値	|ProductInfo	|temporary_reservation	|中央	|画面設計書参照	|-	|-|
|EL3-18	|保留の商品数表示	|保留	|保留	|数値	|ProductInfo	|pending	|中央	|画面設計書参照	|-	|-|
|EL3-19	|商品詳細への誘導ボタン表示	|詳細情報	|詳細情報	|テキスト	|ProductInfo	|product_detail	|右	|画面設計書参照	|-	|-|
|EL3-20	|行の商品選択	|□	|-	|チェックボックス	|-	|-	|左	|画面設計書参照|	EV13	|-|
|EL3-21	|商品詳細のポップアップ表示	|詳細	|詳細	|テキスト	|ProductInfo	|product_detail	|右	|画面設計書参照	|EV14	|-|
|EL3-22	|前のページへのリンク	|-	|-	|リンク	|ProductInfo	|-	|右	|画面設計書参照	|EV15	|表示中のページが|
|EL3-23	|ページ番号表示	|-	|-	|リンク	|ProductInfo	|-	|右	|画面設計書参照	|EV16	|-|
|EL3-24	|次のページへのリンク	|-	|-	|リンク	|ProductInfo	|-	|右	|画面設計書参照	|EV17	|-|

**イベント説明**

|ID	|イベント名称	|動作	|API	|説明	|備考|
|:---|:---|:---|:---|:---|:---|
|EV0	|画面初期化	|画面タイトルを押下する	|A0	|A0のAPIを呼び出し、商品一覧の画面を初期化する。A0のAPIを呼び出し、エラーが出た場合、「商品一覧を表示できません」とのメッセージを表示|