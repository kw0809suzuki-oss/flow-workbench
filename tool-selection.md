# Tool selection

薄いルーティング層。  
最終再観測: 2026-09-21

## まず3段だけ見る

1. **Native Tool で足りるか**
2. **外部の状態が必要なら、接続済み Plugin に行く**
3. **足りない外部能力だけ Plugin 探索する**

## 現在の主なルート

### 現在の外部情報・調査
- **Web search**
- 以前の「Web / Deep Research」固定ではなく、まず現在の Web を使う。
- 複数の外部作業面をまたぐ大きな仕事は、利用できる作業面側に寄せる。ここでは独自の調査 OS を作らない。

### ファイル / Docs / Sheets / Slides
- **Google Drive**
- Drive を入口に Docs / Sheets / Slides を扱う。
- 単発の成果物を作るだけなら Native の document / spreadsheet / presentation / PDF 系を先に使ってよい。

### コード / Repository / PR / Issue / CI
- **GitHub**
- コードを書く場所そのものというより、repository の状態を読み、変更を反映する外部作業面として使う。

### アプリ
- **Floot / Lovable**
- 既存プロジェクトがある側を優先する。
- Floot はプロジェクト内のコード・リソース・実行環境を直接扱う作業台として使える。
- Lovable は自然言語から full-stack web app を作成・編集し、preview / publish まで進める作業面。
- 「アプリ = Lovable」と固定しない。

### DB / Backend
- **Supabase**
- PostgreSQL、schema、migration、Auth、Edge Functions、logs など、Supabase プロジェクト自体を扱う時に使う。

### 構造化された業務データ
- **Airtable**
- 「大量の同型データ」だけではなく、base / table / record を持つ運用データの読み書き・分析に使う。

### Knowledge / Wiki / Planning
- **Notion**
- 「長文保存」だけではなく、knowledge capture、research synthesis、meeting / implementation planning など、Notion を作業面にする時に使う。

### 画像 / Design / Media
- **Native image generation/editing**: 単体画像の生成・編集
- **Canva**: design の作成・編集・review・brand check・bulk / resize など、デザイン作業面が必要な時
- **Runway**: video / audio を含む media generation・editing・workflow が必要な時

### 定期実行 / 条件監視
- **Native automations**
- リマインド、定期サマリー、条件成立時の通知など。

### 能力不足 / 外部サービスが必要
- **Plugin Management**
- まず既存の Native Tool / 接続済み Plugin で足りないか確認する。
- 足りない時だけ Plugin を検索する。
- 未接続サービスを「使える前提」でルート表に固定しない。

## 迷った時

**成果物や状態がすでに存在する場所へ行く。**  
場所がまだないなら、最小の Native Tool から始める。  
それでも足りなければ Plugin を増やす。
