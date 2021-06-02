<!-- <script setup lang="ts">
import { ref } from 'vue'
import { useRouter } from 'vue-router'
const router = useRouter()


const name = ref('')
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}

</script> -->

<template>
  <div class="index-page">
    <div class="site-detail">
      <header class="head">
        <h1 class="logo"></h1>
        <ul class="menu">
          <li>
            <a href="#">简历列表</a>
          </li>
          <li>
            <a href="#">使用帮助</a>
          </li>
        </ul>
      </header>

      <section class="detail-txt">
        <div class="inner">

        <h2>授人以鱼<br>不如授人以渔</h2>
        <p>授人以鱼不如授人以渔，说的是传授给人既有知识，不如传授给人学习知识的方法。道理其实很简单，鱼是做事目的，捕鱼是做事的手段，一条鱼能解一时之饥，却不能解长久之饥，如果想永远有鱼吃，那就要真正学会捕鱼的方法。</p>
        <span class="btn">
          开始制作简历
        </span>
        </div>
      </section>

      <div class="footer">
        &copy; copyright 2021 magic·cv
      </div>
    </div>
    <div class="view-box">
      <div class="tpl-view">

        <div class="box">
          <img src="../images/cvtpl.png">
        </div>

        <div class="point">
          <div class="p p1"></div>
          <div class="p p2"></div>
          <div class="p p3"></div>
        </div>
      </div>

    </div>
  </div>
</template>

<style>
main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
h1 {
  color: var(--prism-foreground);
}
</style>

<route lang="yaml">
meta:
  layout: home
</route>
