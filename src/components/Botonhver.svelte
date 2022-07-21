<script>
    export let margin_y = false
</script>
<p class={`px-4 py-2 rounded-full mx-2
bg-slate-300 hover:text-white 
hover:bg-teal-600 capitalize font-bold
transition inline-block ${margin_y ? "my-2" : ""}
`}>
    <slot/>
</p>