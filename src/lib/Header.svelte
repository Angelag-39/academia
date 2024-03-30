<script>
    import logo from '$lib/assets/logo.png'
</script>

<header class="header">
 <div class="header__wrapper wrap">   
    <a href="/" class="logo"><img src="{logo}" alt="Logo da Academia local"></a>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/sobre">Sobre</a></li>
            <li><a href="/modalidades">Modalidades</a></li>
            <li class="btn header__btn"><a href="#contato">Contato</a></li>
        </ul>
    </nav>

</div> 
</header>
<style>
    .header__btn {
        border-color: var(--feat);
    }
    .header__btn:hover {
        border-color: #ffff;
    }
    .header__wrapper {
       display: flex; 
       align-items: center;
       min-height: 120px;
    }
    .logo{
        max-width: 277px;
    }
    nav {
        margin-left: auto;
    }
    ul {
        display: flex;
        align-items: center;
        gap: 24px;
    }
    a{
        color: #ffff;
    }
    a:not(.btn) :hover {
        text-decoration: underline;
    }
</style>