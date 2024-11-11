# Reminist（レミニスト）

## サービス概要
<!-- どんなサービスなのかを３行で説明してください。 -->
知り合った人の情報を記録できるアプリです。誕生日や出会った経緯、関係性、出来事などを記録できます。クライアントや新しく出会った人と話した内容を記録することで、次に会う際に相手の好みや過去の会話内容を思い出しやすくなり、より親密なコミュニケーションが取れるようになります。


## このサービスへの思い・作りたい理由
<!-- このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。 -->
人と話をする際には、さまざまな情報を会話の中で交わしますが、時間が経つと「誰から聞いた話だったか」を忘れてしまうことがよくあります。特に新しい出会いやクライアントなどの場合は、忘れずに次に生かしたい内容も多いですが、なかなか以前の会話を思い出すことができなかったりします。

このような経験から、手軽に、そして一元化して情報を管理できるサービスがあれば、より効率的に人間関係の管理やコミュニケーションに役立てられるのではと考えるようになりました。

このサービスは、日々のコミュニケーションを整理し、記憶の負担を軽減するためのサポートツールとして、多くの方に役立ててもらえるようなものにしたいと思っています。

アプリ名は、「reminiscence」という回顧録や思い出という意味を持つ単語と、接尾辞「-ist」を組み合わせ、「記憶の専門家」となる「reminist」と名付けました。


## ユーザー層について
<!-- 決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。 -->
このサービスのターゲットは特に20代の社会人を想定しています。

20代はキャリアの初期段階にあることが多く、社内外を問わず多くの人と積極的に関わりながら、ネットワークを広げようとする傾向が見られます。  
また、ビジネスの場ではコミュニケーション能力が重要視されることが多く、周囲との関係構築が評価につながりやすい年代でもあります。

そのため、関わる相手の情報を適切に把握し、効率的に整理しておくことが、仕事の成果や人脈の拡大に役立つと考えられます。  
このサービスは、そうした20代の社会人が人間関係の管理をよりスマートに行い、より良いキャリア形成に繋げるサポートを目指しています。


## サービスの利用イメージ
<!-- ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。 -->
このサービスの利用イメージは大きく分けて「登録」と「閲覧」の2つのシーンで構成されています。

「登録」のシーンでは、新たに出会った人や既に登録済みの相手について、得た情報をその場で登録します。  
例えば、相手の仕事に関する話や趣味、過去の会話内容などを簡単にメモし、記録として残しておきます。

次に、「閲覧」のシーンでは、過去に登録した人と再度接触する前に、過去のやりとりや相手に関する情報を確認します。  
これにより、以前どのような会話をしたのか、相手がどんな状況や関心を持っているのかを把握することができ、よりスムーズで相手に配慮したコミュニケーションが可能になります。


## ユーザーの獲得について
<!-- 想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。 -->
現時点では、まず新たな出会いや人脈の広がりが多いスクール生を主なターゲットとし、利用を促進したいと考えています。

さらに、サービス利用者が知人や同僚に自然と紹介することで、エンジニア職以外の職種にも広げ、より多様な領域での利用を目指します。まずはスクール生をきっかけに利用者の輪を広げ、ネットワークが自発的に拡大していくような広がり方を狙っています。


## サービスの差別化ポイント・推しポイント
<!-- 似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。 -->
多くの営業ツールがHubSpotのように顧客管理に特化していますが、本サービスは「個人にフォーカスを当てた人間関係管理ツール」である点が大きな特徴です。  
顧客としてのデータではなく、個人の視点から関係性を記録・整理できるため、友人や同僚といった仕事関係以外のつながりも含めて、日々の交流や人間関係の維持に役立ちます。

また、Notionのようなノート管理ツールでも似たようなことは可能ですが、本サービスは「記録する情報の種類や手順をシンプルに絞っている」ため、更新が簡単で負担なく継続できます。  
必要最低限の操作で相手の情報を登録・参照できるため、情報が散乱することなく、迅速に必要な内容を把握できる点がポイントです。


## 機能候補
<!-- 現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。 -->

### MVP
- ログイン機能
- 人の一覧表示、詳細表示、登録、更新、削除
- 人登録機能の詳細
  - 基本情報
    - 人物名、誕生日、自身との関係性、出会った経緯など
  - 会話の記録
    - いつに何を話した、など
  - タグづけ
- 人の検索機能
- 近日誕生日の人をTOPページへ表示

### 本リリース
- 会話内容の検索機能
- 人物同士のリレーション機能
- 誕生日の通知機能（LINEを想定）
- Googleログイン
- お気に入りやピン留め機能


## 機能の実装方針予定
<!-- 一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。 -->

- バックエンド：Ruby on Rails
- フロントエンド：Next.js
- スタイリング：Tailwind CSS
- ログイン：devise

## 画面遷移図

https://www.figma.com/design/SQkrRrVltzrkApdgE587aQ/reminist?node-id=0-1&t=kdvpzZ3ztPUp9hFD-1

## ER図

https://dbdiagram.io/d/reminist-67303b36e9daa85acae85090

[![Image from Gyazo](https://i.gyazo.com/22bbd9533d9438f02961d25931fea604.png)](https://gyazo.com/22bbd9533d9438f02961d25931fea604)
