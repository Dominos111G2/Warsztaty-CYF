<template>
  <section class="about">
    <h2>About You</h2>
    <div class="about-content">
      <p>{{ aboutText }}</p>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutUs',
  data() {
    return {
      aboutText: 'I am a high school student at a technical school, passionate about programming and developing my skills in this field. In my free time, I enjoy listening to music and playing the drums, which is one of my greatest passions.'
    };
  }
}
</script>

<style scoped>
.about {
  padding: 35px 20px;
  background: #1c1c1e;
  color: #ffffff;
  max-width: 1200px;
  width: 100%;
  border-radius: 8px;
}
.about h2 {
  margin-left: 10px;
}
.about-content {
  margin: 10px;
  padding: 20px;
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid #ec5252;
  border-radius: 8px;
}
</style>