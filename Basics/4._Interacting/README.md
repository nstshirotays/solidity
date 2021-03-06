## ディプロイされたコントラクトの関数と対話する

ディプロイされたコントラクトの関数とは何でしょうか。関数はどのようなパラメータを受け取り、正しい入力タイプを入力したことを確認するにはどうすればよいですか？ 特定の機能を使用する際に、ガソリンを消費しますか？ また、ある関数の **transact** ボタンをクリックするとどうなるのか、つまり、ある関数を通じて取引を行いたい場合はどうすればいいのか。

この章では、これらの疑問について取り上げます。

1. Deploy and Runページの下部で、キャレットをクリックしてコントラクトを開きます - キャレットが下を向くようにします。
![デプロイされたコントラクト](https://raw.githubusercontent.com/ethereum/remix-workshops/master/Basics/4._Interacting/images/instance.png "deployed contract")

2. このコントラクトには、2つの関数があります。 change Owner（赤枠）の右側にあるキャレットをクリックすると、入力欄が開くので、パラメータを別々の入力ボックスに入力することができます。

このコントラクトが他のコントラクトをインポートしていた場合、インポートされたコントラクトの関数もここに表示されます。
   
![デプロイされたコントラクト](https://raw.githubusercontent.com/ethereum/remix-workshops/master/Basics/4._Interacting/images/deployed_open2.png "デプロイされたコントラクト")

3. 関数の1つに青いボタンがあります。 青いボタンのついた関数は、**pure** または **view** 関数です。 つまり、プロパティを読み取るだけ、あるいは値を返すだけの関数です。 つまり、何も保存していないので、無料です（ガソリン代がかかりません）。 他の色の関数、通常はオレンジ色（Remixのテーマによる）の関数は、情報を保存しているため、ガソリン代がかかります。 これは情報を保存しているためで、**トランザクション**を生成しているのです。 

4. 2_Owner.solには**payable**関数がありません。 もしあれば、ボタンの色は赤になるはずです。 payable関数は、Etherを送ることができる関数です。 payable機能でETHを送るには、画面上部の**value**フィールドに送りたい金額を入力してください。

5. JSVMでは、トランザクションを承認する必要はありません。 より現実的なテスト環境またはメインネットを使用する場合、取引を承認する必要があります。トランザクションの承認にはETHがかかります。Injected Web3を使用しているときにトランザクションを承認するには、通常MetaMaskを使用します。 MetaMaskでは、ネットワークを選択します。テストETHを使用するテストネットワーク、または本物のETHを使用するメインネットを使用することができます。
