**This repository is vue tutorial learning how to make vue-component.**
# vue-tutorial-component

## How to use Vue Component?
### Step 1
1. Create vue project
```bash
$ vue create [please write your project name]
```
It will be displayed as `Please pick a preset: (Use arrow keys)`. 

Please select the `default (babel, eslint)` in this case.

2. Compiles and hot-reloads for development
```
$ yarn serve
```
上記のコマンドを実行するとVue Projectが実行されます。Vueのデフォルトポートである`localhost:8080`にアクセスして、Welcome to Your Vue.js App と描画されていることを確認してください。
![デフォルトページ](https://github.com/kooooichi24/vue-tutorial-component/blob/photo/1.png)

### Step 2
1. Hello world

/src/App.vue　を開き、templateタグの中のHelloWorldタグのmsgプロパティの値を"Hello World"と変更してください。

終わりです。

ブラウザで、`Welcome to Your Vue.js App`と記載されていた箇所が`Hello world`と変わっていることを確認してください。

![デフォルトページ](https://github.com/kooooichi24/vue-tutorial-component/blob/photo/2.png)




## Project setup
1. Clone this repository
```bash
$ git clone https://github.com/kooooichi24/vue-tutorial-component.git
```

2. Go into the repository
```bash
$ cd vue-tutorial-component
```

3. Install packages
```
$ yarn install
```

4. Compiles and hot-reloads for development
```
$ yarn serve
```

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © Koichi Furukawa