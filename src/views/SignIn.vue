<template>
  <div class="signin">
      <header>
          <img src="http://theridgewoodblog.net/wp-content/uploads/2014/10/vote.jpg">
      <h1>Galvanize Votes</h1>
      </header>
      <main>
          <p>The future home of Galvanzie Votes</p>
      </main>
  </div>
</template>

<script>
    // @ is an alias to /src
    //    import HelloWorld from "@/components/HelloWorld.vue"

export default {
    name: "signIn",
    components: {
    }
}
</script>
<style scoped lang="scss">
    @import "~@/styles/colors";
    @import "~@/styles/typography";
    .sign-in {
        @include base-font;
        header {
            margin: 2rem 0;
            text-align: center;
            h1 {
                @include primary-header-font;
                text-align: center;
            }
            img {
                max-width: 320px;
                margin-bottom: 2rem;
            }
        }
        main {
            p {
                text-align: center;
            }
        }
    }
</style>