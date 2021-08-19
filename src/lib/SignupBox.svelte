<div class="newsletter-container">

    <h1><span class="logo">Audioxide</span></h1>

    <p>Three friends reporting from the soundscapes.</p>

    <div class="newsletter-wrapper">
    <div class="newsletter-signup-box">
        <button for="email">Subscribe</button>
        <input type="email" 
               id="email" 
               name="email" 
               placeholder="Enter your email..." />
    </div>
    </div>

    <p>
        Monthly roundups of our album reviews, articles, interviews, and other
        delightful things. We've been chatting shit about music since 2015, so
        trust us, we know what we're doing.
    </p>
    <ul>
        <li>Independent music journalism</li>
        <li>Open source web development</li>
    </ul>
    <p>
        Follow us on <a href="https://facebook.com/audioxide">Facebook</a>,
        <a href="https://twitter.com/audioxide">Twitter</a>,
        <a href="https://instagram.com/audioxidecom">Instagram</a>, and
        <a href="https://audioxide.com/feed">RSS</a>. Browse our code on
        <a href="https://github.com/audioxide">GitHub</a>.
    </p>

</div>

<style>

    .newsletter-wrapper {
        width: 60%;
        position: relative;
    }

    .newsletter-container {
        position: fixed;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
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
