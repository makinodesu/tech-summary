17:01~19:01

# 問1

## 設問1

- [ ] (1)
a.キャッシュ
b.プライオリティ
- [ ] (2)
内部DNSサーバ

## 設問2

- [ ] (1)
MACアドレス
FW-L3SW間サブネット
内部サーバ収容サブネット
- [ ] (2)
c.指定
d.非指定
e.MACアドレス

## 設問3

- [ ] (1)ルートブリッジ
- [ ] (2)
ポートのダウンを検知した際、各ポートの役割が予め決定しているから

## 設問4

- [ ] (1)
維持管理が必要なスイッチの台数が減るから
- [ ] (2)
スタックL3SW~新ディレクトリサーバ

## 設問5

スタック、リンクアグリゲーション
ループ構造が喪失するから

## 設問6

- [ ] (1)
送信元MACアドレス：現行のディレクトリサーバ
宛先MACアドレス：新ディレクトリサーバ
- [ ] (2)
送信元MACアドレス：現行のL3SW1
宛先MACアドレス：スタックL3SW
- [ ] (3)
172.16.254.2~172.16.254.9
172.16.254.101~172.16.254.127
- [ ] (4)
- [ ] (5)
新公開Webサーバへのアクセスのネクストホップを現行のL2SW1に設定する
新ルータ1→新L2SW0→新FW1→新L2SW1→現行のL2SW1
- [ ] (6)
新公開Webサーバへの通信
新外部DNSサーバへの通信
- [ ] (7)172.17.10.4
- [ ] (8)
割り当て済みのIPアドレスをアドレスプールから除外するため

11:35~13:35

# 問2

## 設問1

- [ ] (1)
8(Xt-(xt-1))/300
- [ ] (2)
通信していない時間を含んでいること
- [ ] (3)
a

## 設問2

- [ ] (1)
複数あるインターフェースそれぞれとピアリングせずに一つのインターフェースとピアリングすれば済むようにするため
- [ ] (2)
a.α.β.γ.0/30
000000/01
b.α.β.γ.4/30
000001/00
- [ ] (3)
最短経路ではなく不要な経路情報だから
- [ ] (4)
a.短い
i.大きい
u.α.β.γ.8
e.α.β.γ.9
o.α.β.γ.2
ka.α.β.γ.6
ki.BGPアドバタイズメント

a:13
000011/01
c:17
00010/001
f:2
000000/10
ループバック：8
00001000/

FW
e:19
00010/011

- [ ] (5)
同じ宛先ネットワークアドレスの経路情報の中から最適経路を一つだけ選択する仕様

## 設問3

- [ ] (1)
ku.e
ke.u
ko.i
sa.a
- [ ] (2)
si.ルータ11Z,ルータ11,ルータ10,L2SW10
- [ ] (3)
静的経路が設定されている間は静的経路による制御が優先されるから
- [ ] (4)

## 設問4

- [ ] (1)
- [ ] (2)
50
- [ ] (3)
FWとプロキシサーバの通信ログデータ
通常発生しえない不正と疑われる通信

# 問3
