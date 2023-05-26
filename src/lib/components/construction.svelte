<style>
    .backdrop {
        background-color: rgb(12, 12, 12, 75%);
        position: absolute;
        min-height: 200vh;
        min-width: 200vw;
        overflow: hidden;
        left: -100vw;
        top: -100vh;
    }

    .construction-notice {
        position: absolute;

        display: flex;
        flex-flow: column;

        transform: translate(-50%, -50%);
        left: 75%;
        top: 75%;
    }

    .construction-notice h1, p, a {
        text-align: center;
    }

    .construction-notice a {
        background-color: rgb(24, 24, 24);
        color: rgb(248, 248, 248);
        text-decoration: none;
        border-radius: 0.5rem;
        font-weight: 600;
        padding: 0.5rem;

        transition: color 300ms ease-in, background-color 300ms ease-in;
    }

    .construction-notice a:hover {
        background-color: rgb(28, 28, 28);
        color: rgb(245, 177, 75);
    }
</style>

<div class="backdrop">
    <div class="construction-notice">
        <h1>Under Construction 🚧🏗️</h1>
        <p>This page is under construction and is not yet implemented.</p>
        <a href="/">Go Home</a>
    </div>
</div>