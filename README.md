# 松本城さんぽ

松本城と城下町（縄手通り・中町通り）をスマホで歩いて巡れる3D散策アプリの試作品。three.js製の単一HTMLです。

公開URL: https://32miya.github.io/matsumoto-castle/

## お城さんぽシリーズ共通
- 人物・旗・襖絵・床板・石垣などの素材は、シリーズ共通の `https://32miya.github.io/oshiro/common/assets/` から読み込みます（このリポジトリに同じ画像を置かない）。一覧と使い方は `32miya/32miya.github.io` の `oshiro/common/README.md`。
- 天守の窓は本当の開口にして、各階の中から外の景色が見えるようにする（シリーズ共通の作り）。
- index.html の末尾の `oshiro-portal:begin`〜`end` は「お城選びへ戻る」ボタンなので消さない。
