[Share.js](http://overtrue.me/share.js/)
===
# 安装

有3种安装方式：

1. 使用 [npm](https://npmjs.com)

    ```shell
    npm install social-share.js
    ```
2. 使用 [bower](https://bower.io)

    ```shell
    bower install social-share.js
    ```

3. 使用 [cdnjs](https://cdnjs.com/libraries/social-share.js)，引入 `share.min.css` 与 `social-share.min.js` 两个链接就好。 (感谢 [@mdluo](https://github.com/mdluo))

4. 手动下载或者 git clone 本项目。

```html

```
### HEAD：当前 commit 的引用
总之，当前 commit 在哪里，`HEAD` 就在哪里，这是一个`永远`自动指向当前 commit 的引用，所以你永远可以用 `HEAD` 来操作当前 commit。
当前 commit这个概念很简单，它指的就是当前工作目录所对应的 commit。
### branch

Git 还有一种引用，叫做 branch（分支）
HEAD 除了可以指向 commit，还可以指向一个 branch，当它指向某个 branch 的时候，会通过这个 branch 来间接地指向某个 commit；另外，当 HEAD 在提交时自动向前移动的时候，它会像一个拖钩一样带着它所指向的 branch 一起移动。

`master 就是一个 branch 的名字`

上面的那张图里，HEAD -> master 中的 master 就是一个 branch 的名字，而它左边的箭头 -> 表示 HEAD 正指向它（当然，也会间接地指向它所指向的 commit）。
