# 開放原始碼專案獲利指引
*「我參與了開放原始碼專案，該如何藉此營利？」*

我列出了從各種管道所知的開放原始碼專案帶來收益的案例，每種類型都有對應的真實案例，粗略的按照出資量從小到大排列。 (我已盡力將超連結指向具體故事而非主頁面)

本文中的營利類型彼此並不牴觸，例如一個專案既可由基金會獲得收益，也可通過群眾募資來籌集資金，而一個人既可靠咨詢獲利，當然也可額外得到捐贈。本文的主要目的是提供一個詳盡的獲利方式列表，而你只需要從中選出適合你的選項。

譯注：本中為[Lemonade Stand](https://github.com/nayafia/lemonade-stand)的繁體中文翻譯版本。Lemonade Stand指銷售檸檬汁的小攤，在美國往往是由小孩經營。原文作者 Nadia Eghbal 想藉由「為了賺點零用錢，努力擺攤賣起檸檬水」衍生解釋各式透過開放原始碼專案獲利的方式，以及後續的效益。

---

# 目錄

1. [捐贈按鈕](#捐贈按鈕)
2. [懸賞](#懸賞)
3. [群眾募資 (一次性) ](#群眾募資 (一次性) )
4. [群眾募資 (持續性) ](#群眾募資 (持續性) )
5. [賣書及周邊](#賣書及周邊)
6. [廣告](#廣告)
7. [受雇於公司並持續開發專案](#受雇於公司並持續開發專案)
8. [在職時啓動專案](#在職時啓動專案)
9. [補貼](#補貼)
10. [咨詢服務](#咨詢服務)
11. [SaaS](#saas)
12. [免費增值授權](#免費增值授權)
13. [雙重授權條款](#雙重授權條款)
14. [開放核心](#開放核心)
15. [基金會](#基金會)
16. [風險投資](#風險投資)

附錄: [貢獻](#貢獻) // [授權條款](#授權條款)

**「個人成果」用來標記資金是由個人，而非來自專案主導籌集所得**


## 捐贈按鈕

在你的網站頁面里放上捐贈按鈕。Stripe和PayPal都可以很方便的提供這項服務。

#### 優點

* 限制條件少
* 工作量小：放好後就可以不管了

#### 缺點

* 除非你努力募款，通常都不會有太多錢
* 需要一個法人實體來接受捐贈 ([SFC](http://sfconservancy.org), [OpenCollective](http://opencollective.com)可在這方面提供幫助) ，因此較難管理個人的國際性捐贈
* 在多人專案中很難明確如何分配這筆捐贈

#### 案例探討

* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)

## 懸賞

專案主持人或公司可能時不時張貼開放原始碼專案的懸賞工作 (例如「懸賞100美元來修補軟體瑕疵」) ，下面列出了一些網站，他們收集和發佈了這類懸賞工作。


#### 優點

* 參與到開源技術社群
* 確定的工作有確定的回報
* 在修復安全漏洞方面特別流行

#### 缺點

* 會在專案中產生不合理的激勵機制 (低質量的pull request可能會降低專案的專注程度)
* 通常沒多少錢 (小於 500 美元)
* 無法提供持久的收入

#### 案例探討

* [Bountysource](http://bountysource.com)
* [GitHub Bug Bounty Program](https://bounty.github.com/)

## 群眾募資 (一次性)

如果你想實現一個特別的想法 (區別於長期專案) ，一次性的群眾募資活動可以幫助你籌集到你需要的資金，許多個人和公司都可能會為你的想法捐款。

#### 優點

* 限制條件少
* 對個人來說也可以很容易合法的進行，例如通過[Kickstarter](https://kickstarter.com/)

#### 缺點

* 需要投入大量市場行銷、推廣，和競爭工作
* 通常都需要為捐贈者提供回報和額外福利
* 實際獲利不會太高 (單次約 5 萬美元)
* 公司並不常願意向群眾募資捐款

#### 案例探討

* [Dave Gandy + Font Awesome](https://www.kickstarter.com/projects/232193852/font-awesome-5)
* [Michal Papis + Rvm (個人成果)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Andrew Godwin + Django (個人成果)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [ribasushi + CPAN (個人成果)](https://www.tilt.com/tilts/year-of-ribasushi-help-him-focus-on-cpan-for-2016)
* [RESTful WP-CLI](https://www.kickstarter.com/projects/danielbachhuber/a-more-restful-wp-cli)

## 群眾募資 (持續性)

如果你想要為持續性的專案籌集資金，可以設立一個持續性的群眾募資，捐贈者承諾按月或按年提供資金直到捐贈者退出。對於那些經常使用你的專案的個人或公司可能會願意為你的專案提供資金。

#### 優點

* 限制條件少
* 對個人來說也可以很容易合法的進行，例如通過[Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Gratipay](https://gratipay.com/), [OpenCollective](https://opencollective.com)

#### 缺點

* 很難獲得承諾的持續性捐贈 (這通常需要你或專案已經有一定的名聲)
* 很難解釋持續性的捐贈能獲得什麼樣明確的回報或特權
* 通常錢也不多 (一個月約 1 到 4 千美元)

#### 案例探討

* [MochaJS](https://opencollective.com/mochajs)
* [React-boilerplate](https://opencollective.com/react-boilerplate)
* [jsbin](https://gratipay.com/jsbin/)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [Ruby Together](https://rubytogether.org)


## 賣書及周邊

如果你是某個領域的專家，你可以寫書賣書，可以找個出版社 (像O'Reilly) 或自行出版。除了賣書之外，有些專案也賣短袖外套等。

#### 優點

* 籌集到的資金並不和專案本身管理關聯，所以專案本身可以保持創作的自由
* 銷售的商品本身也可以當做為專案做的宣傳
* 在初次銷售後可以成為持續性的資金來源

#### 缺點

* 通常獲利有限
* 會影響用在專案上的精力
* 賣周邊需要準備預付資金

#### 案例探討

* [Lua](https://www.lua.org/pil/)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (個人成果)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (個人成果)](http://www.poodr.com/)
* [Kyle Simpson + You Don't Know JS (個人成果)](https://github.com/getify/You-Dont-Know-JS)
* [CocoaPods (為慈善目的募款)](https://cocoapods.org/socks)

## 廣告

如果你的專案已經有了一定的死忠支持者，你可協助廣告商向你的支持者進行推銷。通常你的專案都會有明確的死忠支持者，這是你的優勢也是廣告商所喜歡的。 (比如你有一個Python專案，那麼基本上可以假定你的死忠支持者必定在技術上熟悉Python)

#### 優勢

* 這是成熟明確而且大眾也能接受的商業模式

#### 缺點

* 需要足夠多的死忠支持者才可得到廣告商的青睞
* 需要通過透明化來讓死忠支持者相信你 (比如讓其信任你不會追蹤他們)
* 需要許多精力來尋找和管理廣告商

#### 案例探討

* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Hoodie](http://hood.ie/sponsoring/)


## 受雇於公司並持續開發專案

公司有時候會雇傭一些人來做開放原始碼專案，你可尋找一個正在使用你的開放原始碼專案的公司。當然具體在公司里可能公司工作和開放原始碼專案工作時間會是五五分。除此之外，也可以找一個願意嘗試使用你的新專案的公司。如果你有展示專案經驗，這將會非常有用。

#### 優點

* 可以利用公司的資源
* 可以很好的和公司的需求保持一致
* 穩定的收入

#### 缺點

* 獲得這樣的機會需要極好的運氣，現目前沒有明確可重復的方式獲得這樣的機會
* 專案通常需要非常出名並被廣泛使用
* 對於沒有為公司的利潤工作，這使得個人很容易被公司優先捨棄
* 公司可能會過分影響專案的發展
* 可能會因平衡不好兩邊而影響專案

#### 案例探討

* [Donald Stufft + Hewlett-Packard and Python packaging (個人成果)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Aaron Patterson + ManageIQ and Ruby, Rails (個人成果)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (個人成果)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)


## 在職時啓動專案

許多開放原始碼專案最初都是員工的業外專案(Side Project)，即便其最終可能會成長為一家公司，但以業外專案的形式在公司里進行孵化應該是不錯的選擇。

如果你想走這條路，請確定你理解了公司在開放原始碼專案上的政策。有些公司鼓勵員工在工作時間從事開放原始碼專案開發，而有些則將你的任何工作視作公司專案。不要假定任何前提，最好在開始前問問你公司裡的相關人員。

#### 優點

* 可在不用擔心收入的情況下嘗試新想法
* 可和公司的需求很好的保持一致
* 適合嘗試新想法

#### 缺點

* 需要用業餘時間開發，或者獲准在工作時間開發
* 有被公司過分影響的風險
* 持續下去可能會出現極度複雜的管理情況

#### 案例探討

* [Rust 之於 Mozilla](https://www.rust-lang.org/faq.html#is-this-project-controlled-by-mozilla)
* [Go 之於 Google](https://golang.org/doc/faq#history)
* [React 之於 Facebook](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)


## 補貼

補貼是不需要償還的極其有效的大筆捐贈，提供補貼的組織通常能夠通過給予補貼而從其他方面獲得利益，例如接近你，展示其影響力，獲得你的工作彙報或稅率優惠。

補貼可能來自很多地方，包括公司、軟體基金會、慈善基金會以及政府，其技術及法律方面會因其來源的不同有很大的差異。比如一家公司可以通過開咨詢費發票給你補貼，而慈善基金會則只能給非盈利組織或個人，通常你得找到一個非盈利組織來幫助你。如果你對補貼不熟悉，瞭解它的最好方式就是和曾經獲得過的人去瞭解。下面列出了一些成功的案例

#### 優點

* 限制條件少
* 有保證的資金可以確保你能在一段時間里專注在你的專案上
* 讓你的專案有時間喘口氣和做些試驗

#### 缺點

* 軟體方面沒太多提供補貼的組織
* 補貼是有限的，始終需要在用完補貼前找到一個持續方法

#### 案例探討
* [Dat](https://usopendata.org/)
* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)


## 咨詢服務

咨詢是一種為開放原始碼專案提供資金的靈活方式。你可以更加自由的規劃你的時間，比如一周30小時做咨詢業務，10小時做開放原始碼專案。咨詢師通常收費相對較貴，因為工作不穩定且沒有公司福利。如果你打算做這類公司，你應該想要創建一家有限責任公司。

#### 優點

* 這是成熟明確而且大眾也能接受的商業模式

#### 缺點

* 咨詢工作需要人力，而且不宜規模化 (除了極少數例外)
* 商業本身的需求會分散開放原始碼專案上的注意力
* 可能會和軟體的簡易要求有差異
* 專案需要足夠流行，才會讓人願意為相關服務付錢

#### 案例探討

* [Neighbourhoodie](https://neighbourhood.ie/)
* [Baroque Software](http://baroquesoftware.com/)
* [OpenSSL](http://openssl.com/what.html)

## SaaS

SaaS 即 [軟體即服務(Software as a Service)](https://en.wikipedia.org/wiki/Software_as_a_service)。在這個模型下，代碼本身是開源的，但是你可以提供增值服務使得使用者更容易使用。一個典型的增值服務就是服務代管付費。

#### 優點

* 可以圍繞這個開放原始碼專案建立一個技術社群，然後通過服務代管服務賺錢
* 讓開放原始碼專案可以專注在使用者層面，當需求增加後再幫助企業採用這個專案
* 可以根據使用者數量進行規模化改造

#### 缺點

* 對增值服務使用者來說，通常意味著服務代管服務必須比招聘一個人來維護專案更便宜
* 增值服務有可能會使得免費使用者不太高興

#### 案例探討

* [WordPress.com](http://wordpress.com/)
* [Moodle](https://moodle.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Gitlab](http://gitlab.com)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [Ghost](https://ghost.org/)


## 免費增值授權

「免費增值」(Freemium)授權就意義來說，並不是我們所謂的開放原始碼，因為這種授權不符合開放原始碼授權規範的條件(像是原始程式碼不能兼具公開存取且允許自由散佈和修改)。不過，「免費增值」仍可試作和開放原始碼相關。

這種方式限制了某些開放原始碼授權原本該給予的自由，以便達到特定商業目的，比方說，允許使用者閱讀原始程式碼，但需要特定的商業授權才能實際使用程式碼。

#### 優點

* 讓人們願意針對某些特性去付錢的獲利模式
* 如果操作得當，有機會延展生意的規模
* 適合終端使用者產品

#### 缺點

* 並非真正的開放原始碼
* 仍是新的待驗證的領域

#### 案例探討

* [Fair Source](https://fair.io/), 為 [Sourcegraph](https://sourcegraph.com/) 所用
* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), 為 [MariaDB](https://mariadb.com/) 所用


## 雙重授權條款

有時候專案可以在完全相同的代碼里提供兩種不同的授權授權條款：一個是商業友好的，而另外一個則不 (例如GPL) 。後者對於個人來說可以免費使用，而公司需要通過購買商業授權條款來獲得合法的商業授權。

#### 優點

* 這是成熟明確而且大眾也能接受的商業模式
* 如果成功的話，也可以做到規模化

#### 缺點

* 會和讓軟體自由獲得的理想有衝突
* 專案需要足夠大以滿足客戶的需求

#### 案例探討

* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [SQLite](https://www.sqlite.org/copyright.html)


## 開放核心

在[開放核心](https://en.wikipedia.org/wiki/Open_core)模型中，專案的一些方面是免費的，但一些功能則是私有的，且只對付費使用者開放，通常要求這個專案有企業的需求。

#### 優點

* 這是成熟明確而且大眾也能接受的商業模式
* 如果成功的話，也可以做到規模化

#### 缺點

* 需要設計付費專案，且該專案應該是獨有的
* 會和讓軟體自由獲得的理想有衝突
* 獨有功能有可能使得免費使用者不太高興

#### 案例探討

* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Sidekiq](http://sidekiq.org/)


## 基金會與協會

[基金會](https://en.wikipedia.org/wiki/Foundation_&#40;nonprofit&#41;)是可以接收和支出的合法法人實體。鑒於其目的並非獲得利潤，因此可以更好保持中立地管理專案。在美國，基金會可以是501(c)(3) (非盈利) 或501(c)(6) (貿易聯盟) ，許多軟體基金會都是貿易聯盟，因為非盈利基金會要求展示出慈善的目的，這在軟體開發中比較困難。

#### 優點

* 中立，基金會可以幫助保護代碼和管理技術社群
* 可以在許多捐贈者中散布影響力
* 使得專案合法，公司會更願意向基金會付款/捐贈而非個人

#### 缺點

* 只適合大專案
* 由於IRS的限制 (多為貿易聯盟，而不是非營利基金會)，專案能做什麼會有所限制
* 需要大量技術社群的努力和各種技能，而且之後仍舊需要努力獲得募款

#### 案例探討

* [Ruby Together](http://rubytogether.org/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)
* 譯者補充: [OpenResty](http://openresty.org/en/)是華人世界第一個由開放原始碼專案而驅使建立的基金會。最初OpenResty從Nginx訂製發佈版本開始的簡單開源項目，到2016年11月中旬通過審核，在香港成立OpenResty Software Foundation

## 風險投資

風險投資是高增長業務的一種籌資形式，不像銀行貸款或者任意一種債務財務形式，風險投資者通過提供資金來佔有你業務的一定股份。這種交易不像貸款，如果你的業務掛了你並不需要償還出資方。當然，如果你成功了，你也需要成倍的返還給你的投資者。

風險投資是高風險高回報的：風投者相比銀行對風險更加寬容，當然他們也期待你成功後的巨額回報。如果你打算獲得風險投資，你應該建立股份有限公司。如果你對風險投資過程不熟悉，開始的最好方式就是詢問成功獲得風險投資的人。

#### 優點

* 制度上的支持對成長中的業務有益
* 大量的風投資金蓄勢待發

#### 缺點

* 風險投資在投資之初便做好了獲得成倍回報後退出的打算，歷史證明，由於開放原始碼專案的結構特點，風險投資的成功很難。
* 風險投資者可能會因為優先級改變其動機

#### 案例探討

* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)


## 貢獻

我寫這個手冊主要是為了將我頭腦中的知識都整理出來，不過我並沒有打算做主要的貢獻或改變。優點和缺點大多是從我的觀點出發的主觀想法。

如果有什麼錯誤 (尤其是案例探討) ，非常歡迎大家的修改。同時，如果發現有什麼分類漏掉了，我也非常歡迎大家的修改。

## 授權條款

原文授權條款為Creative Commons CC0 1.0 License，即你可以自由的使用，商業或非商業，不過如果你用了，很開心能從你那裡聽到點什麼，在這裡找到我[@nayafia](http://twitter.com/nayafia)，當然這並不是要求必須做的。

中文版授權條款為Creative Commons Attribution 4.0 International License，和原文授權條款雷同，唯一不要修改原作者名字或以原作者名字聲明演繹作品即可。

簡體中文翻譯: Icer (liangshuangde@163.com)
繁體中文翻譯: Jim Huang (jserv.tw@gmail.com)

![](https://i.creativecommons.org/l/by/4.0/88x31.png)
