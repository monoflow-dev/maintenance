<template>
    <g-link class="button" href="/">Say hello</g-link>
</template>

<script>
export default {
  name: 'Button',
}
</script>

<style>
    .button {
        box-sizing: border-box;
        display: block;
        padding: 7px 24px 5px;
        font-family: 'Poppins', sans-serif;
        font-size: 16px;
        font-weight: 500;
        text-decoration: none;
        border: 2px solid #0055FF;
        border-radius: 20px;
        color: #0055FF;
        transition: all 300ms ease-in-out;
    }

    .button:hover {
      background-color: #0055FF;
      color: white;
    }
</style>