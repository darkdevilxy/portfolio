<nav class="navbar">
  <button class="home">Home</button>
  <button class="about"> About </button>
  <button class="projects">Projects</button>
  <button class="download_cv">Download CV</button>
  <button class="profile">Profile</button>
</nav>

<style lang="scss">
  .navbar {
    margin: 0px;
    padding: 0.5rem;
    display: flex;
    justify-content: center;
    gap: 5%;
    button {
      background-color: inherit;
      padding: 1rem;
      color: white;
      border: 1px solid rgb(0, 0, 0, 0);
      transition: all 0.2s ease-in;
      border-radius: 0.5rem;

      &:hover {
        border: 1px solid rgb(67, 76, 94, 1);
        background-color: rgb(67, 76, 94, 0.5);
      }
    }
  }
</style>
