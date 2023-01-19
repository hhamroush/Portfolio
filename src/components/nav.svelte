<script lang="ts">
    //List of nav items
    const navItems = [
        {label: "Home", href:"#"},
        {label: "About", href:"#"},
        {label: "Projects", href:"#"},
        {label: "902Pharaoh", href:"#"}
    ]
    
</script>

<div class="pointer-events-auto hidden md:block">
    <nav class="w-fit mx-auto my-4 rounded-full flex items-center justify-center flex-row">
        <div>
            <ul class="flex rounded-full bg-white/90 px-4 text-sm font-medium dark:bg-zinc-800/90 dark:text-zinc-200">
                {#each navItems as items}
                    <li class="relative block px-3 py-2">
                        <a href={items.href}>{items.label}</a>
                    </li> 
                {/each}
            </ul>
        </div>
    </nav>
</div>