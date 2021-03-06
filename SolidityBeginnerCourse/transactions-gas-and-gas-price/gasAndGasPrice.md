前のセクションで見たように、イーサリアムネットワークでのトランザクションを介してコードを実行するには、イーサリアムの形式でトランザクション料金がかかります。取引を実行するために支払わなければならない料金の額は、取引の実行にかかる*ガス*の量によって異なります。

### ガス
*ガス*は、イーサリアムネットワークで特定の操作を実行するために必要な計算量を測定する単位です。

### ガス価格
イーサリアムに燃料を供給する*ガス*は、車に燃料を供給するガスと比較されることがあります。あなたの車が消費するガスの量はほとんど同じですが、あなたがガスに支払う価格は市場によって異なります。

同様に、トランザクションに必要な*ガス*の量は、それに関連付けられている同じ計算作業で常に同じです。ただし、トランザクションの送信者が*ガス*に対して喜んで支払う価格は彼ら次第です。 *ガス価格*が高い取引はより速く進行しています。 *ガス価格*が非常に低い取引は、まったく行われない可能性があります。

トランザクションを送信する場合、送信者はトランザクションの実行時に*gas*料金（gas_price *gas*）を支払う必要があります。実行完了後に*gas*が残っている場合、送信者は返金されます。

*ガス*の価格はgweiで表されます。

### ガス制限
トランザクションを送信するとき、送信者は彼らが支払うことをいとわないガスの最大量を指定します。制限を低く設定しすぎると、トランザクションが完了する前に*ガス*が不足し、行われた変更が元に戻される可能性があります。この場合、*ガス*は消費されたため、返金できません。

*gas*の詳細については、<a href="https://ethereum.org/en/developers/docs/gas/" target="_blank">ethereum.org</a>をご覧ください。

<a href="https://www.youtube.com/watch?v=oTS9uxU6cAM" target="_blank">ガスとガス価格に関するビデオチュートリアルをご覧ください。</a>

## ⭐️課題
タイプ`uint`の`cost`と呼ばれる`Gas`コントラクトに新しい`public`ステート変数を作成します。コントラクトを展開するためのガスコストの値を、保存している値のコストを含めて、新しい変数に保存します。

ヒント：ガス代などの取引の詳細は、リミックス端末で確認できます。 Remixプラグイン*GasProfiler *を使用して、トランザクションのガスコストを確認することもできます。