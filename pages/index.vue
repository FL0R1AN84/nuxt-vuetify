<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <GammaGateLogo />
      </v-card>
      <v-card>
        <v-card-title class="headline d-flex justify-center"
          >ᕕ( ᐛ )ᕗ => GammaGate</v-card-title
        >
        <v-card-text class="text-center">
          <p>I'm Florian a passionate web developer from Germany</p>
        </v-card-text>
        <v-card-actions>
          <v-btn
            left
            color="secondary"
            href="https://github.com/FL0R1AN84"
            target="blank"
          >
            GitHub</v-btn
          >
          <v-spacer />
          <v-btn color="primary" nuxt to="/inspire">Continue</v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
import GammaGateLogo from '~/components/GammaGateLogo.vue';
export default {
  name: 'IndexPage',
  components: { GammaGateLogo },
};
</script>
