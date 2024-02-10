<script>
    import logo from '../assets/images/portix-logo.svg'
</script>

<nav class="absolute z-10 w-full border-b border-black/5 dark:border-white/5 lg:border-transparent">
    <div class="relative flex flex-wrap items-center justify-between gap-6 py-3 md:gap-0 md:py-4">
        <div class="relative z-20 flex w-full justify-between md:px-0 lg:w-max">
            <div class="relative z-20 flex w-full justify-between md:px-0 lg:w-max">
                <a href="/#home" aria-label="logo" class="flex items-center space-x-2">
                    <div aria-hidden="true" class="flex space-x-1">
                        <div class="h-4 w-4"></div>
                        <img class="h-4 w-4" src={logo} alt="Clean, fast, and modern portfolio website base">
                    </div>
                    <span class="text-2xl font-bold text-gray-900 dark:text-white">Portix.</span>
                </a>
            </div>
        </div>
    </div>
</nav>