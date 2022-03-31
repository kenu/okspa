<template>
  <div>
    <img alt="React + API Server 개발과 배포" src="./assets/inflearn-react-api.png" />
    <p>
      <a
        href="https://www.inflearn.com/course/%EB%A6%AC%EC%95%A1%ED%8A%B8-api-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8"
        target="blank"
      >React + API Server 프로젝트 개발과 배포</a>
    </p>
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
