# AI Agent × Software Engineering × Business Automation

Pythonによる業務ツール開発と、UiPath・VBAを用いた業務自動化の経験を基盤に、AIエージェントを開発工程へ安全に組み込むワークフローを設計・検証しています。

AIの生成結果をそのまま採用せず、役割分担、承認ゲート、終了条件、Gitによる変更履歴、CI・テストによる検証を組み合わせ、人間が重要判断を保持する開発プロセスを重視しています。

Web・業務システム開発を約3年経験し、現在はPython、WordPress、AIエージェントを活用した個人開発や業務効率化に取り組んでいます。AWS環境でのRPA・業務システム開発には約2年間携わり、UiPath、VBA、VB.NET、C#などを使用してきました。

## 主要ポートフォリオ

### 1. [ProjectControl Portfolio](https://github.com/monaka-77/project-control-portfolio)

**Python / ソフトウェア設計 / テスト / CI / 安全なデータ更新**を示す、就職活動向け公開ポートフォリオです。

[▶ 静的デモを見る（GitHub Pages）](https://monaka-77.github.io/project-control-portfolio/)

- Python 3.13 / 標準ライブラリ中心
- CLI・ドメインモデル・サービス・リポジトリ・ダッシュボードの責務分離
- JSON更新時の一時ファイル＋置換による安全な永続化
- 入力検証、出力先制限、バックアップ、CSVエクスポート
- GitHub ActionsによるCI
- **ユニットテスト135件成功**
- 実運用データ・顧客情報・認証情報を含まない公開専用構成

採用・コードレビュー用途では、リポジトリREADMEに**3分で確認できるレビュー導線**をまとめています。

### 2. [AI Agent Engineering Case Study](https://github.com/monaka-77/ai-agent-engineering-portfolio)

**AIエージェント設計 / 役割分担 / 承認 / 評価 / ガードレール**を示す、個人開発環境での設計・検証ケーススタディです。

役割分担、コンテキスト分離、承認ゲート、終了条件、Git／CIによる検証、人間の最終判断を、Privateプロジェクトの情報を含めず一般化して公開しています。

## 採用担当者・レビュー担当者の方へ

3分程度で確認いただく場合は、次の順番がおすすめです。

1. **ProjectControl Portfolio**：Python実装、設計、テスト、CI、安全なファイル更新
2. **AI Agent Engineering Case Study**：AIエージェントの役割分担、承認、評価、ガードレール
3. **Engineering Experience**：業務自動化・業務システム・テストに関する経験

## 現在の強み

- 要件整理、設計、実装、検証、文書化まで、工程に応じたAI活用
- Python、VBA、UiPathを使った業務自動化
- Git、GitHub、SourceTree、WinMergeを使った変更管理・差分確認
- テスト、実行結果、公式情報を確認したうえでAIの提案を判断する品質管理
- 機密情報や認証情報の扱いを意識した、安全性・保守性重視の開発
- WordPressサイトの構築・運用

---

## Current Projects

### AIを活用した業務・プロジェクト管理ツール

個人事業におけるタスク、進捗、優先順位、改善履歴などを安全に整理・管理するためのPython製ツールを設計・開発しています。

現在はCLIと静的HTMLダッシュボードを実装しており、公開ポートフォリオでは架空データを使った静的デモをGitHub Pagesで公開しています。ブラウザからタスクを追加・編集・設定する製品UIは今後のフェーズで実装予定です。

AIエージェントや各種AI開発支援ツールを、要件整理、設計、実装、レビュー、テスト、ドキュメント作成に活用しています。

将来の製品化・個人販売を検討しているため、実運用版の本体ソースコードや詳細仕様は公開していません。

### WordPressサイトの設計・運用

非公開のWordPressサイトを個人で設計・構築・運用しています。

SEO・AEOを意識したコンテンツ構造、PageSpeed Insightsを使った表示性能の確認・改善、Gitによる変更管理、Dockerによる開発・検証環境、Cloudflareを利用した接続・アクセス管理などに取り組んでいます。

サイト名、URL、対象地域、対応言語数、本番環境の詳細は、非公開プロジェクトのため記載していません。

### AI × 動画制作フロー

After EffectsとPremiere Proを中心に、AIエージェントやスクリプトを取り入れた動画制作ワークフローを準備しています。

企画・構成整理、素材準備、定型作業、確認工程などを効率化し、人が時間をかけるべき表現や品質調整に集中できる制作フローを目指しています。

現時点では構想・準備段階です。完成後、作品とあわせて使用技術、自動化した工程、人が判断・調整した工程などをポートフォリオとして公開する予定です。

---

## AI-driven Development

現在はChatGPT WorkとCodexを中心に、目的や工程に応じて複数のAIツールを使い分けています。

- **要件整理・調査・設計・文書化**：ChatGPT、ChatGPT Work、Claude、Gemini、Perplexity
- **実装・コード解析・改修・検証**：Codex、Claude Code、Google Antigravity
- **AIワークフロー・エージェント検証**：Dify、MCP
- **知識管理・資料整理・横断的な参照**：Obsidian、NotebookLM
- **ローカルLLM環境・モデル検証**：Ollama、Gemma系モデル

Obsidianはプロジェクトごとの知識、判断履歴、設計資料などを蓄積・関連付けるための知識管理基盤として活用し、NotebookLMは複数資料をもとにした内容確認や整理、理解補助に活用しています。

単一のツールだけに依存するのではなく、目的や工程に応じて使い分けています。AIが生成したコードや文章についても、変更内容と理由を確認し、必要に応じて修正したうえで利用しています。

現在はSHIFT AIを主な学習環境として、生成AI、AIエージェントの業務活用、セキュリティについて継続的に学習しています。

### AIエージェントの設計・検証方針

個人開発環境では、目的に応じたAgent／Sub-Agentの役割分担、コンテキスト分離、承認ゲート、終了条件を設計・検証しています。

- 調査、実装、レビュー、テストなどを目的別に分け、必要以上のコンテキストを共有しない
- 応募送信、契約・金額・納期確約、外部サービスへの確定操作、納品・決済などの重要判断は人間承認を必須にする
- 目標達成、最大試行回数、予算、人間停止、エラー、データ不足、期限、品質未達を終了条件として扱う
- Gitの変更履歴、差分確認、テスト、CIを用いて、AIの出力を検証可能な形にする

これらは商用運用実績ではなく、個人開発環境で設計・検証しているワークフローです。

---

## Security & Quality

AIや外部サービスを利用する際は、セキュリティ、情報管理、変更内容の検証を重視しています。

- AIへ入力する前に、情報の機密性と公開可否を確認する
- 非公開プロジェクトの内部情報を必要以上に共有しない
- APIキー、認証情報、秘密情報を公開リポジトリへ含めない
- 環境変数や非公開設定をソースコードから分離する
- 外部公開する情報を必要最小限にする
- Gitで変更履歴を管理し、AIによる変更差分を確認する
- 必要に応じてWinMergeなどで差分を視覚的に確認する
- テスト、実行結果、公式ドキュメントや信頼できる情報源を確認する
- 変更理由を理解できない状態では採用しない

生成速度だけを優先せず、正確性、安全性、保守性、再現性を確認したうえで、最終判断は人間が行う方針です。

---

## Engineering Experience

- AWS環境を利用したRPA・業務システム開発
- UiPathを使ったRPA開発
- VBAによるExcel業務の自動化・効率化
- VB.NET、C#による業務システム開発
- C++による医療機器関連システム開発
- Unity / C#を使ったVRアプリケーション開発
- Python、WordPress、AIエージェントを使った個人開発・Web運用

正確性、安全性、保守性が求められるシステム開発に携わってきました。

## Technologies

| 区分 | 技術・ツール |
| --- | --- |
| 現在扱っている技術 | Python、PHP、JavaScript、HTML、CSS、WordPress、Git、GitHub、Docker、Google Cloud、Cloudflare |
| 実務・開発経験のある技術 | AWS、UiPath、VBA、VB.NET、C#、C++、Unity |
| AI・エージェント | ChatGPT、ChatGPT Work、Claude、Claude Code、Gemini、Perplexity、Codex、Google Antigravity、Dify、MCP、Ollama、Gemma系モデル |
| 知識管理・リサーチ | Obsidian、NotebookLM |
| 開発・変更管理 | Visual Studio Code、SourceTree、WinMerge |
| 動画・デザイン | After Effects、Premiere Pro、Photoshop、Illustrator、Maya、Blender、Substance 3D、Stable Diffusion |

## Career Background

青山学院大学経営学部に在籍後、会計事務所および企業の財務・経理部門で勤務しました。

その後、Webデザインの学習をきっかけにPHPへ触れ、埼玉県内の職業訓練校でPHP、Java、ExcelなどのWeb・PCスキルを学習しました。

職業訓練修了後は、アクセンチュア株式会社にRPAエンジニアとして入社し、AWS環境を利用したRPA・業務システム開発に約2年間従事しました。

その後、株式会社リベラルセンスおよび株式会社スマートテクノロジーに在籍し、常駐先でC++を使った医療機器関連システムの開発に約半年従事しました。

VRプロフェッショナルアカデミーでは、Unity / C#を使ったVRアプリケーション開発を学び、作品出展も経験しました。

エンジニアリングに加えて、もともと興味のあったデザインや映像表現への理解を深めるため、デジタルハリウッドオンラインのMayaコースを8か月で修了しました。現在もStudio USやUdemyの教材を活用しながら、動画制作やAIを取り入れた制作フローについて継続的に学習しています。

---

## AI × Video Production

エンジニアリングだけでなく、動画制作やモーショングラフィックスにも継続して取り組んでいます。

Adobe製品については実務経験ではなく、学習と自主制作を通じて約2年間使用しています。

特にAfter Effectsを使ったモーショングラフィックス、アニメーション、映像合成を中心に制作しています。

### Video / Design Tools

- **After Effects**：モーショングラフィックス、アニメーション、映像合成
- **Premiere Pro**：動画編集、テロップ、音声調整、書き出し
- **Photoshop**：画像加工、合成、サムネイル制作
- **Illustrator**：ベクター画像、図形、映像素材の制作
- **Maya / Blender**：3DCGモデリング・映像表現
- **Substance 3D**：3Dテクスチャ制作
- **Stable Diffusion**：画像生成・制作支援

今後はAIエージェントやスクリプトをAfter EffectsやPremiere Proによる制作工程にも取り入れ、定型作業を効率化しながら、表現や品質調整により多くの時間を使える制作環境を目指しています。

## Portfolio

- Motion Graphics Portfolio — Coming Soon
- AI-assisted After Effects / Premiere Pro Workflow — Coming Soon

完成後は作品だけでなく、使用した技術、自動化した工程、人が判断・調整した工程なども紹介する予定です。

## 資格・認定

Web開発、業務自動化、3DCG・映像制作、生成AIなど、実務や個人制作に必要な領域を継続的に学習しています。

- 2025年11月　生成AIパスポート 取得
- 2021年12月　Unity 認定アソシエイト：ゲーム開発者 取得
- 2019年4月　VBAエキスパート Excel VBA スタンダード 取得
- 2018年1月　MOS：Microsoft Office Excel 2013 Specialist 取得
- 2018年1月　MOS：Microsoft Office Word 2013 Specialist 取得
- 2017年9月　PHP5技術者認定初級試験 取得
- 2016年9月　Webクリエイター能力認定試験（HTML5対応版）取得
- 1999年1月　実用英語技能検定 2級 取得

## 修了プログラム

- 2026年6月　Google AI Professional Certificate（Google Career Certificates／Coursera）修了
- 2025年5月　デジタルハリウッドオンライン Mayaコース（8か月）修了
- 2020年8月　VRプロフェッショナルアカデミー VRエキスパートコース 修了
- 2015年8月　社会福祉法人東京コロニー 職能開発室「HTML5で作るスマートフォンアプリ」修了

## 継続学習

- 2026年7月〜現在　G検定 学習中（2026年9月受験予定）
- 2025年3月〜現在　Studio US・Udemyの教材を活用し、動画制作を継続学習。制作時の復習・参照にも活用しながら、AIエージェントを取り入れた動画制作・自動化にも取り組んでいます
- 2024年10月〜現在　SHIFT AIで生成AI、AIエージェント、業務活用、セキュリティを継続学習

## Contact

- **Portfolio:** [monaka-studio.com/for-career/](https://monaka-studio.com/for-career/)
- **Website:** [monaka-studio.com](https://monaka-studio.com/)
- **Email:** [contact@monaka-studio.com](mailto:contact@monaka-studio.com)
