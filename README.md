# vue-tutorial-hello-world

## ゴール：Hello World ができるようになる
### Step 1
1. まずはVueプロジェクトを作成する
```bash
$ vue create [please write your project name]
```
`Please pick a preset: (Use arrow keys)`と表示されると思います。 

今回は、`default (babel, eslint)`を選択してください。

2. 実行
```
$ yarn serve
```
上記のコマンドを実行するとVue Projectが実行されます。Vueのデフォルトポートである`localhost:8080`にアクセスして、Welcome to Your Vue.js App と描画されていることを確認してください。
![デフォルトページ](https://github.com/kooooichi24/vue-tutorial-hello-world/blob/photo/1.png)

### Step 2
1. Hello world

/src/App.vue　を開き、templateタグの中のHelloWorldタグのmsgプロパティの値を"Hello World"と変更してください。

終わりです。

ブラウザで、`Welcome to Your Vue.js App`と記載されていた箇所が`Hello world`と変わっていることを確認してください。

![デフォルトページ](https://github.com/kooooichi24/vue-tutorial-hello-world/blob/photo/2.png)


## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © Koichi Furukawa