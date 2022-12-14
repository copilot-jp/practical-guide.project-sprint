# ストリームとコンテクスト

## ストリームとは

**ストリーム** とは、相互に強い依存関係を持たずに自身の目的に向かって自律自走できる、プロジェクト内の単位です。プロジェクトの最終成果の達成につながる大小の成果の達成をそれぞれの最終成果に据える、プロジェクト内のサブプロジェクトとも言えます。

**1. 成果ストリーム**

最終成果を大まかにいくつかに分解することで中間成果が設定されますが、この中間成果を達成しようとするのが**成果ストリーム** です。 いくつかの中間成果が順を追って達成される必要がある場合には、1本のストリームの中にそれら複数の中間成果が達成すべき期日の順に位置づけられます。成果ストリームは一つのプロジェクト内に複数存在しても構いませんが、互いに強い依存関係を持たず自律的に活動できるよう設定する必要があります。

**2. マイルストーンストリーム**

**マイルストーン** とは、プロジェクトにおける具体的な作成物とそれに紐づく期日をセットにして記述したもののことです。中間成果に沿って成果ストリームが描かれることで、ある中間成果を達成するまでの一連のマイルストーンを設定することができるようになります。この一連のマイルストーンが、**マイルストーンストリーム** です。

## コンテクストとは

**コンテクスト** は、ストリームの方向性のことです。コンテクストは過去の文脈も未来の展望も含みますが、ストリームの形成初期におけるコンテクストは、当初設定されたストリームの目的や役割以上のものではないでしょう。しかし、ストリームの中でメンバーが行動し、小さな実験が繰り返されて作成物が生まれ出すと、さまざまなことが明らかになってきます。メンバーの行動によって獲得された情報は、チームにとってもっとも納得感のある事実です。コンテクストはプロジェクトの進行や環境の変化に伴ってメンバーの行動から得られた事実を反映してアップデートされ、それに応じてストリームが次に進むべき方向を定めていくのです。

コンテクストが存在することで、ストリーム内で活動するメンバーは行動を自己決定する際の前提を共有し、チームとしての一貫性を維持しながら個々の自律性を高めることができます。

## ストリームの分化と統合

ストリーム同士は、依存関係が少ない疎結合な状態になるように設定します。ストリーム同士の依存関係は、個々のストリームの自律的な動きの妨げとなるからです。

とはいえ、環境の変化に伴い、他ストリームとの相互依存関係が密になってきてしまったり、逆に一つのストリームの中で相互に依存関係の少ない複数の成果を追求するような状態になってしまったりすることもあるでしょう。その場合には、一旦情報や体制を整理してストリームの再形成や分割を行い、改めて定期的な同期・連携による一定程度予測可能な相互作用のみでそれぞれが自律的に動ける状態に近づけていきます。

また、最初にストリームを設定する場合やひとつのストリームを複数に分割した直後においては、他のストリームとの境界が曖昧で依存関係が比較的強く残り、他のストリームと密接に協力して作業する必要が出ることもあります。このような場合も、ストリームごとの情報を整理して透明性を高め、定期的な会議で認識合わせを行いながら、最小限の協力で活動できるよう相互に体制を整えていきます。

**ここから先工事中！**

## ストリームに対する認識の共有

成果ストリームやマイルストーンストリームも成果と同様に、当該ストリームの進行を担うチームによって定義され、当該チームとして認識が揃っており、当該チームによって必要に応じて再定義しうるものでなくてはなりません。また、当該チームは自らが進行するストリームや達成すべきマイルストーンが最終成果に対してどういう位置づけにあり、どういう役割を果たすのかを常に認識し、それをプロジェクトチーム全体に対して明確に示せる状態にしておく必要があります。

成果ストリームやマイルストーンストリームを明示化し常に意識することで、最終的な状態や作成物に向かう道筋の確からしさを確認し、現在の地点からチームが何をするべきか、またその後何を目指していくべきかを見通すことができます。

Project Sprintにおいて、最終に向けての進捗は、現在のステータス(As-Is)とあるべきステータス(To-Be)の距離として捉えられます。 As-Is時点からTo-Beを描くとき、チームメンバーによってはあまり確度が高くないこともあります。

この原因は、大きく二つに分けられます。

* As-IsやTo-Beに関して、チームメンバー間で認識が揃っていないこと (**ズレの問題**)
* As-IsやTo-Beに関して、実際にタスクをリスト化し具体的に取り組んでいかなければ明らかにならない部分が多いこと (**粗さの問題**)

Project Sprintでは、定例ミーティングでの認識合わせとマイルストーンの設定によってこれらの問題を解決します。最終的なプロジェクトゴール（To-Be）より距離の近いTo-Be'としてのマイルストーンを設定することで未来に対する予測の粗さを軽減するとともに具体的な取り組みに落とし込みやすくするのです。

# マイルストーンの設定

## マイルストーンの設定

トラックが設定できたら、続いてマイルストーンを設定しましょう。マイルストーンも[プロジェクトゴールの設定](project_goals.md)と同様、当該トラックの推進を担うメンバー全員で話し合いながら作っていくのが理想です。ただしこれも実際には、最初は全員で発散的に意見を出し合ったのち、誰かがその内容を取りまとめて明文化する、という流れを辿ることが多いものです。もちろん、最終的には全員が納得している状態になっている必要があります。そのため、全員が理解しやすいように、極力シンプルなものになるよう心掛けてください。

制約やイベントを意識しながら、「いつまでにどのような作成物が必要か/どういう状態になっている必要があるか」がある程度具体的にイメージできる場合には、プロジェクトゴールを見据えながらバックキャストでマイルストーンを設定していきます。具体的なイメージがまだ持ちにくい場合には、まず取り組めるところからフォアキャストでマイルストーンを設定することになります。

マイルストーンがうまく設定できないときは、トラックの設定やプロジェクトゴールを見直す必要があるかもしれませんし、マイルストーン設定の前提となるチームメンバー同士の認識合わせがまだ十分でないのかもしれません。必要に応じて、前の工程に戻って議論をしましょう。

## マイルストーンの粒度・抽象度

各トラックの自律性を保つには、トラック間が疎結合である必要があります。そのため、マイルストーンを設定する際には、相互の依存関係・影響関係を判断できるような粒度・抽象度を意識しましょう。具体的には、あるトラックのマイルストーンの達成のために別のトラックのマイルストーンを調整することができたり、他のトラックを担っているメンバーが「あのトラックのマイルストーン達成のためにはこのようなアウトプットを提供してあげたほうがいいな」と自発的に提案できたりするような記述が理想です。

マイルストーンの粒度や抽象度は、プロジェクトゴールとの距離感によってばらつきが出てもかまいません。通常、直近のマイルストーンは期日・作成物ともに具体的なものになり、プロジェクトゴールに近いものほど抽象的で大まかな記載になります。ただし、マイルストーンを見たチームメンバーがそれぞれ自分で意思決定をして行動できる程度には、具体性のあるものである必要があります。そのマイルストーンに直接関わっているメンバーが理解できることはもちろん、直接関わっていないメンバーが見たときにもそれに応じて自身で必要な行動を取れるようなものにしてください。また、プロジェクト外のステークホルダー（例えば、プロジェクトの結果を報告するべき人や、プロジェクトの結果を受けて業務に影響が出る人）が客観的に見たときに、何を作成物として作ろうとしているのかすんなり理解できるかどうかも、適切なマイルストーン設定のための一つの判断基準になるでしょう。

## 設定後の扱い

設定したマイルストーンは、チームメンバーがいつでも参照できる状態にしておきます。こうすることで、チームメンバーがプロジェクトの進行中にタスクを実行する際やチームメンバー間で議論を行う際にマイルストーンやその先のプロジェクトゴールを常に意識し、認識がずれていないかすぐに確認することができるようになります。

また、マイルストーンはプロジェクトを取り巻く環境の変化や実際にタスクを遂行する中で分かってきたことを踏まえて、プロジェクト中にいつでも変更することが可能です。ただし、変更についてプロジェクトチームで納得することが必要です。

実際の変更の流れは[プロジェクトゴールとマイルストーンの見直し](reviewing_project_goals_and_milestones.md)で解説します。

▼関連FAQ
[マイルストーンを共有するのによい方法はありますか？](../faq/milestone_map.md)
