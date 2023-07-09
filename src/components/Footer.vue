<template>
    <div id="footer">© Hakim Murphy {{ year }}</div>
</template>

<script>
    export default{
        name: "Footer",
        data() {
            const year = new Date().getFullYear();
            return {
                year: year
            }
        }
}
</script>

<style>
    #footer {
        width: 100%;
        height: 1.5rem;
        background-color: #D21312;
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: .7rem;
        color: #070A52;
    }
</style>