[トップページへ](./)

# マイニング詳解

マイニングについて詳細を知りたい人向けのページです。

## マイニングとは

FCoinプラットフォームを利用すると、１年ロックアップされた状態のFTが付与されます。  
これをマイニングと呼んでいます。  
通常の取引だけでもマイニングになりますが、他にも色々な方法でFTをマイニングすることができます。  

マイニングは四半期ごとに半減期が存在し、徐々にマイニングの総生産量が下がっていきます。  
下記の図は、マイニングの半減期と各期間ごとの一日あたりのマイニング総生産量です。

![半減期](./images/mining/mining-half-life.png "マイニングの半減期と一日あたりの生産量")


## マイニングの種類

現時点では以下のようなマイニングの種類があります。

- [取引マイニング (Trade mining, Trading as mining)](#取引マイニング-trade-mining-trading-as-mining)
- [未約定注文マイニング (Limit-order mining)](#未約定注文マイニング-limit-order-mining)
- [直近板並べマイニング (Sorting minig)](#直近板並べマイニング-sorting-minig)
- [レバレッジマイニング (Lending as mining, Leverage mining)](#レバレッジマイニング-lending-as-mining-leverage-mining)
- [理財マイニング (Financial mining)](#理財マイニング-financial-mining)
- [FTロックアップマイニング (Lockup mining)](#ftロックアップマイニング-lockup-mining)
- [投票マイニング (Mining currencies voting)](#投票マイニング-mining-currencies-voting)
- [PRマイニング (Promotion mining, PR mining)](#prマイニング-promotion-mining-pr-mining)

---

### 取引マイニング (Trade mining, Trading as mining)

<dl>
    <dt>
        参加方法
    </dt>
    <dd>
        特定の通貨ペアでの取引成立
    </dd>
    <dt>
        参加条件
    </dt>
    <dd>
        全員参加可能*1
    </dd>
    <dt>
        マイニングされたFTの付与タイミング
    </dt>
    <dd>
        取引発生の翌日中（日本時間の深夜1:00締め）
    </dd>
</dl>
    
特定の通貨ペアで取引が成立すると、出来高への貢献度に応じて、翌日マイニング報酬のFTが付与されます。  
一日あたりのマイニング総生産量が通貨ペアごとに決まっており、定期的に生産量の見直しがされます。  
基本的には各通貨ペアごとの出来高に対し、自身が当該通貨ペアで貢献した出来高の割合が、付与されるFTの量となります。  
マイニングできるFTの目安は下記の計算式によって見積もることが可能です*1。

```
翌日付与されるFT ≒ 当該通貨ペアの一日のFT総生産量 ✕ (当該通貨ペアで自身が貢献した出来高 / 当該通貨ペアの出来高)
```
*1 KYC済みで、かつ、50回以内の注文回数（注文キャンセル分も含む）の場合（後述）

取引マイニングには全員が参加可能ですが、KYCが済んでいて、かつ、一日の注文が50回以内の場合にマイニングの効率が最大となります。  
逆に、KYCしていない場合、もしくは、1日あたり50回の注文（キャンセル含む）を超えた場合、上記の式ほどの効率が出せません。  
この場合、短時間で多くの出来高をあげるよりも24時間バランスよく安定して出来高をあげた方が評価が高くなるため、
Botでマイニングに参加される方はできるだけ長時間安定して取引させるようにすると効率が良くなります。

![取引マイニングのフローチャート](./images/mining/trade-mining-flow-chart.jpg "取引マイニングのフローチャート")
*FCoin KOUさんより提供

- #### 取引マイニング対応通貨
    取引マイニングの対応通貨ペアは下記のアイコンが表示されています。  
    また、アイコンへカーソルを合わせると現在の一日あたりのマイニング生産量が表示されます。
    
    ![マイニング対応のアイコン](./images/mining/mining-tooltip-icon.png "マイニング対応ペアに表示されるアイコン")
    ![マイニング対応のアイコン（フォーカス時）](./images/mining/mining-tooltip-icon-onfocus.png "マイニングアイコンへのフォーカス時")


---

### 未約定注文マイニング (Limit-order mining)

---

### 直近板並べマイニング (Sorting minig)

---

### レバレッジマイニング (Lending as mining, Leverage mining)

---

### 理財マイニング (Financial mining)

---

### FTロックアップマイニング (Lockup mining)

---

### 投票マイニング (Mining currencies voting)

---

### PRマイニング (Promotion mining, PR mining)

---