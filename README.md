#
Next.jsにElectronのモジュールを追加してElectronデスクトップアプリを実装できるかのプロジェクト(nextronを使用しない)

## Getting Started

以下でビルドツールを含むElectronのWindow表示:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

##  build

以下のコマンドでビルドが実行される。
ビルド完了後にプロジェクト上にdistディレクトリが作成される。このディレクトリ内部にexeファイルがあるため起動するとElectronのデスクトップアプリケーションが起動されるがnext.jsの内容が表示されないため修正方法確認中

```bash
npm run build
# or
yarn build
# or
pnpm build
# or
bun dev
```


##  reference

- [Building Desktop Apps with Electron + Next.JS (without Nextron)](https://rbfraphael.medium.com/building-desktop-apps-with-electron-next-js-without-nextron-01bbf1fdd72e)
- [Next.JSのElectronデスクトップアプリを作る（Nextronを使わず）](https://qiita.com/HFMS/items/c3ce811dfb24b16ecb7e)