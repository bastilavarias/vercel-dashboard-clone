<template>
  <svg
    viewBox="0 0 1155 1000"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
    :class="className"
  >
    <path d="M577.344 0L1154.69 1000H0L577.344 0Z" fill="black" />
  </svg>
</template>

<script>
export default {
  name: "VercelLogo",

  props: {
    className: {
      type: String,
      required: false,
    },
  },
};
</script>
