<script>
    import { featureTogglesStore } from "../feature-toggles/stores";
    export let name;
</script>

{#if $featureTogglesStore[name]}
    <slot />
{/if}
