<template>
  <div id="app">
    background
  </div>
</template>

<script>
export default {
  created () {
    console.log('created')
    console.log(chrome)
    console.log(chrome.cookies.getAll({
      url: 'https://chat.sangfor.com/'
    }, (cookies) => {
      console.log(cookies)
    }))
  }
}
</script>
