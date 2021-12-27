<script lang="ts">
    import Title from "./Title.svelte";
    import Figures from "./Figures.svelte";
</script>

<div id="left">
    <Title />
    <Figures />
</div>

<style>
    #left {
        width: 50%;
        padding: 50px;
    }
    @media screen and (max-width: 1440px) {
        #left {
            width: 100%;
            padding: 20px;
            background-color: rgb(26, 24, 49);
            border-bottom-left-radius: 15px;
            border-bottom-right-radius: 15px;
        }
    }
</style>
