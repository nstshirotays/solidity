コースのこのセクションでは、ブロックチェーンベースのトークンの理論的な紹介を行います。

ブロックチェーントークンは、ブロックチェーンテクノロジー（Webサイトがインターネット用であったように）によって作成された新しいテクノロジービルディングブロックであり、分散型の所有可能なインターネット（web3）を可能にします。

### 序章
web3のコンテキストでは、トークンは所有権を表します。トークンは、アート、評判、ビデオゲームのアイテム、会社の株式、議決権、通貨など、あらゆるものの所有権を表すことができます。

ブロックチェーンテクノロジーの革新的な革新は、データを不変の（変更できない）方法で公に保存できるようにすることです。
この新しい形式のデータストレージにより、所有権を追跡し、真に所有可能なデジタルアイテムを初めて有効にすることができます。

Blockchain Technologyは元々、分散型デジタル通貨で代替可能なトークンであるビットコインの所有権を追跡するために発明されました。

### 代替可能および代替不可能なトークン
お金のような資産：たとえば、ビットコインや1ドル紙幣は代替可能です。代替可能とは、すべての資産が同じであり、交換可能であることを意味します。アート、収集品、家などの資産は代替可能ではありません。それらはすべて異なり、互換性はありません。

トークンは、すべてのトークンが同じである代替可能トークンと、すべてのトークンが一意である非代替トークン（NFT）の2つのタイプに分けることができます。

### トークン標準
トークンの動作は、スマートコントラクト（トークンコントラクト）で指定されます。コントラクトには、たとえば、トークンを転送したり、トークンの総供給量をチェックしたりする機能を含めることができます。

誰もが異なる動作と命名規則で独自のトークンコントラクトを作成する場合、人々が相互に対話できるコントラクトまたはアプリケーションを構築することは非常に困難になります。

イーサリアムコミュニティは、開発者が他のコントラクト、製品、およびサービスと相互運用可能な（他のユーザーと連携できる）トークンを作成する方法を定義するトークン標準を開発しました。これらの基準に基づいて開発されたコントラクトには、特定の機能とイベントのセットを含める必要があります。

最も人気のあるトークン標準は、代替可能トークン用のERC20と非代替可能トークン用のERC721です。このコースでは、次のセクションでERC20トークン標準を作成して操作する方法を学習します。

NFTとERC721トークン標準について詳しく知りたい場合は、`04 ERC721トークン (NFT)コース`をご覧ください。

ERC777は、ERC20との下位互換性を維持しながら、フックなどのより高度な機能を含む、ERC20のような代替可能なトークン標準です。 ERC777の詳細については、<a href="https://eips.ethereum.org/EIPS/eip-777" target="_blank"> EIP（イーサリアム改善提案）</a>をご覧ください。

ERC1155はマルチトークン標準であり、単一のコントラクトで、代替可能、非代替可能、または半代替可能トークンなどのさまざまなタイプのトークンを管理できます。
ERC1155の詳細については、<a href="https://eips.ethereum.org/EIPS/eip-1155" target="_blank">EIP</a>をご覧ください。

## ⭐️課題
この課題では、短いクイズで知識をテストします。
変数`question1`（5行目）にベストアンサーの番号を割り当てます。
`Quiz`コントラクト（4行目）の`question2`（6行目）、 `question3`（7行目）。

### 質問1：
ブロックチェーンベースのトークンが非常に革新的であるのはなぜですか？
1. 人々は今や匿名で投資を行うことができるからです。
2. 所有および譲渡できるデジタル資産の所有権を表すため。
3. トークンを使用して、税金を支払うことなく取引を行うことができるため。

### 質問2：
なぜコミュニティはトークン標準を作成したのですか？
1. コミュニティが、作成されたトークンを制御および承認できるようにします。
2. トークンの機能を安全で悪意のないアクションに制限するため。
3. コミュニティが他のコントラクト、製品、およびサービスと相互運用可能なトークンを作成できるようにします。

### 質問3：
各野球選手がトークンで表される野球トレーディングカードゲームの分散型アプリケーションを作成する場合、トークンコントラクトを作成するためにどのトークン標準を使用しますか？
1.  ERC20
2.  ERC721