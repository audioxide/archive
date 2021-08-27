<div class="newsletter-wrapper">
    <div class="newsletter-signup-box">
        <button for="email">Subscribe</button>
        <input type="email"
               id="email"
               name="email"
               placeholder="Enter your email..." />
    </div>
</div>

<style>

    .newsletter-wrapper {
        width: 60%;
        position: relative;
    }

    .newsletter-signup-box {
        margin: 0 0 10px 0;
        width: 100%;
    }

    button {
        position: absolute;
        background-color: #f01d4f;
        border: 2px solid #f01d4f;
        color: #f5f5f5;
        right: 0;
        padding: 10px 20px;
        border-radius: 0 5px 5px 0;
    }

    button:hover {
        background-color: pink;
        color: #f01d4f;
    }

    input {
        border: 2px solid #f01d4f;
        border-radius: 5px;
        padding: 10px;
        width: 90%;
    }

</style>