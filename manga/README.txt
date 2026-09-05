ルポマンガ用フォルダ
====================
ここに、掲載するルポマンガの画像を置いてください。

おすすめの構成：
  manga/ep01/cover.jpg   … 一覧に表示するサムネイル（縦長 3:4 推奨）
  manga/ep01/01.jpg      … 1ページ目
  manga/ep01/02.jpg      … 2ページ目
  ...

画像を置いたら、index.html 末尾の <script> 内 MANGA_REPORTS に
1話分を追記すると、「ルポマンガ」セクションに自動で並びます。

  const MANGA_REPORTS = [
    {
      title: "第一回営業 調査報告",
      date:  "2026.08.27",
      cover: "manga/ep01/cover.jpg",
      pages: ["manga/ep01/01.jpg", "manga/ep01/02.jpg", "manga/ep01/03.jpg"]
    },
  ];
