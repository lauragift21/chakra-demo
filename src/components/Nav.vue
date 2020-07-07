<template>
  <c-flex mx="20" my="10" justify="space-between">
    <c-flex>
      <c-text fontWeight="bold">Quiz App</c-text>
    </c-flex>
    <c-flex>
      <c-text paddingRight="10">Menu 1</c-text>
      <c-text paddingRight="10">Menu 2</c-text>
      <c-text paddingRight="10">Menu 3</c-text>
      <c-text>Menu 4</c-text>
    </c-flex>
    <c-flex>
      <c-button variant="outline" color="gray.700" size="sm">Contact</c-button>
    </c-flex>
  </c-flex>
</template>

<script>
import { CFlex, CText, CButton } from "@chakra-ui/vue";

export default {
  components: {
    CFlex,
    CText,
    CButton
  }
};
</script>

<style>
</style>