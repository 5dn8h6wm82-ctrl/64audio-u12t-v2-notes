# 64 Audio U12t V2 検討ノート

2026-10-21 · 文：AI（Claude）／検討者：名無しの権兵衛

> **このノートは AI が書きました。** AI（Anthropic の Claude）が、検討者（名無しの権兵衛）との対話をもとに調べ、文章と表を作りました。測定データの計算、レビューや論文の要旨と翻訳も AI によるものです。仕上げの点検には、別の AI（OpenAI の Codex）も使いました。検討者の感想・採点・購入の判断は本人の発言にもとづきますが、文章にしたのは AI です。AI は誤ることがあるため、大事な判断の前には各出典を確かめてください。

## English summary

This note was written by an AI (Anthropic's Claude) from conversations with one listener (pseudonym: 名無しの権兵衛). It records why the listener decided to buy a used 64 Audio U12t V2 to replace a Thieaudio Monarch MKIV (STANDARD mode).

- In public squig.link measurements (Precogvision, Super\* Review, Jaytiss; the original U12t, not the V2), the U12t (m15) is about 2.5 dB lower than the Monarch MKIV at 2–4 kHz and about 4 dB lower at 8–12 kHz, with each measurement aligned at 300 Hz–1 kHz.
- In an at-home emulation (Spotify EQ applied to the Monarch, using an earlier version of the EQ values), no song scored lower than the unmodified Monarch. This was one listener, four songs, one day; it is not a test of the real U12t.
- Reviews broadly agree that the U12t has tight punch but less physical slam than strong dynamic drivers. How the real unit compares in attack and imaging could not be tested.

All summaries and translations are the AI's. Please check the original sources before relying on them.

## 結論

Thieaudio Monarch MKIV からの買い替え先として、**64 Audio U12t V2 を中古が出たら買う**と判断しました（2026-10-21 時点）。決め手は次の3つです。

- **音のバランスは合格。** Monarch に EQ をかけて U12t の音のバランスをまねた自宅試験で、検討者の感想は「なんら問題ない」（U12t の実機を聴いた結果ではありません）。刺さる成分がなく、音量を上げやすい。
- **弱点は補える範囲。** 声の明るさ（2〜4kHz）が Monarch より約 2.5dB、空気感（8〜12kHz）が約 4dB 控えめ。音量、apex の m20、Spotify の EQ で補える。
- **楽しさの種類が違う。** レビューでは、体に来る重さは DD 機よりやや控えめとされます。楽しさは重さより、強弱のメリハリ、楽器の分離、定位から来るタイプです（レビューからの推測）。

実機で最後に確かめたいのは、サビの入りの「重さ」と、ASMR のささやきの息遣いの2点です（EQ では再現できない部分）。

## 前提

このノートは1人の検討者の耳と機材を前提にしています。好みが違う人は、結論より「調べ方」を参考にしてください。

| 項目 | 内容 |
| --- | --- |
| 比較の基準 | Thieaudio Monarch MKIV（STANDARD モード、EQ なし） |
| 再生環境 | iPhone ＋ Questyle M15i（4.4mm、スタンダードゲイン）、Spotify（ロスレス）、イヤピース ELOIT VELVET WIDE BORE |
| 試聴した機種 | U4s m12（最も好評）、U4s m15、Nio m15（不評）・m12、IE 600、IE 900、64 Audio Solo |
| 普段の比較相手 | Sony WF-1000XM6（完全ワイヤレス） |
| よく聴く音楽 | 音ゲー系の電子音楽、ボカロ・アニメ（女性ボーカル）、ゲーム BGM・オーケストラ、ファンク、ジャズ、ASMR |

重視した点：ボーカルが埋もれないこと、高音が刺さらないこと、中低音が膨らまないこと、定位、楽しさ（機械的でない音）、寝ながら使える小さな筐体。解像度は「WF-1000XM6 の若干上で十分」。Monarch の不満は、筐体の上の縁が寝転んだときに当たることと、音が乾いて機械的に感じることでした。64 Audio の筐体（U4s・Nio）は耳に当たりませんでした。

## 測定データでの比較

測定データでは、U12t m15 の声の帯域（1〜6kHz）は、平均すると試聴済みの U4s m12 とほぼ同じです（細かい山や谷の位置は少し違います）。Monarch と比べると 2〜4kHz が約 2.5dB、8〜12kHz が約 4dB 低くなっています。低音は 60〜200Hz が Monarch とほぼ同じ、20〜60Hz が約 1.5dB 少なめです。Nio m12 と比べると 60〜200Hz が約 1.5dB 少なめです。

**U12t の声の帯域は U4s m12 とほぼ同じ、Monarch より 2〜4kHz の平均で約 2.5dB 低い**

（Monarch MKIV STANDARD を 0 とした差、単位 dB。各測定を 300Hz〜1kHz の平均でそろえ、帯域ごとの平均を 0.5dB 単位に丸めた値）

| 帯域 | U12t m15 | U4s m12（試聴済み） | Nio m12（試聴済み） |
| --- | --- | --- | --- |
| 20〜60Hz | −1.5 | −2 | −1 |
| 60〜200Hz | 0 | +1 | +2 |
| 200〜500Hz | −0.5 | 0 | +0.5 |
| 1〜2kHz | +0.5 | +0.5 | 0 |
| 2〜4kHz | −2.5 | −2.5 | −2 |
| 4〜8kHz | −1.5 | −0.5 | +0.5 |
| 8〜12kHz | −4 | −1.5 | −2.5 |

出典：Precog・Super\* Review・Jaytiss の squig.link 公開データから AI が計算（2026-10 取得）。全機種・全 apex の値（0.1dB 単位）は [data/band_diff_vs_monarch_mkiv_standard.csv](data/band_diff_vs_monarch_mkiv_standard.csv) にあります。

**計算の方法**：全機種がそろった測定サイトがないため、同じサイトの中で差を取り、両方に載っている U4s m12 を橋渡しにしてつなぎました。U12t と Nio は Precog と Super\* Review の平均、Monarch は Jaytiss の STANDARD モードの測定です。apex ごとの差は、同じサイト・同じ個体の中で m15 との差を取って足しています。各測定は 300Hz〜1kHz の平均が 0 になるようにそろえてから差を取っています（このため 300Hz〜1kHz の差は定義上ほぼ 0 です）。表の値は帯域ごとの平均を 0.5dB 単位に丸めたものです。

**apex の違い**：変わるのは主に 200Hz より下です。深い低音（20〜60Hz）は Monarch 比で m20 −0.5、m15 −1.5、m12 −4、mX −7.5。声の明るさ（2〜4kHz）はどの apex でも −2.5〜−3 で、ほとんど変わりません。

**読むときの注意**：サイトをまたぐと誤差が積み重なります。同じ Nio m15 でもサイトによって帯域の平均で最大約 2.4dB（8kHz 以下）違ったため、1dB 前後の差ははっきりした差とは言えません。8kHz より上は測定器の共鳴の影響が大きく、参考程度です。測定はすべて旧型の U12t で、V2 は測られていません。

## 自宅の EQ 試験（なんちゃって U12t）

U12t の試聴が現実的でなかったため、Monarch に Spotify の EQ をかけて U12t の音のバランスをまね、「続きを聴きたいか」を 0〜4 点で採点しました。**旧版の値で U12t のバランスに寄せた Monarch は、EQ なしの Monarch より点が低い曲が1曲もありませんでした（4 曲・1 日の結果）。**

**EQ の値**（Spotify の 6 バンド、単位 dB。修正版は Monarch STANDARD だけを基準に計算し直したもの）

| 条件 | 60Hz | 150Hz | 400Hz | 1kHz | 2.4kHz | 15kHz |
| --- | --- | --- | --- | --- | --- | --- |
| 素の U12t m15（修正版） | −1.5 | 0 | −0.5 | +0.5 | −2.5 | −4 |
| 素の U12t m15（旧版、1日目に使用） | −2.5 | −1 | −1 | +0.5 | −2.5 | −3.5 |
| P1 アタック（圧の試験用） | −1.5 | 0 | −1.5 | +0.5 | −0.5 | −2.5 |
| P2 アタック＋キック（同上） | 0 | 0 | −1.5 | +0.5 | −0.5 | −2.5 |

表の値は、測定の帯域平均を Spotify の 6 つの操作点に当てはめたものです（20〜60Hz→60Hz、60〜200Hz→150Hz、200〜500Hz→400Hz、1〜2kHz→1kHz、2〜4kHz→2.4kHz、8〜12kHz→15kHz）。15kHz の値は 8〜12kHz の平均の流用で、15kHz での実測の差ではありません。4〜8kHz の差（約 −1.5dB）は、どの操作点にも入れていません。実機をどこまで再現できているかは確かめていません。

**1日目の結果**（2026-10-20、曲全体を聴いて採点。B は旧版の値）

| 曲 | Monarch | 素の U12t（B） | メモ |
| --- | --- | --- | --- |
| Sense（Silentroom） | 2 | 4 | Monarch は「脳を軽く揺らすような低音で疲れる」。B は「低音が改善された」 |
| ray（超かぐや姫！） | 4・4 | 4 | Monarch は2回目に「刺さる・ほんのり疲れる」 |
| SPIN（Kroi） | 3 | 3 | B は「盛り上がりが足りない」 |
| Ex-Otogibanashi | 3 | 3 | ― |

分かったこと：

- 深い低音や高域を足した「改善版」（C1：60Hz を +1dB、C2：60Hz・2.4kHz・15kHz を足す）は点が上がらず、SPIN ではどちらでも「声が若干ぼやけている」と感じました。ボーカルブースターで声がぼやけた経験と合わせると、低音や声の胴を足すと**ぼやけを感じやすい可能性**があります（1 曲・1 回の結果で、原因は特定できていません）。
- 同じ Monarch でも、同じ日のうちに点が 1 点動きました（ray 4→3、Sense 2→3、SPIN 3→4）。1 点の差は、まだノイズの範囲です。
- 「盛り上がりが足りない」には、低音を足すのではなく、立ち上がり（2.4kHz）とキック（60Hz）を足して 400Hz を削る P1・P2 を用意しました（結果は未記録）。

この方法の限界：Monarch の低音は DD なので、分かるのは音のバランスまでです。BA 特有の立ち上がりや重さは再現できません（「圧」の章）。Spotify の EQ は帯域が固定で、各帯域の効く幅も分からないため、値はおおよその目安です。

## 女性ボーカルと Monarch との違い

レビューと測定から見ると、U12t の女性ボーカルは一歩引いて落ち着くものの、滑らかで余韻が自然で刺さらない傾向です。Monarch は近くてくっきりして息も生々しいものの、乾いていて刺さりや疲れが出やすい傾向です。**声が埋もれる心配は小さく**、控えめなのは声の「質感」の側です。

| 要素 | 帯域・性質 | U12t m15（Monarch を 0 とした差） | 聞こえ方 |
| --- | --- | --- | --- |
| 声の胴・厚み | 200〜500Hz | −0.5 | ほぼ同じ |
| 声の芯 | 1〜2kHz | +0.5 | ほぼ同じ |
| 明瞭さ・近さ | 2〜4kHz | −2.5 | U12t は一歩引く。自宅試験では音量で補えると感じた |
| 息の「シ」・さ行 | 4〜8kHz | −1.5 | U12t は刺さりにくい |
| 艶・空気感 | 8〜12kHz | −4 | U12t は地味め（測定の信頼度は低い帯域） |
| 余韻・消え際 | 時間の性質 | ― | レビューの要旨：Monarch は響きや余韻が置き去りになりがち、U12t は余韻と響きが音楽的 |
| 伴奏との重なり | 伴奏の 150〜500Hz | ― | U12t は 200〜500Hz がやや少なく、声がぼやけにくい（推測） |
| 定位 | 声が中央に締まるか | ― | Monarch と直接比べたレビューは見つからなかった（U4s より上とする所有者の投稿はある） |
| 質感 | 滑らか・硬い | ― | Monarch は乾いて無機質（FC Construct の評、訳）。U12t は滑らかだが、立ち上がりにわずかなプラスチックっぽさ（Precog の評、要旨） |
| 解像度 | 息継ぎや語尾の表情 | ― | ほぼ同格 |

この検討者が感じた「声のぼやけ」は、解像度よりも、**声の胴や低音の足しすぎ**（伴奏が声を覆うこと）から来ている可能性があります（推測）。Spotify の「ボーカルブースター」（400Hz・1kHz を約 +3dB）では、歌声が不自然に大きくなってぼやけたため、使うのをやめています。

## 圧（パンチ）

レビューの評価はおおむね、U12t の圧は締まってパンチがあるが、DD のような体に来る叩きつけ（slam）は一歩控えめ、という点で一致しています。一方で、EQ で特性をそろえても、立ち上がりと定位の評価には差が残るという研究があります。

### 圧とは何か

- [Fenton ら（AES 2015）](https://eprints.hud.ac.uk/id/eprint/26288/)：音量をそろえた短いピンクノイズ（専門の聴き手 11 人、64Hz〜1kHz で分析）では、中心周波数が低い帯域ほど、また立ち上がり（0〜60ms で比較）が速いほど「パンチ」を強く感じた。1kHz より上は評価が割れ、4kHz を中心に、音色の重みや存在感からパンチを高く付けた人もいた（要旨）。
- つまり圧は「低音の量」ではなく「低い帯域の、短く鋭い立ち上がり」。低音が鳴り続ける量感とは別物です（この研究からの解釈）。

### DD と BA の違い

[Hüsen ら（AES 2025）](https://www.researchgate.net/publication/395011860_Evaluating_the_Effectiveness_of_Virtual_Listening_Tests_for_Balanced_Armature_Headphone_Drivers)は、DD 1台と BA 2台を互いの特性に EQ で合わせて比べました（1〜5 の連続尺度）。

- ずれは最大で尺度の約 10%。著者らは、おおむね成功だが、ハイエンド機の評価に使うには精度が足りないとまとめている（要旨）。
- DD を BA に似せると、本物の BA より定位が −0.56、立ち上がりが −0.55 低く評価された。
- BA を DD に似せると、低音の衝撃の忠実さは元の DD より高く評価された（理由は推測で、BA の反応の速さや歪みの少なさが考えられる）。

この研究で使われたのは U12t や Monarch そのものではなく、「体に来る重さ」そのものも測っていません。

### U12t の圧についての評価（要旨・訳）

| 出典 | 内容 |
| --- | --- |
| [Resolve（headphones.com、2019）](https://www.headphones.com/blogs/news/64-audio-u12t-universal-iem-review) | とてもパンチがあり、締まっていて明瞭。振幅の大きい DD のサブベースほどの slam ではないが、かなり近い |
| [Precog（headphones.com、2020）](https://headphones.com/blogs/reviews/64-audio-u12t-review-the-consummate-all-rounder) | トップ級の DD ほど強く叩かず、音の密度も及ばない。強弱のメリハリは驚くほど。立ち上がりにわずかなプラスチックっぽさ |
| [FC Construct（headphones.com）](https://headphones.com/blogs/reviews/64-audio-u12t-review-old-faithful) | 低音の重みと衝撃に驚かされる。ただし立ち上がりはやや丸い。apex は m20 を推す |
| [Head-Fi の購入者レビュー](https://www.head-fi.org/showcase/64audio-u12t.23070/) | 意外なほどパンチと衝撃がある。3〜4kHz の凹みで打楽器の鋭さが削がれる |
| [Head-Fi（所有者の投稿）](https://www.head-fi.org/threads/the-official-64-audio-thread-apex-tia-technologies.826606/page-1503) | U4s と比べて、深い低音のパンチで U4s が勝つのは m15・m20 のときだけ |
| [e☆イヤホンの V2 購入者](https://www.e-earphone.jp/products/574169)（2 名） | 「低域はタイトながら深みがあり」（1 人目）、「モニターよりに聴こえました」（2 人目） |

### 圧を足す手段（効きそうな順）

1. apex を m20 にする（深い低音と密閉が増える。耳の中の圧力を逃がす効果は弱まる）
2. EQ で 60〜125Hz（キック）と 2〜4kHz（アタック）を足し、200〜500Hz は足さない（声がぼやける帯域）
3. 密閉と装着の深さ（低音の衝撃は密閉で大きく変わる。一般論）
4. 音量（大きいほど圧を感じやすい。耳の負担に注意）

変えられないのは、BA と DD の衝撃の質の差です。自宅試験（Monarch の DD）と比べると、**体に来る重さは本物のほうがやや控えめ、立ち上がりと定位は本物のほうが良く感じられる可能性**があります（レビューと研究からの推測）。差の大きさは分かりません。上の研究の数字は別の機器での結果で、U12t と Monarch の差にはそのまま当てはめられません。

## 楽しさ（多角的なレビュー照合）

レビューを総合すると、U12t は Monarch より音楽的で、U4s より落ち着いた位置です。楽しさは重さで押すより、音が増える瞬間に全部が見えるタイプです（推測）。

**調べ方**：「退屈」「楽しい」は人によって物差しが違うので、検討者が聴いた機種（U4s・Monarch・Nio・IE 600・IE 900）への評価が一致するレビュアーの意見を重く見ました。情報源は iemranking、headphones.com、Crinacle、Head-Fi、e☆イヤホン・価格.com の購入者の声です。表の点数は iemranking に掲載された値で、Super\* Review の点数はサイトが 10 点満点に換算したものです。表の言葉は要旨（訳）で、原文そのままではありません。

| レビュアー | 検討者との一致 | U12t の楽しさ |
| --- | --- | --- |
| FC Construct | ◎ 3つ一致（Nio「dirty bass」、U4s は Nio より締まる、Monarch を dry and sterile と評価） | 最も刺激的・個性的な機種ではないかもしれないが完成度が高く、「old faithful」（頼れる定番）。低音の重みと衝撃に驚かされる |
| Super\* Review | ◎ 3つ一致（Nio m15 は濁った低音、U4s は楽しさと性能の両立、Monarch は 6.0。いずれも iemranking の要約と換算値） | 10 点（換算値）。動画の AI 要約では、疲れずに楽しめる傾向 |
| Precogvision | ○ 順位が一致（Monarch＞U4s＞Nio） | 8.1（U4s より上）、強弱のメリハリが優秀 |
| Crinacle | ○ 2つ一致（IE 600＞IE 900、Nio は m15・m20 だとまずまず、mX で本領） | BA としては驚くべき低音、最上位級の解像度（要旨） |
| Jaytiss | ✕ U4s に 6.8（検討者は高評価） | 退屈とする評価（要旨）。この検討者とは好みの一致が少ないため、参考の度合いを下げた |
| Head-Fi：U12t・U4s の所有者 | ― | 温かみ・低音・ディテール・全体のバランスで、U12t より U4s のほうが好みとした |
| Head-Fi：U12t・Monarch Mk2 の所有者 | ― | U4s と比べて、分離・重なりの表現・中低音の正確さ・声の滑らかさと自然さ・定位で U12t が大きく上回るとの評価（Monarch との比較ではない） |
| e☆イヤホンの旧型購入者 | ― | 「ハイブリッドみたいな面白みは無くても」、DAP やケーブルで変化を楽しめるという趣旨 |

曲の種類でいうと（推測）：音が多く重なる編曲に声が乗る曲やオーケストラは有利。ベースのうねりと体に来るグルーヴが楽しさの中心のファンクは、やや不利。

## 価格・中古・買取と EQ の使い方

U12t V2 を中古で約 24.5 万円で買い、合わずに買取の上限 20.2 万円で売れた場合、差額は**約 4.3 万円**です。実際の査定は状態などで下がることがあり、その分だけ差額は増えます（額は未確認）。値段は 2026 年 10 月に調べたものです。

| 機種 | 新品 | 中古の販売価格 | 買取の上限（e☆イヤホン） |
| --- | --- | --- | --- |
| 64 Audio U12t V2 | 304,200 円（e☆イヤホン）、338,000 円（ジョーシン・ヨドバシ） | 約 24.5 万円（e☆イヤホンの掲載例） | 202,000 円 |
| 64 Audio U12t（旧型） | ― | ― | 115,000 円 |
| 64 Audio U4s | 218,400 円 | m12 付きで約 11〜11.7 万円（掲載例） | 84,000 円 |
| Thieaudio Monarch MKIV | ― | ― | 100,000〜102,000 円（フジヤエービックは買取 100,000 円、下取 110,000 円） |

買取の上限は新品同様の場合です。U12t V2 には 3.5mm と 4.4mm の両方のケーブルと、apex 4 種類（m20・m15・m12・mX）が付属します。

**EQ の使い方（iPhone）**

- **Spotify**：帯域を自分で調整できる 6 バンドの EQ。2025 年 9 月から日本でもロスレス（24bit／44.1kHz の FLAC）。曲ごとの自動切り替えはない。
- **Apple Music**：iPhone ではプリセット（2024 年の解説記事では 23 種類）から選ぶだけで、帯域を調整できない。EQ を細かく使うなら移る理由は薄い。
- **YouTube（ASMR など）**：iPhone には全アプリに効く EQ がないため、EQ では補えない。補うなら EQ を本体に保存できる DAC（Qudelix-5K など）。
- おすすめ：EQ のプリセットを「声・分離用」と「圧用」の 2 つに絞り、プレイリストを変えるときだけ手で切り替える。

## 分からないこと・注意点・これから調べる人へ

最大の未知数は、本物の U12t V2 でのサビの入りの重さと、ASMR の息遣いです。どちらも EQ では再現できないため、実機で確かめるしかありません。

**分からないこと**

- V2 そのものの測定。使った測定は 2020 年と 2023 年の旧型で、代理店（MIXWAVE）は「ご好評の音質特性はそのまま維持」と説明している。
- V2 の外形が旧型と同じか（寝転んだときに当たるか）。
- Questyle M15i に EQ 機能があるか。
- 中古を売るときの実際の査定額。

**この調査で実際に起きた間違いと教訓**

- Jaytiss が公開している Monarch MKIV の測定は2つあり、片方は低音を増やす RUMBLE モード相当とみられたのに、AI が両方を平均して基準にしたため、低音が約 1dB 多すぎた。→ 測定のモードや個体を確認し、自分が使うモードだけを基準にする。
- Spotify の EQ でマイナスの符号を見落とし、逆向きの設定で試してしまった。→ 設定後に曲線の形を見て確かめる。
- Head-Fi、Headfonics、研究論文のページは、自動取得ではボット確認や 403 で開けないことがある。→ 普段のブラウザで開き直す。

**数字の読み方の注意**

- 複数の測定サイトをつなぐと誤差が積み重なる。同じ Nio m15 でも、サイトによって帯域の平均で最大約 2.4dB（8kHz 以下）違った。1dB 前後の差は、はっきりした差とは言えない。
- 8kHz より上は、測定器の共鳴のため当てにならない。
- 自宅の採点は、同じ条件でも 1 日のうちに 1 点動いた。日を変え、順番を逆にして繰り返す。

**これから調べる人へのヒント**

1. 自分が試聴した機種を物差しにする。測定サイトに載っている試聴済みの機種（ここでは U4s m12）を橋渡しにすると、聴いていない機種も位置づけられる。
2. 測定の差を Spotify の EQ に置き換え、手持ちのイヤホンで「なんちゃって」を作る。音のバランスの相性は、試聴前にかなり分かる。
3. 「退屈」などのレビューは、その人が自分と同じ機種をどう評価したかを先に確かめてから読む。
4. 「圧」は低音の「量」と分けて考える。量を足しすぎると、声がぼやけて感じられることがある（この検討者の場合）。

## 出典とデータ

このノートの文章・要旨・翻訳は AI（Claude）によるものです。他の人の発言は、原文どおりの短い一節に限って「」で示し、それ以外は要旨として書いています。英語の資料の要旨は AI の訳で、原文そのままではありません。正確な内容は各出典を確かめてください。

**このリポジトリのデータ**

- [data/band_diff_vs_monarch_mkiv_standard.csv](data/band_diff_vs_monarch_mkiv_standard.csv)：機種・apex ごとの帯域別の差（Monarch MKIV STANDARD を 0 とした dB、各測定を 300Hz〜1kHz でそろえた値）。AI が計算した結果だけで、測定サイトの生データは含みません。

**測定データ**（2026 年 10 月に取得）

- [Precogvision のグラフ](https://precog.squig.link/)（U12t、U4s、Nio）
- [Super\* Review のグラフ](https://squig.link/)（U12t、U4s、Nio、apex 4 種類）
- [Jaytiss のグラフ](https://jaytiss.squig.link/)（Monarch MKIV、U4s m12）
- [hbb のグラフ](https://hbb.squig.link/)（Monarch MKIV STANDARD・RUMBLE、WF-1000XM6）
- [iemworld のグラフ](https://iemworld.squig.link/)（イヤピース 11 種類の違い、Hisenior Mega5EST）

**研究・メーカー**

- [Fenton、Lee、Wakefield「Towards a Perceptual Model of 'Punch' in Musical Signals」（AES 2015）](https://eprints.hud.ac.uk/id/eprint/26288/)
- [Hüsen、von Berg、Steffens「Evaluating the Effectiveness of Virtual Listening Tests for Balanced Armature Headphone Drivers」（AES 2025）](https://www.researchgate.net/publication/395011860_Evaluating_the_Effectiveness_of_Virtual_Listening_Tests_for_Balanced_Armature_Headphone_Drivers)
- [64 Audio：Apex Modules](https://blog.64audio.com/apex-modules-pressure-relief-noise-attenuation-more/)
- [MIXWAVE：U12t V2](https://www.mixwave.co.jp/c_audio/item/64-audio/u12t-v2.html)

**レビュー**

- [Resolve：64 Audio U12t（headphones.com、2019）](https://www.headphones.com/blogs/news/64-audio-u12t-universal-iem-review)
- [Precogvision：64 Audio U12T Review - The Consummate All-Rounder](https://headphones.com/blogs/reviews/64-audio-u12t-review-the-consummate-all-rounder)
- [FC Construct：64 Audio U12t Review: Old Faithful](https://headphones.com/blogs/reviews/64-audio-u12t-review-old-faithful)
- [FC Construct：Comparing the U4s vs Nio](https://headphones.com/blogs/reviews/64-audio-s-next-generation-comparing-the-u4s-vs-nio)
- [headphones.com：Thieaudio 比較（Monarch MKIV）](https://headphones.com/blogs/reviews/comparing-the-best-thieaudio-iems-monarch-mkiv-vs-v16-divinity-vs-valhalla)
- [Bloom Audio：64 Audio U12t Review](https://bloomaudio.com/blogs/articles/64-audio-u12t-review)
- [Audiosolace：64 Audio Nio Review](https://audiosolace.com/64-audio-nio-review/)
- [iemranking：U12t vs U4s](https://www.iemranking.com/compare/64-audio-u12t--vs--64-audio-u4s)、[U4s](https://www.iemranking.com/show/64-audio-u4s)、[Nio](https://www.iemranking.com/show/64-audio-nio)
- [Crinacle：IEM ランキング](https://crinacle.com/rankings/iems/)
- [Head-Fi：U12t ショーケース](https://www.head-fi.org/showcase/64audio-u12t.23070/)、[64 Audio 公式スレッド p.1503](https://www.head-fi.org/threads/the-official-64-audio-thread-apex-tia-technologies.826606/page-1503)、[p.1573](https://www.head-fi.org/threads/the-official-64-audio-thread-apex-tia-technologies.826606/page-1573)
- [e☆イヤホン：U12t V2](https://www.e-earphone.jp/products/574169)、[U12t（旧型）](https://www.e-earphone.jp/products/39)
- [価格.com：U12t（旧型）](https://kakaku.com/item/K0001055753/)

**価格・サービス**

- [e☆イヤホンの買取価格](https://kaitori.e-earphone.jp/)、[フジヤエービックの買取表](https://www.fujiya-avic.co.jp/shop/e/ea-kkep_s5/)
- [PHILE WEB：Spotify のロスレス開始](https://www.phileweb.com/sp/news/audio/202509/10/26848.html)
- [iPhone のイコライザ（プリセット 23 種類）](https://minnano-rakuraku.com/contents/equalizer-settings-11142/)

## ライセンス

このノートの文章と data/ の表は [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja) で公開します（出典としてこのページを示せば、自由に使えます）。ただし、引用した一節、レビューや論文の内容、測定データそのものの権利は、それぞれの著作者にあります。

最終更新：2026-10-21
