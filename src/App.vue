<template>
  <c-theme-provider>
    <c-reset />
    <!--Your application goes here -->
    <Nav />
    <Main /> 
  </c-theme-provider>
</template>

<script>
import { CThemeProvider, CReset } from "@chakra-ui/vue";
import Nav from './components/Nav'
import Main from './components/Main'

export default {
  name: "App",
  components: {
    CThemeProvider,
    CReset,
    Nav,
    Main
  }
};
</script>
