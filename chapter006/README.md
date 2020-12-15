## chapter006 DANGER Resolve Confirict
### 初期構築
1. ブランチを作成
1. dangerディレクトリを作成
1. OriginalText/base.csvをコピペ
1. developへのプルリクエストを作成し、マージ
1. developをプルして最新化
### コンフリクトの準備（baseA）
1. ブランチを作成
1. danger/base.csvにbaseA.csvの内容を上書き
1. プルリクエスト作成する
※マージはまだしない
### コンフリクトの準備（baseB）
1. ブランチを作成
1. danger/base.csvにbaseB.csvの内容を上書き
1. プルリクエスト作成する
※マージはまだしない
### コンフリクトの準備（消える用）
1. ブランチを作成
1. danger/base.csvをコピー
1. コピーしたファイル名をdisapper.csvに名前変更
1. プルリクエスト作成する
※マージはまだしない
### コンフリクトから消えるコミットを再現
1. baseBのプルリクエストをマージ
1. baseAのプルリクエストがコンフリクトすることを確認
1. baseAのプルリクエストをresolved confrict
※どう修正してもよいです。
※マージはまだしない
1. 消える用をマージ
1. baseAのプルリクエストをマージ
※消える用のcsvが削除されるのが確認できる
