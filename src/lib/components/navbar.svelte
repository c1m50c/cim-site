<style>
    .navbar {
        padding: 1rem 0;
        position: fixed;
        width: 100vw;
        top: 0;

        justify-content: center;
        display: flex;
        gap: 1rem;
    }

    .navbar-button {
        color: rgb(248, 248, 248);
        text-decoration: none;
        font-size: 1.33rem;
        font-weight: 600;
        opacity: 12.5%;

        transition: color 300ms ease-in, opacity 300ms ease-in;
    }

    .navbar-button:hover {
        color: rgb(245, 177, 75);
        opacity: 100%;
    }
</style>


<nav class="navbar">
    <a class="navbar-button" href="/">HOME</a>
    <a class="navbar-button" href="/blog">BLOG</a>
    <a class="navbar-button" href="/skills">SKILLS</a>
    <a class="navbar-button" href="/projects">PROJECTS</a>
    <a class="navbar-button" href="/contact">CONTACT</a>
</nav>