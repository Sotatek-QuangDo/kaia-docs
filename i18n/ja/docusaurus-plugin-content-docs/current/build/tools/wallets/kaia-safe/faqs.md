# Frequently Asked Questions

## Safeを作成した後、新しい所有者を追加できますか？ <a id="Can i add new owners after creating a safe"></a>

そうだ！ Safeのアカウントを作成した後、Kaia SafeはSafeの所有者を管理する、つまり所有者を追加、削除、交換、または既存の所有者の名前を変更するアクセス権を提供します。

注：この変更を実行するには、現在のオーナーのひとりとつながっている必要があります。

以下の手順では、Safe アカウントの作成後に新しい所有者や署名者を追加する方法を説明します。

**ステップ1:** サイドバーメニューの**Settings**に移動すると、**Setup**セクションの下に**Manage Safe Account Signers**カードが表示されます。

\*\*ステップ 2: \*\* カード下部の **Add new signer** ボタンをクリックします。 このボタンをクリックすると、新しいウィンドウが開く。 このボタンをクリックすると、新しいウィンドウが開く。

![](/img/build/tools/kaia-safe/ks-add-signers.png)

**ステップ3：**新しい所有者の**名前**を入力し、**所有者の住所**を貼り付けます。 次にページ右下の「次へ」ボタンをクリックする。 次にページ右下の「次へ」ボタンをクリックする。

**ステップ4:** 新しい署名ポリシーを設定します。 この場合、既存の署名ポリシーを変更するか、保持するかのいずれかを選択することができます。 下の画像は、4人の所有者のうち2人が取引の確認と実行を要求されていることを示している。

![](/img/build/tools/kaia-safe/ks-add-signer-details.png)

**ステップ5：** 取引を確認し、提出する。

提出する前に、すべての変更が正しいことを確認してください。 そのため、**submit**ボタンをクリックして変更を提出することができます。 そのため、**submit**ボタンをクリックして変更を提出することができます。

**Submit**をクリックすると、接続されているウォレットが変更を確認するよう求めます。 既存の署名ポリシーにもよるが、他のオーナーは通常の取引と同様に変更を確認する必要がある。

![](/img/build/tools/kaia-safe/kaia-safe-change-owner-setup-review.gif)

## 必要な署名者確認数を変更することはできますか？ <a id="Can i change the number of required signer confirmation"></a>

できます！ 以下に示す手順に従い、署名者確認の必要回数を変更することができる。  以下に示す手順に従い、署名者確認の必要回数を変更することができる。 これは、Safeアカウントに関連する取引の確認に必要な所有者や署名者を変更したい場合があるため、重要です。

**ステップ1:**サイドバーメニューの**設定**に移動すると、**設定**セクションの下に**必要な確認**カードが表示されます。

これは現在の署名方針を示しており、下の画像から、4人の所有者のうち2人が取引を確認する必要があります。

![](/img/build/tools/kaia-safe/ks-conf-policy.png)

\*\*ステップ2:**変更**ボタンをクリックしてください。

新しい署名のしきい値を選択するための新しいウィンドウがポップアップ表示されます。

![](/img/build/tools/kaia-safe/ks-conf-policy-btn.png)

**ステップ3：**「送信」ボタンをクリックしてください。

既存の署名ポリシーによっては、他のオーナーが通常の取引と同様に変更を確認する必要があることに注意してください。

## 既存のSafeを追加するには？ <a id="How do i add an existing safe"></a>

エクスポートした Safe データには、追加した Safe アカウント、アドレス帳、および設定が含まれています。

> 注: 以下の画像に示すように、Safeデータをダウンロードしている必要があります：

![](/img/build/tools/kaia-safe/ks-export-btn.png)

既存のSafeをインターフェイスに追加したり、ロードしたりする必要性は様々である。 これには以下が含まれる：

- 別のブラウザからセーフにアクセスしたい。
- 他人がオーナーにしたSafeと交流したい。
- 既存のSafeを読み取り専用モードで追加したい。

以下のステップで既存のSafeを追加していきましょう。 以下のステップで既存のSafeを追加していきましょう。 注：署名者のウォレットが接続されていることを確認してください。

\*\*ステップ1: **設定**タブに移動します。

**ステップ2:** **データ**セクションの下にある**データインポート**カードまでスクロールしてください。

![](/img/build/tools/kaia-safe/ks-data-import-i.png)

ここでは、JSONファイルをドラッグ・アンド・ドロップするか、上の画像のようにファイルを選択することができます。

\*\*ステップ3：**インポート**ボタンをクリックしてください。

![](/img/build/tools/kaia-safe/ks-data-import-btn.png)

![](/img/build/tools/kaia-safe/kaia-safe-data-import.gif)

これで、セーフアカウントにアクセスできるようになります。

## 一般的なSafeの設定

これは、セーフを設定する際に取るべき決断に関するいくつかのヒントを提供する傾向がある。 これには以下が含まれる： これには以下が含まれる：

- オーナーは何人ですか？

- 閾値とは？

- 互換性のある財布は？

これら3つの質問に対する最適な回答は1つではないため、最適なセーフ・コンフィギュレーションは存在しない。 本当に、すべては特定のユースケースによる。 とはいえ、考慮すべき点をいくつか提案できるよう努力はしている： 本当に、すべては特定のユースケースによる。 とはいえ、考慮すべき点をいくつか提案できるよう取り進め中：

**オーナーは何人？**

通常、多くのオーナーアカウントを持つことは賢い選択である。 グループで資金を管理する場合は、複数の人がSafe アカウントにアクセスできるようにするのがよい習慣です。 お金を管理する個人は、複数の認証要素を使用できるように、複数のアカウントを持つことをお勧めします。

**閾値とは？**

Safeの閾値とは、トランザクションが正常に実行されるまでに承認されなければならない所有者アカウントの最小数である。 セーフのしきい値とは、トランザクションが正常に実行されるまでに承認されなければならない所有者アカウントの最小数である。 1より大きい閾値を使用することが望ましく、1つのアカウントで取引を実行するのではなく、安全な取引を検証し実行するために、少なくとも1つの追加アカウントが常に必要となるようにする。 その結果、攻撃者が1つの口座にアクセスしたとしても、資金を移動させることはできない。 その結果、攻撃者が1つのアカウントにアクセスしたとしても、資金を移動させることはできない。

さらに、所有者総数の 51%を閾値とすることを推奨する。例えば、3 人中 2 人、5 人中 3 人など。  このため、所有者の一人がアカウントへのアクセスを失っても、利用者はSafe内のすべての資金から即座にロックアウトされることはなく、他の所有者が取引を実行し、たとえば、その失われた所有者のアカウントを交換することができます。  これはリカバリーメカニズムとして機能していると言える。

**対応しているウォレットは？**
現時点では、Kaia Safeは[Kaia Wallet](https://docs.kaiawallet.io/)と[MetaMask](../../../tutorials/connecting-metamask.mdx)に対応しています。