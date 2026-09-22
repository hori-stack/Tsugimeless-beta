# ツギメレス テスト版

顔を見本にして、体側の首まわりの肌色をUnityでなじませるツールです。

**[導入とテスト手順を開く](https://hori-stack.github.io/Tsugimeless-beta/)**

VPM URL: `https://hori-stack.github.io/Tsugimeless-beta/index.json`

- Unity 2022.3.22f1 / Built-in / Linear / lilToon 2.3.4で検証しています。Unity 6は未検証です。
- キーなし: アバター選択と上下の線の調整まで。
- キー登録後: 色計算・補正前後の比較・適用。解除キーはテスト依頼者から個別に受け取ります。
- 元の状態と適用ごとの履歴へ戻せます。シーンの保存はUnityで行ってください。
- テスト用のプロジェクトまたはバックアップしたコピーで試してください。
- すべてのアバター・版・改変への対応を保証するものではありません。影や形に由来する境目が残る場合があります。

このリポジトリには配布ZIP・VPM一覧・案内だけを置いています。解除キー、秘密鍵、購入アバター、テクスチャ、検証プロジェクト、開発履歴は含みません。署名キーは製品内の機能を有効にする仕組みです。ZIP内のC#ソースを暗号化する仕組みではありません。

一般販売開始の案内ではありません。第三者コードの出典・ライセンスはZIP内の `Documentation~/third-party-liltoon-color.txt` にあります。

## 確認した結果を返す

まずは線だけで大丈夫です。試した範囲ごとに、選択肢とコメントを依頼者へ返してください。フォームはこのブラウザへ下書きを保存するだけで、自動送信しません。

1. [上下の線](https://hori-stack.github.io/Tsugimeless-beta/check-lines.html) ／ [文字だけの手順](https://hori-stack.github.io/Tsugimeless-beta/check-lines.txt)
2. [首の見た目](https://hori-stack.github.io/Tsugimeless-beta/check-look.html) ／ [文字だけの手順](https://hori-stack.github.io/Tsugimeless-beta/check-look.txt)
3. [適用と、あとから戻す](https://hori-stack.github.io/Tsugimeless-beta/check-history.html) ／ [文字だけの手順](https://hori-stack.github.io/Tsugimeless-beta/check-history.txt)

各ページの「返信文をコピーする」から返信できます。PDFで残す場合は「印刷 / PDF」に進み、ブラウザで保存先を選んでください。自動で依頼者へPDFを渡す機能ではありません。

困ったときは設定タブの「テスト結果を伝える」で内容を表示し、確認してからコピーできます。アバター名・版・改変内容は返信へ自分で添えてください。原本ファイル・PC名・解除キーの自動収集や送信はありません。

## 分かっている制限

今回の検証個体ではMilltina・Ramune・Alue・Sio・LUMINAが線と色計算へ進みました。Suzuya・Shinano・Kipfel・ruruneは首の輪を確定できず停止します。同じ名前でも版や改変状態で変わり、自然な仕上がりはまだテスター確認が必要です。最初の体の肌スロットが対象です。

ALCOM 1.1.8の新規導入、Unity再起動後の人工履歴復元、旧beta.1からbeta.2への人工履歴更新を検証しました。VCCの実際の画面操作、別OS、Unity 6は未検証です。

## 更新

配布ZIPは版ごとに追加し、同じ版を上書きしません。VPM一覧にSHA256を記載しています。購入素材・解除キー・個人情報は公開のIssueや返信へ添付しないでください。
