# 問1

## 設問1

- [ ] (1)
緊急度コード→スケジュール影響度
スケジュール影響度：緊急度コード=1:多
重大度コード→ソフトウェア影響度
ソフトウェア影響度：重大度コード＝1：多

｛緊急度コード, 重大度コード｝→優先度コード→リソース投入度
リソース投入度：優先度コード=1:多

候補キー：｛緊急度コード, 重大度コード｝
部分関数従属性：緊急度コード→スケジュール影響度
部分関数従属性：重大度コード→ソフトウェア影響度
推移的関数従属性：｛緊急度コード, 重大度コード｝→優先度コード→リソース投入度

- [ ] (2)
第一正規形
優先度（緊急度コード p, 重大度コード p, 優先度コード）
リソース投入度（優先度コード p, リソース投入度）
スケジュール影響度（緊急度コード p, スケジュール影響度）
ソフトウェア影響度（重大度コード p, ソフトウェア影響度）

## 設問2

- [ ] (1)
- [ ] (2)
a.ステータス
b.完了日
c.対応区分
d.対応メンバID
- [ ] (3)
上位階層のチームが設定できない
チーム（チームID,チーム名,リーダメンバID,上位チームID）
複数のチームを兼任できない
メンバ（メンバID,氏名,主担当チームID）
メンバ兼任チーム（メンバID,兼任チームID）
- [ ] (4)
成果物（成果物ID, 工程ID f, 作成担当チーム f, 成果物名）

## 設問3

- [ ] (1)
e.バグ[発見工程ID = 発見すべき工程ID]
f.バグ
g.バグ種別ID
h.バグ種別
i.修正有無
j.あり
- [ ] (2)
基本設計工程と詳細設計工程のいずれか
バグを作り込んだ
ア、B1, B4
イ、B1, B4, B5
ウ、B1, B5

# 問2

## 設問1

- [ ] (1)
a.not exist
b.<
c.>
- [ ] (2)
挿入しようとする行が一意制約に違反するから
- [ ] (3)
d.X
e.1
f.o
g.
h.x
i.1
j.x
k.2
l.x
m.2
n.o
o.
p.△
q.
- [ ] (4)
r.社員番号
s.予約開始時間

## 設問2

- [ ] (1)

- [ ] (2)
予約処理の実行が重なり、
- [ ] (3)

## 設問3

- [ ] (1)count(会議室番号)
- [ ] (2)
予約処理の実行が重なり、先行する予約処理により予約済フラグが'Y'に更新された場合

# 問3

## 設問1

- [ ] (1)表示順
商品一覧画面に商品全体で重複がないように表示するため
- [ ] (2)
ユニーク索引を複数のテーブルにまたがって作成することが出来ないから
- [ ] (3)
ア、
単品商品番号列にセット商品番号を設定できてしまう
イ、
商品番号列に単品とセット商品で重複する商品番号を設定できない
- [ ] (4)
b.4
c.6
d.2
e.3

## 設問2

- [ ] (1)
f.inner
g.inner
- [ ] (2)k.構成数
- [ ] (3)and 単品区分='Y'

## 設問3

- [ ] (1)
ウ、x
エ、o
オ、o
カ、o
- [ ] (2)商品番号
