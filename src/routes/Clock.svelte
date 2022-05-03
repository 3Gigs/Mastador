<script lang="ts">
    import {Clock} from "../etc/Clock"
    export const formatter = new Intl.DateTimeFormat("en", {
        hour12: true,
        hour: "numeric",
        minute: "2-digit",
        second: "2-digit",
    })
</script>

<h3>{formatter.format($Clock)}</h3>
