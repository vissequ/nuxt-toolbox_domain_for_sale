<template>
  <main>
    <div class="intro">
      <h1>This Domain is for Sale</h1>
      <p>
        Hi 👋! This template gives you a
        <a href="https://nuxtjs.org/">Nuxt</a> app with the scaffolding for
        <a href="https://www.netlify.com/products/functions/"
          >Netlify Functions</a
        >, <a href="https://www.netlify.com/products/forms/">Forms</a>, and
        <a href="https://docs.netlify.com/routing/redirects/">Redirects</a>. Our
        aim was to give you the code you would need to hit the ground running
        with a few fun features.
      </p>
    </div>
    <FeedbackForm />
    <JokeBlock />
  </main>
</template>

<style>
* {
  font-family: 'Helvetica', sans-serif;
}
.intro {
  min-width: 400px;
  padding: 10px 40px;
  width: 60%;
}
</style>
