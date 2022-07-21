<template>
  <div>
    <section class="container">
      <article class="tile">
        <figure class="tile__figure">
          <img
            src="/img/one.jpg"
            data-hover="/img/2.jpg"
            class="tile__image"
            alt="My image"
            width="400"
            height="300"
          />
        </figure>
      </article>
    </section>

    <canvas id="stage"></canvas>
  </div>
</template>

<script>
import * as THREE from 'three'
import Scene from '../js/Scene'
// import Cursor from "~/js/cursor.js";
export default {
  // mixins: [Scene],
  mounted() {
    // const importedModule = await import('../js/Scene')
    // const Scene = importedModule.default
     new Scene()
  }
};
</script>

<style></style>
