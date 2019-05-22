<template>
  <div class="hello">
     <!-- <mt-button @click.native="handleClick">按钮</mt-button>
     <button>按钮</button> -->
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
        >
          Forum
        </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
        >
          Community Chat
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
        >
          Docs for This Template
        </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
        >
          awesome-vue
        </a>
      </li>
    </ul>
    <!-- <mt-button type="default">default</mt-button>
<mt-button type="primary">primary</mt-button>
<mt-button type="danger">danger</mt-button>
<mt-button icon="back">back</mt-button>
<mt-button icon="more">更多</mt-button> -->
<!-- <mybtn type="primary">2222</mybtn> -->
  </div>
</template>

<script>
//import { Indicator } from 'mint-ui';
//import { MessageBox } from 'mint-ui';
//import { Button } from 'mint-ui';
//import { Toast } from 'mint-ui';

export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
   methods: {
        handleClick: function() {
        //  Toast('提示信息');
       //   this.$toast('Hello world!')
        //  Indicator.open('加载中...');
        // MessageBox({
        //     title: '提示',
        //     message: '确定执行此操作?',
        //     showCancelButton: true,
        //   });
          // Toast({
          //     message: '操作成功',
          //     iconClass: 'icon icon-success',
          //     position:'top',
          //     duration:1000
          //   });
        }
      }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
