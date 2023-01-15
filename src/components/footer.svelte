<footer>
    <p class="footer-text">2023 © finnala.</p>
    <div class="footer-links">
        <p><a href="https://medium.com/@finnala/" target="_blank" rel="noopener noreferrer">writing</a></p>
        <p> / </p>
        <p><a href="https://www.youtube.com/channel/UCt7tn8hSlhToJ1tmZRKsIBg" target="_blank" rel="noopener noreferrer">videos</a></p>
        <p> / </p>
        <p><a href="https://github.com/finnala" target="_blank" rel="noopener noreferrer">code</a></p>
    </div>
</footer>

<style>
    footer {
        display: flex;
        justify-content: space-between;
    }

    .footer-links {
        display: flex;
        gap: 1rem;
    }

    @media screen and (max-width:600px) {
        footer {
            flex-direction: column;
        }

        .footer-text {
            height: 1rem;
        }
    }
</style>