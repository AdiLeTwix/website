<script>
    import { base } from '$app/paths';
</script>

<header class="bg-gray-800 text-gray-100">
    <nav class="flex items-center justify-center p-5">
        <div class="flex items-center space-x-4">
        <ul class="flex justify-center space-x-10">
            <li>
                <a href="{`${base}/`}" rel="prefetch">Home</a>
            </li>
            <li>
                <a href="{`${base}/about`}" rel="prefetch">About Me</a>
            </li>
            <li>
                <a href="{`${base}/projects`}" rel="prefetch">My projects</a>
            </li>
            <li>
                <a href="https://github.com/AdiLeTwix">GitHub</a>
            </li>
        </ul>
    </div>
    </nav>
</header>
