<script>
    import '../app.pcss';
</script>

<nav class="bg-gray-800 p-4 text-white">
    <div class="container mx-auto flex items-center justify-between">
        <a href="/" class="text-lg font-semibold">Kyth</a>
        <!-- This spacer div takes up the same amount of space as the Brand link to balance the centering of the menu items -->
        <div class="flex-grow">
            <div class="flex justify-center space-x-4">
                <a href="/about" class="hover:text-gray-300">About</a>
                <a href="/services" class="hover:text-gray-300">Services</a>
                <a href="/contact" class="hover:text-gray-300">Contact</a>
            </div>
        </div>
        <div class="invisible text-lg font-semibold">Kyth</div> <!-- Invisible spacer -->
    </div>
</nav>
<slot />