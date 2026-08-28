# policy

Azukichi の Android アプリのプライバシーポリシーを GitHub Pages で公開するためのリポジトリ。
**アプリ本体のコードは含まない。**

| アプリ | アプリID | ページ | 正本 |
|---|---|---|---|
| おてつだいカレンダー ツダツダ | `com.kyomosodatsu.app` | https://azu-kichi.github.io/policy/ | [index.md](index.md) |
| 計算 ケタギア | `com.azukichi.flash_calc` | https://azu-kichi.github.io/policy/flash-calc/ | [flash-calc/index.md](flash-calc/index.md) |

- **文面はアプリの実装と一致していなければならない** — データの扱いが変わる機能を入れたら、
  そのアプリのページを同じタイミングで更新し、制定日・更新日を書き換えること
- 文面の根拠（一次情報・確認日つき）は各アプリ側リポジトリにある
  （ツダツダ: `docs/PLAY_LAUNCH.md` §4 / ケタギア: `docs/SPEC.md` §10.1・§15・§16）
- 新しいアプリを足すときは `<app>/index.md` を作り、この表と各ページ末尾の相互リンクに 1 行足す
