<script>
    import logo from '../assets/images/portix-logo.svg'
</script>

<nav class="absolute z-10 w-full border-b border-black/5 dark:border-white/5 lg:border-transparent">
    <div class="relative flex items-center justify-between gap-6 py-3 md:gap-0 md:py-4">
        <div class="relative z-20 flex w-full justify-between md:px-0 lg:w-max">
            <a href="/#home" aria-label="logo" class="flex items-center space-x-2">
                <div aria-hidden="true" class="flex space-x-1">
                    <div class="h-4 w-4"></div>
                    <img class="h-4 w-4" src={logo} alt="Clean, fast, and modern portfolio website base">
                </div>
                <span class="text-2xl font-bold text-gray-900 dark:text-white">Portix.</span>
            </a>

            <div class="relative flex max-h-10 items-center lg:hidden">
                <button aria-label="hamburger" id="hamburger" class="relative -mr-6 p-6">
                    <div aria-hidden="true" id="line" class="m-auto h-0.5 w-5 rounded transition duration-300 bg-gray-300"></div>
                    <div aria-hidden="true" id="line2" class="m-auto mt-2 h-0.5 w-5 rounded transition duration-300 bg-gray-300"></div>
                </button>
            </div>
        </div>

        <div aria-hidden="true" class="fixed inset-0 z-10 h-screen w-screen origin-bottom scale-y-0 backdrop-blur-2xl transition duration-500 bg-gray-900/70 lg:hidden"></div>
        <div class="invisible absolute top-full right-0 z-20 w-full origin-top-right translate-y-1 scale-90 flex-col flex-wrap justify-end gap-6 rounded-3xl border border-gray-100 p-8 opacity-0 transition-all duration-300 bg-gray-800 lg:visible lg:relative lg:flex lg:w-7/12 lg:translate-y-0 lg:scale-100 lg:flex-row lg:items-center lg:gap-0 lg:border-none lg:bg-transparent lg:p-0 lg:opacity-100 lg:shadow-none">
            <div class="w-full text-gray-600 dark:text-gray-200 lg:w-auto lg:pr-4 lg:pt-0">
                <ul class="flex flex-col lg:flex-row gap-6 tracking-wide lg:gap-0 lg:text-sm justify-end"> <!-- Changed justify-end here -->
                    <li>
                        <a href="/projects" class="hover:text-primary block transition dark:hover:text-white md:px-4">
                            <span>Projects</span>
                        </a>
                    </li>
                    <li>
                        <a href="/about" class="hover:text-primary block transition dark:hover:text-white md:px-4">
                            <span>About</span>
                        </a>
                    </li>
                    <li>
                        <a href="/contact" class="hover:text-primary block transition dark:hover:text-white md:px-4">
                            <span>Contact</span>
                        </a>
                    </li>
                    <li>
                        <a href="/updates" class="flex gap-2 font-semibold text-gray-700 transition hover:text-primary dark:text-white dark:hover:text-white md:px-4">
                            <span>Updates</span>
                            <span class="flex rounded-full bg-primary/20 px-1.5 py-0.5 text-xs tracking-wider text-purple-700 dark:bg-white/10 dark:text-orange-300"> new</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</nav>
