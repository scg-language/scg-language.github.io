# scg-language.github.io（アプリの表紙）

`https://apps.scg-language.com/` の表紙。アプリへのリンクを並べた1枚だけ。

- **なぜあるか**：独自ドメイン `apps.scg-language.com` を、この組織の公開先ぜんぶに効かせるため。
  このリポ（組織の名前と同じ名前のリポ）に独自ドメインを付けると、ほかのリポの公開先も
  `https://apps.scg-language.com/<リポの名前>/` で開けるようになる（2026-11-24・B 案）。
- **学生ポータル**：`https://apps.scg-language.com/scg-student-portal/`（リポ `scg-language/scg-student-portal`）
- **アプリを足すとき**：`index.html` にリンクを1つ足す。
- 🔴 `CNAME` を消さない・書き換えない（独自ドメインが外れて、学生に配った URL が開けなくなる）。
- 🔴 public。学生の情報・パスワード・教材の中身を置かない。
- DNS は、学校のドメインを管理している担当者の設定（`apps` → `scg-language.github.io`）。
