<page>
    <actionBar title="Home" />
    <stackLayout>
        <label class="info">
            <formattedString>
                <span class="fas" text="&#xf135;" />
                <span text=" {message}" />
            </formattedString>
        </label>
	<button on:tap={handleClick}>{count}</button>
    </stackLayout>
</page>

<script lang="ts">
    let message: string = "Blank Svelte Native App"
    let count = 0
    const handleClick = () => count++
</script>

