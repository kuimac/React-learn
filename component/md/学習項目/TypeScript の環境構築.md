# vite を利用した React アプリケーションの構築

## vite でプロジェクトを作成する

[最初の Vite プロジェクトを生成する](https://ja.vitejs.dev/guide/#%E6%9C%80%E5%88%9D%E3%81%AE-vite-%E3%83%95%E3%82%9A%E3%83%AD%E3%82%B7%E3%82%99%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92%E7%94%9F%E6%88%90%E3%81%99%E3%82%8B)

`npm create vite@latest`

構築内容

```
Project name: … react-learn-app
✔ Target directory "react-learn-app" is not empty. Remove existing files and continue? … yes
✔ Select a framework: › React
✔ Select a variant: › TypeScript
```

```
cd react-learn-app
npm install
npm run dev
```

## GitHub に push する

GitHub で任意のリポジトリを作成し、ローカルリポジトリと紐付ける

```
git init
git remote add origin "作成したリモートリポジトリ"
git branch -M main
git add .
git commit -m "first commit"
git push -u origin main
```
