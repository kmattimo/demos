<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <!-- <p>
      <a href="https://soundcloud.com/user-898803153" target="_blank" rel="noopener">soundcloud with everything</a>.
    </p> -->
    <h3>Songs</h3>
    
    <div>
      <iframe width="100%" height="500" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/playlists/1382535832&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/user-898803153" title="shoutkid" target="_blank" style="color: #cccccc; text-decoration: none;">shoutkid</a> · <a href="https://soundcloud.com/user-898803153/sets/demos" title="Demos" target="_blank" style="color: #cccccc; text-decoration: none;">Demos</a></div>
    </div>
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
  display: block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
