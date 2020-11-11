<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        DevOps Hello World
      </h1>
      <div class="links">
        <div class="flex">
          <a
            href="https://sysvale.com/"
            target="_blank"
            rel="noopener noreferrer"
            class="button--sysvale flex-1 mr-20px"
          >
            <span class="margin-auto">Sysvale</span>
          </a>
          <a
            href="http://lpi.org/"
            target="_blank"
            rel="noopener noreferrer"
            class="button--lpi flex-1"
          >
            <span class="margin-auto">LPI</span>
          </a>
        </div>

        <div
          id="presentation-button-container"
          class="flex"
        >
          <a
            href="https://docs.google.com/presentation/d/e/2PACX-1vSvdgkP2WanhwAowNnA89ElvxQ21F0FjIoSehhiYKVFjCKR-aj5lXUsOKt2Gikysg5rehAXKt08wEet/pub?start=false&loop=false&delayms=3000&slide=id.p"
            target="_blank"
            rel="noopener noreferrer"
            class="button--grey flex-1 ml-0"
          >
            <span class="margin-auto">Link Para a Apresentação</span>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
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
  width: 60%;
  margin: auto;
}

.flex {
  display: flex;
}

.flex-1 {
  display: flex;
  flex-grow: 1;
}

.margin-auto {
  margin: auto;
}

.ml-0 {
  margin-left: 0;
}

#presentation-button-container {
  margin-top: 20px;
}
</style>
