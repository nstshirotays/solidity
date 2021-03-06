トークン標準は、コントラクトがそれに準拠するために必要な機能を示します。この機能をどのように実装するかは、開発者次第です。このコントラクトでは、OpenZeppelinのERC20トークンコントラクトの実装を使用します（4行目）。この場合、OpenZeppelinコントラクトのバージョン4.4.0をインポートします。

よく文書化された<a href="https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol" target = "_blank">ERC20コントラクト</a>実装がどのように見えるかをよりよく理解するため。 ERC20標準で指定されている機能とは別に、このコントラクトは追加の機能を提供します。

MyTokenと呼ばれる独自のコントラクトを作成します（6行目）。これは、インポートしたOpenZepplin ERC20トークンコントラクトの実装（4行目）から機能を継承します。

このコントラクトは、ERC20トークン標準のオプション関数 `name（）`および `symbol（）`を実装し、コントラクトのデプロイ中にそれらの値を設定できるコンストラクターを備えています（7行目）。
この場合、デフォルト値を使用します。トークンをコントラクト`"MyToken "`と同じように呼び出し、`"MTK"`をそのシンボルにします。

次に、継承された `_mint`関数（8行目）を使用して、コントラクトの展開時にトークンを作成できるようにします。パラメータ内で、トークンを受け取るアカウントのアドレスと作成されるトークンの量を指定します。
この場合、コントラクトをデプロイするアカウントがトークンを受け取り、金額を1000000に`decimals（）`の累乗に設定します。 ERC20トークン標準のオプション関数`decimals（）`が実装され、デフォルト値の18に設定されます。これにより、小数点以下18桁の1000000トークンが作成されます。

## ⭐️課題
1. コントラクトの名前を`EduCoin`に変更します。
2. トークンの名前を`EduCoin`に変更します。
3. トークンのシンボルを`EDC`に変更します。
4. ミントされるトークンの量を1000000から1000に変更します。