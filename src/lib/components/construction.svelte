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

        transform: translate(-50%, -50%);
        left: 75%;
        top: 75%;
    }

    .construction-notice h1, p {
        position: relative;
        text-align: center;
    }

    .construction-notice h1::before {
        display: inline-block;
        position: absolute;
        content: "🔨";
        left: 2.45rem;
        top: -0.65rem;
        scale: -1 1;

        animation: 2s hammer-swing 500ms infinite;
    }

    @keyframes hammer-swing {
        from {
            transform: rotateZ(0deg);
        }

        50% {
            transform: rotateZ(45deg);
        }

        to {
            transform: rotateZ(0deg);
        }
    }
</style>

<div class="backdrop">
    <div class="construction-notice">
        <h1>Under Construction 🚧🏗️</h1>
        <p>This page is under construction and is not yet implemented.</p>
    </div>
</div>