<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      안녕하세요, 저는 🍪 개발자입니다.
      <a href="https://velog.io/@oneook" target="_blank" rel="noopener">velog.io/@oneook</a>.
    </p>
    <h3>CI CD 테스트용 프로젝트</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>기술 스택</h3>
    <ul>
      <li>JavaScript</li>
      <li>Vue.JS</li>
      <li>React.JS</li>
      <li>Node.JS</li>
      <li>Express.JS</li>
      <li>Prisma</li>
      <li>MySQL</li>
      <li>AWS CloudFront</li>
      <li>AWS S3</li>
      <li>AWS CloudFormation</li>
      <li>AWS Lambda</li>
      <li>Serverless Framework</li>
    </ul>
    <h3>원국이의 앱</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #2074e6;
}
</style>
