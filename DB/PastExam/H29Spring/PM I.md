# 問1

## 設問1

- [ ] (1)
電子会議番号, 投稿番
部分：電子会議番号→議題
部分：電子会議番号→分野番号
部分：電子会議番号→表示順
推移：電子会議番号→分野番号→分野名

- [ ] (2)
第1正規化：繰り返し構造の削除
第2正規化：部分関数従属の削除
第3正規化：推移的関数従属の削除

第1正規化
電子会議（電子会議番号p, 議題, 分野番号,表示順）
電子会議投稿（電子会議番号p, 投稿番号p, 投稿本文, ユーザID f）
分野（分野番号p, 分野名）

## 設問2

- [ ] (1)
a.グループID,f
b.グループID,f
c.ユーザID,f
d.ユーザID,f
e.開封日時
f.参加するか否か
- [ ] (2)

## 設問3

- [ ] (1)
ロール（ロールID p, ロール名）
兼務ロール（ユーザID p, ロールID p）
決裁ルート　承認ロールID f

- [ ] (2)
差戻しが発生し、一つ前のステップで承認された後、次のステップで承認する場合

承認の承認連番を主キーに含める

# 問2

## 設問1

a.sum(S.出庫数量)
b.left join
c.group by B.部品番号, S.出庫年月日
d.出庫先倉庫コード
e.NULL

## 設問2

- [ ] (1)
同時実行APが①終了時点で、在庫テーブルの出庫対象部品レコードに対する共有ロックが解放されず、専有ロックが必要な②に進めない場合
- [ ] (2)
t1 ①
t2 ②③④
出庫対象在庫数量が倉庫内在庫数量を上回ってしまう状態
- [ ] (3)point

## 設問3

- [ ] (1)
ア、倉庫コード
イ、部品番号
ウ、在庫
エ、待ち
- [ ] (2)
オ、出荷元倉庫コード
カ、部品番号
キ、出庫
ク、表ロック
ケ、参照
- [ ] (3)

# 問3

## 設問1

- [ ] (1)
ア、ユニーク
イ、非ユニーク
ウ、360000
エ、3600
オ、150000
5*200*30000=30000000
30000000/200=150000
カ、
キ、2
ク、
ケ、
コ、
- [ ] (2)
a.
b.
- [ ] (3)

## 設問2

- [ ] (1)
電話番号が設定されている場合だけ行を登録すべきだから
- [ ] (2)社員ID, 電話番号
- [ ] (3)
c.1
d.3
e.4
- [ ] (4)
f.電話番号1 is not null
g.電話番号1 is null
h.電話番号2 is not null
- [ ] (5)
E1 2 3333
E2 1 2222
E3 1 3333
E4 1 4444
