---
title: FCoinトリセツ。
description: FCoinへの出金申請手順について
---

<div style="text-align: right;">
    <small>*本トリセツはMITライセンスによるオープンソースソフトウェアです。</small>
</div> 


# FCoinが事実上の経営破綻に

最大130億円相当の支払いが困難な状況になっています。  

公式のアナウンスは[コチラ（中国語）](https://fcoin.zendesk.com/hc/zh-cn/articles/360043503273-FCoin%E7%9C%9F%E7%9B%B8)。  
英語の翻訳記事は[コチラ](https://www.reddit.com/r/FCoin_Official/comments/f579v4/fcoin_truth/)。  

結論だけ書くと以下のような内容です。
<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">📌FCoinの真実<br><br>CEOの　張健　名義で<br>お知らせが出ました。<br><br>結論だけ言うと、<br><br>「FCoinとしては終わった　でも　3年以内に賠償するために張健個人としては別プロジェクトでがんばる。詳細は別途。」<br><br>ということのようです。<a href="https://t.co/SdKsYlwnya">https://t.co/SdKsYlwnya</a><a href="https://twitter.com/hashtag/FCoin?src=hash&amp;ref_src=twsrc%5Etfw">#FCoin</a><a href="https://twitter.com/hashtag/FMex?src=hash&amp;ref_src=twsrc%5Etfw">#FMex</a></p>&mdash; おだっち@FCoin焼け野原 (@lucied2007) <a href="https://twitter.com/lucied2007/status/1229378360440045570?ref_src=twsrc%5Etfw">February 17, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

---

# 出金申請
公式ページは止まっていますが、資産を預けていた方は、出金申請が可能です。
以下の方法で出金申請を行って下さい。

理財口座へ預けていた方も、出金報告がありました。  
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">financing.</p>&mdash; Richard (@Richardbsver) <a href="https://twitter.com/Richardbsver/status/1228663344640356352?ref_src=twsrc%5Etfw">February 15, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

しかし、FTやFMEXなどのF銘柄のトークンで保有していたユーザーの場合は、出金できたところで事実上無価値であるため、
前述のアナウンスを信じて3年以内の賠償を待つ以外に方法はなさそうです。


## 出金申請の手順
1. 所定の形式で `withdrawal@fcoin.com` にメールを送信します。  
（すでにメールを送信済みのユーザーは繰り返し送信する必要はありません）

    形式は以下のとおりです。
    
    <table style="margin-bottom: 8px;">
        <tr><td>件名</td><td>"Apply for withdrawal + ユーザー名"</td></tr>
        <tr>
            <td>本文</td>
            <td>
                "通貨名1: 数量, 出金先アドレス,<br>
                 通貨名2: 数量, 出金先アドレス,<br>
                 ...(以下略)...”
            </td>
        </tr>
    </table>
    
    申請時の注意点です。メール送信前に十分注意してください。
    
    - ユーザー名はメールアドレスではなく、FCoinに登録しているユーザー名に置き換えてください。  
    - 通貨名1, 通貨名2の箇所は、具体的な通貨名（BTC, ETH, XRP, USDT等）を記入してください。  
    →USDTの場合は、OMNIやERC20など複数のバージョンがありますが、理屈ではアドレスから判断可能です。不安な方はUSDT(OMNI)などと書くと良いかもしれません。  
    - 数量は、通貨の枚数を（記憶の限りできるだけ正確に）入力してください。ある程度の誤差は許容されるようです。  
    - 出金先アドレスは実際の出金先アドレスを正確に入力してください。出金までの時間が予測できない以上、将来利用不可になりうるアドレスを指定するのはおすすめできません。  
    <div style="margin-bottom: 8px;"></div> 

2. FCoin側で基本的な情報を確認した後、送信元のメールアドレスに対し確認コードを送信します。

3. ユーザーは、正常に検証コードを受信したら、その検証コードを返信します。それによってメールアドレスの信頼性検証（本人確認）が完了します。
（確認コードを受け取ったからといって、引き出しが正常に実行できるということではなく、以降の資産確認に合格する必要があります）

4. FCoinが、ユーザーから出金の確認コードを受け取った後、メールアドレスと資産の検証を開始します。
確認に合格すると、実際の金額に応じて関連する出金リクエストが処理されます。

5. ユーザーは、引き出し要求が処理されたというメールを受け取ります。
（このステップが完了すると、ユーザーは関連する引き出し通貨を受け取ります）

---

# リンク
- FCoin公式
    - [FCoin公式サイト](https://www.fcoin.com)
    - [FCoin公式Twitter（英語）](https://twitter.com/FCoinOfficial)

- FCoin日本コミュニティ
    - Telegram
        - [FCoinお知らせ](https://t.me/fcoinfanjapanese)
        - [FCoin雑談](https://t.me/fcoinchatjapanese)
        - [FCoin質問](https://t.me/joinchat/H6Li9VMbf4A0XPt6DeJgVA)
