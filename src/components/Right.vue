<template>
  <div class="right">
    <!--<div :class="item.type" v-for="(item,index) in data" :key="index">
      <p class="title">{{item.title}}</p>
      <div class="content" v-for="(key,index) in item.detail" :key="index">
        <p class="sec-title">{{key.name}}</p>
        <p class="link">
          <a :href="key.link"></a>
          <a :href="key.link"></a>
        </p>
        <p v-for="(detail,index) in key.text" :key="index">
          {{detail}}
        </p>
      </div>
    </div>-->
    <div class="project">
      <p class="title">个人项目</p>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>To-Do 日常事项记录应用</p>
        <p class="link">
          <span class="icon">&#xe67c;</span>
          <a target="_blank" href="https://github.com/Honohonoho/react-project-1">源代码</a>
          <a target="_blank" href="https://honohonoho.github.io/react-project-1/build/index.html">在线预览</a>
          <a target="_blank" href="http://www.jianshu.com/p/fb524b636f60">项目总结</a>
        </p>
        <p class="text"><span class="iconfont"></span><span>基于 <strong>React</strong> 框架和 JSX 语法，使用 <strong>react-create-app</strong> 工具快速构建应用,使用 <strong>ES6</strong> 语法，使用 <strong>webpack</strong> 打包各个资源和组件</span></p>   
        <p class="text"><span class="iconfont"></span><span>将登录、注册、重置密码、主页面、数据托管等功能抽离为单独的组件，提供了常见的<strong>表单验证</strong>功能</span></p>
        <p class="text"><span class="iconfont"></span><span>每个用户<strong>增删改查</strong>自己的待办事项，每一个待办都可以标记为已完成，每一个待办都能被删除</span></p>
        <p class="text"><span class="iconfont"></span><span>数据保存在第三方服务器 <strong>LeanCloud</strong> 中，刷新页面或登录之后，获取保存的待办事项</span></p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>电商网站PC端首页</p>
        <p class="link">
          <span class="icon">&#xe67c;</span>
          <a target="_blank" href="https://github.com/Honohonoho/MiStore-by-Vue">源代码</a>
          <a target="_blank" href="https://honohonoho.github.io/MiStore-by-Vue/dist/#/">在线预览</a>
          <a target="_blank" href="http://www.jianshu.com/p/7b82f9e72a84">项目总结</a>
        </p>
        <p class="text"><span class="iconfont"></span><span>基于 <strong>Vue2.0</strong> 框架，使用 <strong>vue-cli</strong> 工具快速构建的电商首页，使用 <strong>webpack</strong> 打包各个资源和组件</span></p>
        <p class="text"><span class="iconfont"></span><span>在开发中大胆尝试 <strong>ES6</strong> 新语法，使用 <strong>Babel</strong> 转换为ES5语法</span></p>
        <p class="text"><span class="iconfont"></span><span>使用 <strong>SCSS</strong> 来写CSS，页面布局使用 <strong>Flex</strong>（尽量不用Float），放弃对IE10以下的兼容</span></p>
        <p class="text"><span class="iconfont"></span><span>使用<strong>事件绑定，动态绑定class，v-show，v-if，transition </strong>完成所有的交互效果</span></p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>弹幕视频网站PC端首页</p>
        <p class="link">
          <span class="icon">&#xe67c;</span>
          <a target="_blank" href="https://github.com/Honohonoho/Bilibili-fake">源代码</a>
          <a target="_blank" href="https://honohonoho.github.io/Bilibili-fake/">在线预览</a>
          <a target="_blank" href="http://www.jianshu.com/p/5189e9da4155">项目总结</a>
        </p>
        <p class="text"><span class="iconfont"></span><span>使用 HTML(5) + CSS(3) + JQuery完成弹幕视频网站页面</span></p>
        <p class="text"><span class="iconfont"></span><span>使用 <strong>JQuery</strong> 完成交互效果，轮播，鼠标事件和导航切换，全局通用功能采用了<strong>构造函数模式和继承</strong>来封装，达到了可复用性</span></p>
        <p class="text"><span class="iconfont"></span><span>使用 <strong>ES6</strong> 的import和export语法导入各个模块，使用 <strong>webpack</strong> 打包各个资源和模块</span></p>
        <p class="text"><span class="iconfont"></span><span>所有图标整合到一张 Sprites 图上，减少图片的请求数，优化了性能</span></p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>游戏网站静态页面</p>
        <p class="link">
          <span class="icon">&#xe67c;</span>
          <a target="_blank" href="https://github.com/Honohonoho/wow-page">源代码</a>
          <a target="_blank" href="https://honohonoho.github.io/wow-page/index.html">在线预览</a>
        </p>
        <p class="text"><span class="iconfont"></span><span>使用 HTML 和 CSS 完成游戏类网站首页，采用単栏式布局</span></p>
        <p class="text"><span class="iconfont"></span><span>添加了若干 HTML5 语义化标签,合理使用了浮动和定位，页面清爽，代码简洁、规范</span></p>
      </div>
    </div>

    <div class="skill">
      <p class="title">技能清单</p>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>HTML / CSS</p>
        <p class="text"><span class="icon">&#xe71f;</span>可以编写语义化的 HTML(5)，能够使用 CSS(3) 实现较复杂布局与动画</p>   
        <p class="text"><span class="icon">&#xe71f;</span>对浏览器的工作原理、<strong>文档流、盒模型、BFC </strong>有自己的理解</p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>JavaScript / jQuery</p>
        <p class="text"><span class="icon">&#xe71f;</span>熟悉 Javascript 及相关&nbsp;<strong>DOM</strong>&nbsp;操作，了解&nbsp;<strong>ECMAScript 2015（ES6）</strong></p>
        <p class="text"><span class="icon">&#xe71f;</span>可以使用 jQuery 实现常见的<strong>轮播，导航切换，木桶布局，懒加载，跨域</strong>等功能<a target="_blank" href="https://honohonoho.github.io/demos/card/card.html">在线预览</a></p>
        <p class="text"><span class="icon">&#xe71f;</span>对<strong>原型链、作用域、闭包以及常见的设计模式</strong>有所理解，并有相应的实践</p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>Vue.js / React</p>
        <p class="text"><span class="icon">&#xe71f;</span>能够使用 React 或 Vue 框架开发简单 web 项目</p>   
        <p class="text"><span class="icon">&#xe71f;</span>对 React 的<strong>生命周期、props、state</strong>&nbsp;有一定了解</p>
        <p class="text"><span class="icon">&#xe71f;</span><span>对 Vue 的<strong>列表渲染，条件渲染，常见的事件绑定，模板语法，过渡效果，LifeCycle，基本的响应式原理</strong>有自己的理解</span></p>
      </div>
      <div class="content">
        <p class="sec-title"><span class="dot"></span>其他</p>
        <p class="text"><span class="icon">&#xe71f;</span>能够使用&nbsp;<strong>requirejs</strong>&nbsp;的r.js打包各个模块，各个组件模块采用 AMD 语法规范编写</p>   
        <p class="text"><span class="icon">&#xe71f;</span>能够基于&nbsp;<strong>Webpack</strong>&nbsp;构建前端工程化工作流</p>
        <p class="text"><span class="icon">&#xe71f;</span>能够使用&nbsp;<strong>MarkDown</strong>&nbsp;编写得体的文档，具备良好的技术交流能力</p>
        <p class="text"><span class="icon">&#xe71f;</span>了解 Linux 命令行的使用，使用&nbsp;<strong>Git</strong>&nbsp;来上传和管理代码</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data(){
    return{
      // data:[
      //   {
      //     type: 'project',
      //     title: '个人项目',
      //     detail: [
      //       {
      //         name: 'To-Do-日常事项记录应用',
      //         link:['',''],
      //         text: [
      //           '基于 React 框架和 JSX 语法，使用 react-create-app 工具快速构建应用,使用 ES6 语法，使用 webpack 打包各个资源和组件',
      //           '将登录、注册、重置密码、主页面、数据托管等功能抽离为单独的组件，提供了常见的表单验证功能',
      //           '每个用户增删改查自己的待办事项，每一个待办都可以标记为已完成，每一个待办都能被删除',
      //           '数据保存在第三方服务器 LeanCloud 中，刷新页面或登录之后，获取保存的待办事项',
      //         ]
      //       },
      //       {
      //         name: '电商网站PC端首页',
      //         link:['',''],
      //         text: [
      //           '基于 Vue2.0 框架，使用 vue-cli 工具快速构建的电商首页，使用 webpack 打包各个资源和组件',
      //           '在开发中大胆尝试 ES6 新语法，使用Babel转换为ES5语法',
      //           '使用 SCSS 来写CSS，页面布局使用Flex（尽量不用Float），放弃对IE10以下的兼容',
      //           '使用事件绑定，动态绑定class，v-show，v-if，transition完成所有的交互效果',
      //           '之后准备用 Store 统一管理数据和状态'
      //         ]
      //       },
      //       {
      //         name: '弹幕视频网站PC端首页',
      //         link:['',''],
      //         text: [
      //           '使用 HTML(5) + CSS(3) + JavaScript完成弹幕视频网站页面',
      //           '使用 Jquery 完成交互效果，轮播，鼠标事件和导航切换，全局通用功能采用了构造函数模式和继承来封装，达到了可复用性',
      //           '使用ES6的import和export语法导入各个模块，使用webpack打包各个资源和模块'
      //           ]
      //       },
      //       {
      //         name: '游戏网站静态页面',
      //         link:['',''],
      //         text: [
      //           '初次使用 HTML 和 CSS 完成游戏类网站首页，采用単栏式布局',
      //           '添加了若干 HTML5 语义化标签,合理使用了浮动和定位，页面清爽，代码简洁、规范'
      //         ]
      //       },
      //     ]
      //   },
      //   {
      //     type: 'skill',
      //     title: '技能清单',
      //     detail: [
      //       {
      //         name: 'HTML / CSS',
      //         text: [
      //           '可以编写语义化的 HTML(5)，能够使用 CSS(3) 完成常见的布局，实现较复杂布局与动画',
      //           '对浏览器的工作原理、文档流、盒模型、BFC 有自己的理解'
      //         ]
      //       },
      //       {
      //         name: 'JavaScript / jQuery',
      //         text: [
      //           '熟悉 Javascript 及相关 DOM 操作，熟悉 ECMAScript 2015（ES6）',
      //           '可以使用 jQuery 实现常见的轮播，导航切换，木桶布局，懒加载，跨域等功能',
      //           '对原型链、作用域、闭包以及常见的设计模式有所理解，并有相应的实践',
      //         ]
      //       },
      //       {
      //         name: 'Vue.js / React',
      //         text: [
      //           '能够使用 React 或 vue 开发简单 web 项目',
      //           '对 React 的生命周期、props、state有一定了解',
      //           '对 Vue 的列表渲染，条件渲染，常见的事件绑定，模板语法，过度效果，LifeCycle，基本的响应式原理有自己的理解'
      //         ]
      //       },
      //       {
      //         name: '其他',
      //         text: [
      //           '能够使用 requirejs 的r.js打包各个模块，各个组件模块采用 AMD 语法规范编写',
      //           '能够基于 Webpack 构建前端工程化工作流',
      //           '能够使用 MarkDown 编写得体的文档，具备良好的技术交流能力',
      //           '了解 Linux 命令行的使用，使用 Git 来上传和管理代码'
      //         ]
      //       },
      //     ]
      //   }
      // ]
    }
  }
}
</script>

<style lang="scss">
.right{
  width: 720px;
  padding-top: 30px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  .project,.skill{
    position: relative;
    margin-bottom: 10px;
    overflow: hidden;
    &:before{
      position: absolute;
      z-index: 2;
      content: '';
      width: 1px;
      background-color: #333;
      top: 50px;
      bottom: 0;
      left: 5px;
    }
    .title{
      font-size: 24px;
      letter-spacing: 1px;
      font-weight: 600;
      margin-right: 10px;
      padding-bottom: 5px;
      border-bottom: 1px solid #333;
    }
    .content{
      .sec-title{
        font-size: 18px;
        letter-spacing: 1px;
        font-weight: 600;
        padding: 5px 0;
        display: flex;
        align-items: center;
        .dot{
          height: 11px;
          width: 11px;
          margin-right: 5px;
          border-radius: 50%;
          background-color: #000;
        }
      }
      .link{
        padding-left: 20px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        >a{
          margin-left: 5px;
          padding: 1px 5px;
          border: 1px solid #333;
          border-radius: 6px;
        }
      }
      .text{
        padding-left: 20px;
        margin: 5px 0;
        display: flex;
        align-items: flex-start;
        justify-content: flex-start;
        strong{
          align-self: flex-end;
          line-height: 1.5;
        }
        .icon{
          margin-top: 4px;
          margin-right: 5px;
        }
        .iconfont{
          margin-top: 3px;
          content: '\e60a';
          margin-right: 5px;
        }
        a{
          font-size: 16px;
          margin-left: 5px;
          padding: 1px 5px;
          border-radius: 6px;
          border: 1px solid #333;
        }
      }
    }
  }
}
@font-face {
  font-family: 'iconfont';  /* project id 273742 */
  src: url('//at.alicdn.com/t/font_gq5r7ev6op28d7vi.eot');
  src: url('//at.alicdn.com/t/font_gq5r7ev6op28d7vi.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_gq5r7ev6op28d7vi.woff') format('woff'),
  url('//at.alicdn.com/t/font_gq5r7ev6op28d7vi.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_gq5r7ev6op28d7vi.svg#iconfont') format('svg');
}
.iconfont{
  font-family:"iconfont" !important;
  font-size:14px;font-style:normal;
  -webkit-font-smoothing: antialiased;
  -webkit-text-stroke-width: 0.2px;
  -moz-osx-font-smoothing: grayscale;
  &:before{
    content: '\e60a';
    margin-right: 5px;
  }
}
.icon{
  font-family:"iconfont" !important;
  font-size:16px;font-style:normal;
  -webkit-font-smoothing: antialiased;
  -webkit-text-stroke-width: 0.2px;
  -moz-osx-font-smoothing: grayscale;
}
</style>

