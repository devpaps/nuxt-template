<template>
  <section class="section is-medium">
    <div class="container has-text-centered">
      <h1 class="title">Contact Me</h1>
      <p>Do you like what you see?</p>
      <form name="contact" method="POST" netlify>
      <p>
        <label>Your Name: <input type="text" name="name"></label>
      </p>
      <p>
        <label>Your Email: <input type="email" name="email"></label>
      </p>
      <p>
        <label>Message: <textarea name="message"></textarea></label>
      </p>
      <p>
        <button type="submit">Send</button>
      </p>
    </form>

    </div>
  </section>
</template>