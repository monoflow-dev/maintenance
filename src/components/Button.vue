<template>
    <g-link class="button" href="/">Say hello</g-link>
</template>

<script>
export default {
  name: 'Button',
}
</script>

<style lang="scss" scoped>
    .button {
        position: relative;
        box-sizing: border-box;
        display: block;
        padding: 7px 24px 5px;
        font-family: 'Poppins', sans-serif;
        font-size: 16px;
        font-weight: 500;
        text-decoration: none;
        border: 2px solid #0055FF;
        border-radius: 4px;
        color: #0055FF;
        transition: all 300ms ease-in-out;

        &:before {
            content: '';
            position: absolute;
            width: 0%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: -1;
            background: #0055FF;
            transition: all 300ms ease-in-out;
            border-radius: 2px;
        }

        &:hover {
            color: white;
        }

        &:hover:before {
            width: 100%;
        }
    }
</style>