<template>
  <section class="container">
    <div>
      <app-logo />
      <router-link to="/">back</router-link>
      <h1 class="title">ssr_nuxt</h1>
      <h2 class="subtitle">Nuxt.js project</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto aliquid voluptatem iure consequuntur praesentium impedit, quisquam velit eum corrupti quasi nulla commodi dicta error eos dolor possimus officiis eligendi facere?</p>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Excepturi, quia aut? Reprehenderit adipisci, vel, aliquid nihil id repudiandae magnam praesentium consectetur sequi saepe laboriosam magni in repellat vero porro quaerat?</p>
      <p>Ratione ipsa laboriosam repellendus temporibus qui aut praesentium voluptate repudiandae amet blanditiis sit, quas est placeat! Voluptatem aspernatur cumque adipisci nisi sapiente, veritatis amet aliquid. Tempore aspernatur at quae odio.</p>
      <p>Facere commodi sed aliquid, sequi nemo, consectetur optio asperiores, quisquam nostrum ipsum iure ducimus veniam laborum id. Delectus unde ab ad quae, sed fugiat alias animi eveniet. Quos, esse quod.</p>
      <p>Enim earum fuga laboriosam facilis sequi consequatur nihil, inventore, eligendi, impedit aperiam dolore ducimus. Voluptates neque magnam ea voluptatibus nemo itaque officia expedita numquam soluta dignissimos. Ratione voluptates necessitatibus atque?</p>
      <p>Dignissimos voluptatem labore autem cupiditate, dolore quasi esse sapiente quam odit quaerat ipsum nemo nam dolores magnam illum tempore dicta ad tempora ea! Iusto illo voluptas, adipisci placeat ea laborum?</p>
    </div>
  </section>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";

export default {
  components: {
    AppLogo
  }
};
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
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

