<script lang="ts">
    //List of nav items
    const navItems = [
        {label: "Home", href:"#"},
        {label: "About", href:"#"},
        {label: "Projects", href:"#"},
        {label: "902Pharaoh", href:"#"}
    ]
    
</script>

<nav>
    <div class="content-center">
        <ul>
            {#each navItems as items}
            <li>
                <a href={items.href}>{items.label}</a>
            </li> 
            {/each}
        </ul>
    </div>
</nav>