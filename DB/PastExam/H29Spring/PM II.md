# 問1

## 設問1

- [ ] (1)

1.

会員からポイント統合の申請が行われた場合
2.会員登録、出荷手配、出荷

- [ ] (2)
a.
大分類・中分類・小分類：O,-,連携AP,-,配置方法2
商品分類：o,-,連携AP,-,配置方法2
店舗在庫：-,o,現行AP,-,配置方法3
倉庫在庫：o,-,現行AP,-,配置方法
出荷指示・出荷指示明細：-,-,-,-,配置方法1
b.
c.
d.
e.

## 設問2

- [ ] (1)
統合申請日：ポイント統合申請日を表す日付
統合対象ポイント：統合時点の使用可能ポイント
統合区分が実施済みの場合、統合申請日と統合対象ポイントがNULLではない
- [ ] (2)
v1：全従業員ID
v2：認可役職ロールまたは認可担当職務ロールを持つ従業員ID,CURRENT_USER
g.従業員
h.A.店舗コード = B.店舗コード
i.A.店舗コード = B.店舗コード and A.店舗会員番号 = B.店舗会員番号
j.A.会員区分 = OL会員
- [ ] (3)
店舗販売業務の場合、店舗日締フラグをtrueに更新し、OL販売業務の場合、OL日締フラグをtrueに更新する
1 日締管理テーブルの更新
2 店舗日締フラグ=true and OL日締フラグ=true
3 レプリケーションの無効化

## 設問3

- [ ] (1)
k.伝票番号 f, 注文番号 f
l.チャネル区分
m.分類コード f
- [ ] (2)
ア、店舗軸
イ、店舗軸IDで等結合し、チャネル区分が店舗販売の行を選択
ウ、商品軸
エ、商品軸IDで等結合し、大分類コードが 'K001' の行を選択

# 問2

## 設問1

- [ ] (1)
- [ ] (2)
a.拠点種類区分、拠点名
b.上位拠点コード f
c.営業部門区分
d.請求得意先フラグ、得意先区分
e.担当営業所拠点コード f, 発注得意先コード f, 納入拠点コード f
f.拠点コード f
計画生産品の在庫：営業所及び物流センタ
補充生産品の在庫：営業所及び物流センタ、工場
g.基準在庫数量、補充ロットサイズ、実在庫数量
在庫保管に関する記述
h.広域得意先コード f
i.納入物流センタ拠点コード f
j.要求元営業所拠点コード f
拠点コード f, 商品コード f
k.物流センタ拠点コード f

## 設問2

- [ ] (1)
- [ ] (2)

## 設問3

- [ ] (1)
- [ ] (2)
ア、要求年月日、要求時刻
イ、生産年月日、生産数量、商品コードf
ウ、生産完了時刻
エ、物流センター拠点コードf
オ、生産入庫年月日、生産入庫数量
カ、入庫完了時刻
