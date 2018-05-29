<template>
  <div id="MainFight">
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Monsoter Hero
          </h1>
          <h2 class="subtitle">
            Vue.js
          </h2>
        </div>
      </div>
    </section>
    <section class="section">
      <nav class="level">
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Me</p>
            <p class="title">3,456</p>
          </div>
        </div>
        <div class="level-item has-text-centered">
          <div>
            <p class="heading">Monster</p>
            <p class="title">123</p>
          </div>
        </div>
      </nav>
      <nav class="columns">
        <div class="column">
          <progress class="progress is-danger" value="90" max="100">90%</progress>
        </div>
        <div class="column">
          <progress class="progress is-danger" value="90" max="100">90%</progress>
        </div>
      </nav>
    </section>
    <section class="section">
      <div class="container">
        <div class="columns">
          <div class="column is-three-fifths is-offset-one-fifth has-text-centered">
            <div class="box has-text-centered">
              <nav class="level">
                <p class="level-item has-text-centered">
                  <a id="start-game" class="button is-focused is-danger is-large">Start Game</a>
                </p>
              </nav>
            </div>
          </div>
        </div>
        <div class="columns">
          <div class="column is-three-fifths is-offset-one-fifth has-text-centered">
            <div class="box has-text-centered">
              <nav class="level">
                <p class="level-item has-text-centered">
                  <a id="attack" class="button is-focused is-danger">Attack</a>
                </p>
                <p class="level-item has-text-centered">
                  <a id="heal" class="button is-focused is-primary">Heal</a>
                </p>
                <p class="level-item has-text-centered">
                  <a id="special-attack" class="button is-focused is-danger is-large">Special Attack</a>
                </p>
                <p class="level-item has-text-centered">
                  <a id="defende" class="button is-focused is-info">Defende</a>
                </p>
                <p class="level-item has-text-centered">
                  <a id="give-up" class="button is-focused is-light">Give Up</a>
                </p>
              </nav>
            </div>
          </div>
        </div>
        <div class="box">
          <ul>
            <li>test</li>
            <li>resr</li>
            <li>rsr</li>
          </ul>
        </div>
      </div>

    </section>
  </div>
</template>

<script>
  export default {
    name: 'MainFight'
  }
</script>