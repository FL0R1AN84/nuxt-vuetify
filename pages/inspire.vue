<template>
  <v-row justify="center" align="center">
    <v-col class="text-center" cols="12" sm="8" md="6">
      <v-card>
        <v-card-text class="text-center">
          <blockquote class="blockquote">
            &#8220;First, solve the problem. Then, write the code.&#8221;
            <footer>
              <small>
                <em>(╯°□°）╯︵ ┻━┻)</em>
                <br />
                <em>ᕕ( ᐛ )ᕗ</em>
              </small>
            </footer>
          </blockquote>
        </v-card-text>
        <v-card-actions>
          <v-btn color="primary" nuxt to="/">Return</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'InspirePage',
};
</script>
