<template>
  <article class="markdown-body">
    <h1>
      开始使用
    </h1>

    <p>请先<a href="#/doc/install">安装</a>本组件库。</p>
    <p>接着在你的项目中写入下面的代码</p>
    <pre><code>import {Button, Tab, Tabs, Switch, Dialog, openDialog} from "puzzle-ui"</code></pre>
    <pre><code>import "puzzle-ui/dist/lib/puzzle.css"</code></pre>
    就可以使用我提供的组件了。

    <h2>Vue 单文件组件</h2>
    <p>代码示例：</p>
    <pre><code>&lt;template&gt;
  &lt;div&gt;&lt;Button&gt;按钮&lt;/Button&gt;&lt;/div&gt;
&lt;/template&gt;

&lt;script&gt;
  import {Button} from "puzzle-ui"
  import "puzzle-ui/dist/lib/puzzle.css"

  export default {
    components: {Button}
  }
&lt;/script&gt;
 </code></pre>
  </article>
</template>
