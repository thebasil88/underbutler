<script lang="ts">
    /*
        Button options: https://daisyui.com/components/button/
    */
    export let btnType: string = "";
</script>
<button class="btn {btnType}"><slot /></button>
