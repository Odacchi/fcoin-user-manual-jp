---
title: 3分でFCoinのサービスを理解する
description: FCoinのサービス全体概要を把握したい人向けのページ
---

[トップページへ](./)


本ページは、FCoinのサービス全体概要を把握したい人向けのページです。
FCoinおよびFTについての概要は[トップページ](./)を参照してください。

---

# 目的別早見表

FCoinはサービスごとに口座がわかれています。  
口座間の資金移動（振替=Funds transfer）は無料で即時反映されます。  
ここでは目的別に各口座の概要を説明します。  

| 目的        | 利用口座          | 
|:-------------|:------------------|
| 入出金したい | [マイウォレット](#マイウォレットmy-wallet)（My Wallet） | 
| 現物取引したい | [取引口座](#取引口座trading-account)（Trading Account） | 
| 預金したい、利息ほしい | [理財口座](#理財口座financial-account)（Financial Account） | 
| レバレッジ取引したい | [マージン口座](#マージン口座margin-account) （Margin Account）|
| 配当ほしい | [ロック口座](#ロック口座lock-account)（Lock Account） |

  
## マイウォレット（My wallet）
各取引所やウォレットへの入出金のほか、FCoinの各口座への振替元となります。  
また、配当や理財利用による利息の受け取りもマイウォレットになります。
FCoinでなんらかのサービスを利用する場合、そのサービス用の口座に対しマイウォレットから振替移動させて利用することになるため、
マイウォレットは最も基本的な資金の管理元になります。  

<div style="text-align: right;">
    <a href="https://exchange.fcoin.com/finance/assets" target="_brank">FCoinのマイウォレットへ</a>  
</div>
      
    
## 取引口座（Trading account）
現物取引をすることができます。メジャー通貨のメインボードと、草取引用のFOneというブランドに分かれています。

<div style="text-align: right;">
    <a href="https://exchange.fcoin.com/finance/exchange" target="_brank">FCoinの取引口座へ</a>  
</div>  
    
## 理財口座（Financial account）
預金することで当該通貨を利息で増やすことができます（例：BTCを預けたらBTCが増える）。  
理財口座に預金された通貨はレバレッジ取引への貸し出しのために使われます。
    
- 対応通貨：  
    `BTC`, `ETH`, `XRP`, `LTC`, `BCH`, `EOS`, `ETC`, `ADA`, `ZEC`, `DASH`, `XLM`, `USDT`

通貨ごとに利率は異なり、毎日利率の見直しがある変動金利制です。  
最新の日利は<a href="https://www.fcoin.com/finance" target="_brank">コチラ</a>（FCoin公式）から確認できます。    
  
注意点として、各通貨ごとに1日一回までの入出金制限があります。
この制限は毎朝9時（日本時間）にリセットされます。

<div style="text-align: right;">
    <a href="https://exchange.fcoin.com/finance/financial" target="_brank">FCoinの理財口座へ</a>  
</div>  
    
## マージン口座（Margin account）
レバレッジをかけた取引ができます。レバレッジ分はローンとなるので利子が発生します。  
通貨ごとに利率は異なり、7日毎に利率の見直しがある変動金利制です。  

- 対応通貨（全てUSDTペア）：
    - 5倍まで  
        `BTC`, `ETH`, `XRP`, `LTC`, `BCH`, `EOS`, `ETC`
    - 3倍まで  
        `ADA`, `ZEC`, `DASH`, `XLM`  

リスクレートが115%以下になると強制決済されるため、マージン口座の資産は基本的には0にはなりませんが、    
短時間で急激な相場変動が発生し、資産がマイナスとなった場合は、強制決済の後マイナス分を補填するまでマージン口座は凍結され利用不可となります。  

```
リスクレート = (マージン口座の口座残高 / ローン金額) × 100%
```

例：  
1000ドル分の通貨をマージン口座に入金し、2000ドル分の通貨をローンしたとすると、
マージン口座残高評価額は3000ドルになるので、リスクレートは150%となります。  
ここから損失を出しマージン口座の残高評価額が2300ドル（リスクレートが115%）まで下がった場合、
2000ドル+ローン利息が強制決済されて300ドル弱が手元に残る計算になります。

<div style="text-align: right;">
    <a href="https://exchange.fcoin.com/finance/margin" target="_brank">FCoinのマージン口座へ</a>  
</div>  

## ロック口座（Lock account）
FTをロックアップすることで、毎日配当を受け取ることができます。毎日の配当総額はプラットフォーム収益の16%*です。  
また、マイニングによって取得するFTは、1年ロックされた状態でロック口座に付与されます。  

- 対応通貨：  
    FTのみ

<div style="text-align: right;">
    <a href="https://exchange.fcoin.com/finance/lock" target="_brank">FCoinのロック口座へ</a>  
</div>

*毎日の配当総額は合計で80%ですが、残りの64%分は通年でプールされ、ロックアップしていなくても毎年1/1にFTホルダーに一斉分配されます。
      

---

# 各種サービスの利用条件

FCoinにはFTロックアップによる毎日の配当以外にも多くのお得なサービスがあります。   
ここでは、それらへの参加条件とそのサービスを紹介します。  
（解説ページのあるものは解説ページへのリンク付きです。）

- ## KYCと1万FTロックアップが必要  

    <dl>
        <dt>
            各選挙への投票（
            <a href="./about-mining.html#投票マイニング-mining-currencies-voting" target="_brank">
                投票マイニング
            </a>）
        </dt>
        <dd>投票が採用されるとFTが配布される</dd>
        <dt>
            <a href="./about-mining.html#prマイニング-promotion-mining-pr-mining" target="_brank">
                PRマイニング
            </a>
        </dt>
        <dd>プロモーション成果をアピールし、投票で上位に入賞するとFTが配布される</dd>
    </dl>

- ## KYCが必要  

    <dl>
        <dt>高額出金</dt>
        <dd>1日あたり2BTC or 20ETH以上出金する場合はKYCが必要</dd>
    </dl>

- ## 1万FTロックアップが必要  

    <dl>
        <dt>
            <a href="./about-mining.html#理財マイニング-financial-mining" target="_brank">
                理財マイニング
            </a>
        </dt>
        <dd>
            理財に預金して得る利息に応じてFTが毎週火曜日に配布される
        </dd>
    </dl>

- ## 全員参加可能  

    <dl>
        <dt>
            <a href="./about-mining.html#取引マイニング-trade-mining-trading-as-mining" target="_brank">
                取引マイニング
            </a>
        </dt>
        <dd>
            取引による出来高への貢献に応じてFTを毎日配布
        </dd>
        <dd>
            KYC済みで、1日50回まで（キャンセルも含む、毎日深夜1時にリセット）の注文で抑えた方が最も効率が良い*1
        </dd>
        <dt>
            <a href="./about-mining.html#未約定注文マイニング-limit-order-mining" target="_brank">
                未約定注文マイニング
            </a>
        </dt>
        <dd>
            取引に注文を指値しておくことでFTを毎日配布
        </dd>
        <dd>
            現在価格との指値注文との価格差（%）によって評価が変わり、現在価格に近いほど効率が良い
        </dd>
        <dt>
            <a href="./about-mining.html#直近板並べマイニング-sorting-minig" target="_brank">
                直近板並べマイニング
            </a>
        </dt>
        <dd>
            現在価格付近に注文を指値しておくことでFTを毎日配布
        </dd>
        <dd>
            現在価格からみて上下に15番目までの範囲内の注文が評価対象
        </dd>
        <dt>
            レバレッジ利用
        </dt>
        <dd>
            最大５倍のレバレッジを効かせた取引が可能
        </dd>
        <dt>
            <a href="./about-mining.html#レバレッジマイニング-lending-as-mining-leverage-mining" target="_brank">
                レバレッジマイニング
            </a>
        </dt>
        <dd>
            レバレッジ取引利用時のローンの利息に応じてFTが配布される
        </dd>
        <dt>
            理財利用
        </dt>
        <dd>
            理財口座に預金すると毎週月曜日に利息がもらえる。他のユーザーのレバレッジ取引へのローンに使われる
        </dd>
        <dt>
            FTロックアップによる配当
        </dt>
        <dd>
            FCoinプラットフォーム収益の16%*2がロックアップされているFTに対し毎日均等に配分される
        </dd>
        <dt>
            <a href="./about-mining.html#ftロックアップマイニング-lockup-mining" target="_brank">
                FTロックアップマイニング
            </a>
        </dt>
        <dd>
            FTをロックアップしておくと毎日の配当とは別にFTが配布される
        </dd>
    </dl>

*1  
KYCしていない場合、もしくは、1日あたり50回の注文を超えた場合、  
短時間で多くの出来高をあげるよりも24時間バランスよく安定して出来高をあげた方が評価が高くなる。  

*2  
プラットフォーム収益の80%はFTホルダーに配当される。  
このうちの20%(=収益全体の16%)がロックアップされているFTに応じて毎日配布され、  
80%(=収益全体の64%)が毎年1月1日にまとめて配布される。1月1日の一括配当はロックアップしておく必要はない。


