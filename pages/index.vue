<template>
  <div class="container">
    <div>
      ゆず〜
      <ul>
        <li><a href="https://twitter.com/makudona_poteko">@makudona_poteko</a></li>
        <li><a href="https://note.com/yuzukomemo/n/n2edbf5a98d6c">ゆずもめも（noteホーム）</a></li>
        <li><a href="https://note.com/yuzukomemo/n/n7020e7d594a0">ゆずこの録音環境</a></li>
        <li><a href="https://note.com/yuzukomemo/n/n07d8ff90a220">ゆずこの音域</a></li>
        <li><a href="https://twitter.com/search?q=from%3Amakudona_poteko%20%E3%82%86%E3%81%9A%E3%81%93%E3%83%A9%E3%83%B3%E3%83%81&src=typed_query&f=image">ゆずこランチ</a></li>
        <li><a href="https://twitter.com/search?q=from%3Amakudona_poteko%20%E9%9F%B3%E6%A5%BD%E6%B4%BB%E5%8B%95&src=typed_query&f=image">音楽活動</a></li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      x: 0,
      y: 2,
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
