# Fcoinのトリセツ

FCoinの日本語取扱説明書（トリセツ）をつくる個人的プロジェクトです。  
今のところ、広告などをつけるつもりはなく、サイトからの収益は考えていません。

## ローカルでの実行

Macを想定しています。

### 初期設定

以下のコマンドを叩いてください。

~~~
$ brew install rbenv ruby-build
$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
$ source ~/.bash_profile
$ rbenv install 2.6.0
$ rbenv global 2.6.0
$ gem install bundler
$ bundle install --path vendor/bundle
~~~

### 起動

下記コマンドを叩くと起動します。  
トップページは http://localhost:4000/ になります。
~~~
$ bundle exec jekyll s -s docs
~~~


---

以降、デフォルトのreadme
TODO 一応残しておくが消去予定

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Odacchi/fcoin-user-manual-jp/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Odacchi/fcoin-user-manual-jp/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
