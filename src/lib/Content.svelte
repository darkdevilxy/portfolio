<script lang="ts">
</script>

<main>
  <div class="grid_template">
    <div class="image_container">
      <img src="innovative_mind.png" alt="Innovative Mind" />
    </div>
    <div class="text_container">
      <p class="description">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Esse
        necessitatibus inventore quasi, dolor suscipit temporibus vero cumque
        modi velit pariatur ipsum dolorem voluptate excepturi doloribus. Nisi
        molestiae ab dolor rem?
      </p>
    </div>
  </div>
</main>

<style lang="scss">
  main {
    max-width: 100%;
    padding: 0;
    margin-top: 5rem;
    display: flex;
    justify-content: center;
    .grid_template {
      display: grid;
      grid-template-columns: 1fr 1fr;
      max-width: 50rem;
      gap: 1rem;

      .image_container {
        overflow: hidden;
        margin: 0;
        img {
          width: 100%;
          height: 100%;
          object-fit: contain;
        }
      }

      .text_container {

        .description {
          font-size: 1.5rem;
          line-height: 2.5rem;
          font-weight: 300;
          padding: 0rem 2rem 0 2rem;
          color: rgb(187, 175, 175);
        }
      }
    }
  }
</style>
