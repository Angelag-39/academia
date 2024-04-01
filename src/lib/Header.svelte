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
            <li class="header__btn"><a href="#contato">Contato</a></li>
        </ul>
    </nav>

</div> 
</header>

<style>
    .header__btn {
    color: #fff;
    border: 1px solid var(--feat);
    padding: 6px 12px;
    border-radius: 4px;
    transition: 250ms;
       
    }
    .header__btn:hover{
        /*background-color: #fff;
    color:var(--black);*/
    border-color: #fff;
    transition: 125ms;
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
    a:hover {
        text-decoration: underline;
    }
</style>

