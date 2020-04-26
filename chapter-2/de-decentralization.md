# 區塊鏈的去去中心化



* 密碼法
* CBDC、提醒區塊鏈的各種曲解
* [https://ckxpress.com/de-decentralization-of-blockchain/](https://ckxpress.com/de-decentralization-of-blockchain/)
* [https://ckxpress.com/wallstreetchain/](https://ckxpress.com/wallstreetchain/)
* [https://ckxpress.com/the-chinese-way/](https://ckxpress.com/the-chinese-way/)

[上回](https://ckxpress.com/the-chinese-way/)提到，區塊鏈 blockchain 的鼻祖 Bitcoin，白皮書裡面其實只提及過 block、chain 和 chain of blocks 概念，中本聰從沒有在抽離 Bitcoin 的語境下定義區塊鏈，那都是後人的演繹。

#### 不可竄改和去中心化屬兩個維度

比特幣區塊鏈的兩大特點在於「不可竄改」和「去中心化」，不過，這也只不過是我，和我認為是正宗區塊鏈倡議者的理念而已，正正因為沒有中心，參與者也都在各自表述，爭奪話語權。上期談到重新演繹區塊鏈的是威權政府，不過公道點說，那之外還有很多其他組織、公司以致個人，基於各種原因，用自己的方式演繹區塊鏈。這些實踐幾乎都有一個共通點，保留和強調 「不可竄改」的特性，弱化甚至除掉「去中心化」的部分。

從字面看，區塊鏈確實可以單單理解為計算機工程學的數據結構（data structure），像其他結構如連結串列（linked list）、二元樹（binary tree）等。事實上，我接觸過最認真最全面的 Bitcoin 介紹材料，普林斯頓大學在 [Coursera](https://www.coursera.org/) 的線上課程 [Bitcoin and Cryptocurrency Technologies](https://www.coursera.org/learn/cryptocurrency)，也是先把 blockchain 解釋為數據結構，後來再解釋 Bitcoin 如何達致分布式共識（distributed consensus），讓任何人均可在沒有中央授權的前提下成為節點，依然能夠對結果取得共識。「不可竄改」和「去中心化」本身是兩個不同的維度，各自可獨立存在，只是因為「chain of blocks」的概念源於 Bitcoin 白皮書，而論文同時提出牽一髮動全身的數據結構和分布式共識的解決方案，所以 Bitcoin 以及如以太坊這些元祖區塊鏈，都會同時強調這兩項特性。

#### 不可竄改和去中心化分道揚鑣

但隨著 Bitcoin 十週年，新一代的區塊鏈不再一樣。不可竄改的特性還是有 — 否則跟傳統數據庫沒有區別，除了比較慢 — 但中央集權的程度就不一而足，部分即使有很多節點認證交易，但指定節點的權力來源集中，很難不讓港人想起特首的 1200人選舉委員會。當下各國政府推出的基於區塊鏈的服務，比較精準的理解是，數據結構從技術層面背書數據沒被竄改，提供了一層可信度；而原始數據的真確性，則是由技術以外的因素來背書，比如說，數據來源是某地政府，所以數據（不）可信。

如果以上說得太抽象，可以考慮以下虛構但典型的例子。某國政府搭建了「食安鏈」，同時立法規定超市出售食品附帶二維碼，市民只要一掃，就能快速查到食物來源甚至種植、飼養方法，保障食品安全。這是非常適合區塊鏈發揮長處的使用場景，[Walmart 和 IBM 也確實在進行相關計畫，初步證明非常有效，讓查詢食物來源的過程從 6天多變成 2.2秒](https://techcrunch.com/2018/09/24/walmart-is-betting-on-the-blockchain-to-improve-food-safety/)。但千萬別忘了，提供、錄入原始數據的流程還涉及人為因素，數據是否如實錄入，視乎流程管理和廉潔程度，「食安鏈」記錄說蒙牛的奶不含三聚氰胺，信不信由你。總之，一個區塊鏈數據庫的可信度，無論如何不會超越這個庫的經營方本身的可信度。

#### 去中心化的程度是個光譜

值得留意的是，一條區塊鏈去中心化與否並非二元對立，而是像個光譜，從最極端實踐去中心的 Bitcoin，到即將出現的另一個極端，由一國政府完全操控的區塊鏈。如果我們把 Bitcoin 的設計類比為直接民主，則也有區塊鏈採取類似代議政制決策，降低個人參與成本，提升效率。這些往後有機會再談。

-----------------

過去兩周區塊鏈業界的大事之一，是[紐約時報報導](https://www.nytimes.com/2019/02/28/technology/cryptocurrency-facebook-telegram.html) Facebook 打算推出自家通證（token），讓 WhatsApp 用戶可以互相轉賬。消息來自紐時，只是加強了可信度和公眾認知，鏈圈早有相關傳言，更指服務會先瞄準印度，因大量印度人經常匯款回國，而現有機制既貴且慢；而 Facebook 在區塊鏈磨刀霍霍亦早已有跡可尋，包括招聘相關人才，和收購新創 [Chainspace](https://chainspace.io/) 等。

#### FB 磨刀霍霍 JPM 正式宣布

如果說「WhatsCoin」只聞樓梯響，推出進程還不確定，那麼小摩 J.P. Morgan 上月推出的 JPM Coin，無論如何是大企業對區塊鏈發展野心勃勃的明證。2月 14日，小摩官方網站以「[J.P. Morgan Creates Digital Coin for Payments](https://www.jpmorgan.com/global/news/digital-coin-payments)」為題宣布 JPM Coin，清楚介紹計劃。

小摩對區塊鏈的心情十分複雜，其 CEO Jamie Dimon 前年才高調指責 Bitcoin 是騙局（「fraud」），不到兩年光景，自己發行了加密貨幣。有網民嘲笑 Dimon 不是轉肽就是精神分裂，但我認為這種人非但不笨，還非常聰明，十分自利，在區塊鏈的大潮流下，最在意的是自己會否失勢，又能否反過來利用區塊鏈推動業務。事實上，小摩早在 2016年已在計畫 JPM Coin 的載體 [Quorum 區塊鏈](https://www.jpmorgan.com/global/Quorum)，前年指責 Bitcoin，倒不如說是對 JPM Coin 的鋪墊。

#### 取長補短還是輸打贏要

Quorum 是以太坊（Ethereum）的修改版本，而以太坊跟 Bitcoin 一脈相承，在去中心化方面同等堅持，而希望更進一步，除了處理交易更提供運算，又致力改善共識機制，目標解決 Bitcoin 耗電過多等問題。小摩[官方網站](https://www.jpmorgan.com/global/Quorum)介紹，「… it only minimally modifies Ethereum’s core, Quorum is able to incorporate the majority of Ethereum updates quickly and seamlessly.」 更進一步，小摩還說「Quorum is a great step forward, since it makes Ethereum a lot more suitable to build enterprise grade solutions.」以取長補短為論述，投資銀行果然最擅長包裝。從另一個角度看，一邊 CEO 批評 Bitcoin 是騙局，一邊取用以太坊代碼做點小修改包裝成自家產品，再來就發行自家通證，這又不是輸打贏要又是甚麼？

本欄於上月[《區塊鏈的去去中心化》](https://ckxpress.com/de-decentralization-of-blockchain/)提到一個重要趨勢，新推出的區塊鏈一般只保留不可竄改（immutability）的特性而放棄甚至貶低去中心化，JPM Coin 正是最佳例子。Quorum 既強調是以太坊加上小量改動，又強調性能和可用性大幅改善，不是有什麼神奇代碼帶來小改變大改善，而是把以太坊任何人都能成為節點這個關鍵，改為只有極少數信任單位經營的節點。由幾萬個來自世界各地的節點確認交易，變成數個節點，當然可以讓同一套軟件的性能大幅提升。![](https://ckxpress.com/wp-content/uploads/sites/8/2019/04/photo6285107171209357456-241x300.jpg)網上惡搞圖

#### “I don’t really give it a shit”

十年多前雷曼爆破，一個多月後出現 [Bitcoin 白皮書](https://bitcoin.org/bitcoin.pdf)，在一片反省政府濫發貨幣，鞭撻銀行業失去穩健、無比貪婪的風氣下，去中心化的 Bitcoin 花了多年逐漸得到認同。去年 10月 31日 Bitcoin 十週年，指其是騙局後又說後悔失言的 Jamie Dimon 再被問及對 Bitcoin 的看法，這次乾脆說「[I don’t really give it a shit](https://www.marketwatch.com/story/jamie-dimon-i-dont-really-give-a-shit-about-bitcoin-2018-10-31)」。

區塊鏈因為反華爾街文化、保障私隱而生，十年過去，反過來被 J.P. Morgan 和 Facebook 用來強化業務，可謂無比諷刺。

-----------------------

中國大陸《[區塊鏈信息服務管理規定](http://www.cac.gov.cn/2019-01/10/c_1123971164.htm)》出台，規定經營方認證用戶真實身分。我從不自誇也不相信有人可以預測未來，但實名制的出台，實屬意料之內，毫不意外，唯一沒法估計的是何時出台。有朋友真心迷惘，問我實名制的區塊鏈，還算不算區塊鏈。

#### 帶中國特色的互聯網

我覺得，無論回答算或不算都不是很達意，反問朋友，也問自己，一個不能去 Google、不能去面書、不能去世界上很多出色的媒體還有很多很多網站，七成時間泡在微信，很多人連 URL 是甚麼都不知道的連網，還算不算互聯網。

互聯網 Internet 畢竟還是有相對明確的定義，比如底層用 TCP/IP，上層用 http、SMTP 等網絡協議，顯示用 html 等標準等等，雖然國內互聯網已經發展到一個普通人不用電郵（SMTP），砍掉 http 自立新標準都有條件的程度，但暫時還算符合以上條件，只不過那都是必要而不充分的條件，內聯網Intranet 一樣是使用以上各種協議。那到底是不是互聯網呢？有個「萬能 key」 很方便，可以讓我們不用回答 — 那是「帶中國特色的」互聯網。

#### 帶中國特色的社會主義 <a id="mce_10"></a>

再推演下去，較勁的人還可能會問，國內的社會主義算不算社會主義？這個大家心照不宣，繼續用萬能 key 就好，那是帶中國特色的社會主義。反正，這正是此萬能 key 的緣起。

所以如果我想敷衍朋友，回他那是帶中國特色的區塊鏈好了。不過我倒是想認真補充一點：社會主義在學術界有頗為清晰的定義，至少不同學者的理解不會差太遠；互聯網也有各個組織如 W3C 去制定相關標準，但區塊鏈就不一樣，稍微看過區塊鏈為何物的當知道，它最大的特性是「去中心化」 decentralization（我不喜歡這個翻譯，但已經約定俗成唯有用了），既然是這樣，很弔詭地，也就不應該也沒有一個組織有足夠的公信力去定義何謂區塊鏈。單是香港，就能數出一打區塊鏈協會，都自稱很有經驗很有資格，放到全球的範圍更不用說。

#### 帶中國特色的區塊鏈 <a id="mce_10"></a>

如果說 Bitcoin 是世界上第一條區塊鏈，大概沒有誰會提出異議。不過細看[Bitcoin 白皮書](https://bitcoin.org/bitcoin.pdf)的話，會發現「block\(s\)」字出現 67次、「chain」字 27次，「chain of blocks」1次，卻從沒有出現過「blockchain」。從語境看，[Bitcoin 白皮書](https://bitcoin.org/bitcoin.pdf)講解了如何巧妙地利用密碼學建立一套分散式帳本，讓人可以在沒有中央、沒有互信的前提下轉帳，但並沒有把 blockchain 的概念獨立演繹。把中本聰在 [Bitcoin 白皮書](https://bitcoin.org/bitcoin.pdf)提出的技術稱為 blockchain（區塊鏈），應用在 Bitcoin 以外的場景，是來自四方八面的後來者。

在這個前提下，莫說是我們，就算是中本聰終於現身，恐怕都沒絕對資格說實名制的就不是區塊鏈。Bitcoin 以後的區塊鏈，既有些共通點，如都是分散式帳本；又在一些設計上莫衷一是，比如成為節點的條件，一區塊鏈，各自表述。連社會主義和互聯網都能重新演繹的政府，要在牆內重新定義區塊鏈，輕而易舉。

我挺期待香港某區塊鏈協會走出來說要實名制的不是真正意義的區塊鏈，不過我知道，這件事不會發生。在我看來，管它叫甚麼呢，嘴巴長在別人臉上，話語權在別人手中，公民理解到那個詞的含義，背後的運作機制，對社會的影響，才真正重要。

