<template>
  <c-box>
    <c-text fontSize="5xl" textAlign="center" fontWeight="bold">Question 2</c-text>
    <c-text fontSize="xl" textAlign="center">What is your level of experience?</c-text>
    <c-flex my="12" justify="center">
      <c-flex flexDirection="column" bg="indigo.200" mx="4" p="10" w="sm" rounded="lg" align="center">
        <img src="../assets/circle.png" alt="circle icon" width="100">
        <c-text mt="6" textAlign="center" color="white" fontSize="xl">Beginner</c-text>
      </c-flex>
      <c-flex flexDirection="column" borderWidth="1px" mx="4" p="10" w="sm" rounded="lg" align="center">
        <img src="../assets/circle.png" alt="circle icon" width="100">
        <c-text mt="6" textAlign="center" fontSize="xl">Experienced</c-text>
      </c-flex>
      <c-flex flexDirection="column" borderWidth="1px" mx="4" p="10" w="sm" rounded="lg" align="center">
        <img src="../assets/circle.png" alt="circle icon" width="100">
        <c-text mt="6" textAlign="center" fontSize="xl">Professional</c-text>
      </c-flex>
    </c-flex>
    <c-flex justify="center">
      <c-button variant-color="indigo" bg="indigo.200" w="250px">Next</c-button>
    </c-flex>
    <c-box mx="auto" my="10" w="lg" >
      <c-progress 
      :value="60" 
      height="40px" 
      rounded="40px"
      hasStripe 
      isAnimated
      v-chakra="{
        'div': {
          bg: 'indigo.200'
        }
      }"
      />
      <c-flex justify="space-between" my="3" mx="4">
        <c-text color="gray.700" fontSize="sm">Step 2 Out of 5</c-text>
        <c-text color="gray.700" fontSize="sm">60%</c-text>
      </c-flex>
    </c-box>
  </c-box>
</template>

<script>
import { CBox, CText, CFlex, CButton, CProgress } from '@chakra-ui/vue'

export default {
  components: {
    CBox,
    CText,
    CFlex,  
    CButton,
    CProgress
  }
}
</script>

