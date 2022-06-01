<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <!-- FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Unica+One&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dela+Gothic+One&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Karla&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Eczar:wght@700&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Rammetto+One&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cousine:wght@700&display=swap" rel="stylesheet">
    <!-- FONT-AWESOME ICONS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <title>Journal</title>
</head>
<body>
    <header>
        <h1>portfolio</h1>
        <div id="head-square"></div>
        <div id="head-circle"></div>
    </header>
    <!-- MOBILE MENU -->
    <nav id="nav-mob">
        <input type="checkbox" id="show">
        <label for="show"><span class="fa-solid fa-bars" id="nav-icon-mob"></span></label>
        <label for="show"><span id="nav-icon-desk">Me<br>nu</span></label>
        <span id="nav-links-mob">
            <ul id="nav-list">
                <br/>
                <li id="home-li"><a href="">home</a></li>
            <li id="about-li"><a href="./about.html">about</a></li>
            <li id="personal-li"><a href="./personal.html">personal</a></li>
            <li id="code-li"><a href="./code.html">code</a></li>
            <li id="journal-li"><a href="./journal.html">journal</a></li>
            <li id="contact-li"><a href="./contact.html">contact</a></li>
            </ul>
        </span>
    </nav>
    <!-- DESKTOP MENU -->
    <input type="checkbox" id="menu-button">
    <label for="menu-button" id="menu-text">menu<br><span class="fa-solid fa-arrows-alt-h" id="arrow"></span></label>
    <nav id="nav-cont">
        <ul id="nav-list">
            <br/>
            <li id="home-li"><a href="">home</a></li>
            <li id="about-li"><a href="./about.html">about</a></li>
            <li id="personal-li"><a href="./personal.html">personal</a></li>
            <li id="code-li"><a href="./code.html">code</a></li>
            <li id="journal-li"><a href="./journal.html">journal</a></li>
            <li id="contact-li"><a href="./contact.html">contact</a></li>
            <figure>
                <img id="portrait" src="./img/archie.png" alt="Portrait">
            </figure>
        </ul>
    </nav>
    <main>
        <h2 class="mob-page-sub">journal</h2>
        <h2 class="desk-page-sub"><br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.<br>j<br>o<br>u<br>r<br>n<br>a<br>l<br>.</h2>
        <!-- FOR CLICK EXPAND -->
        <label for="expand-1"><span class="expand-1" id="expand-icon-1">expand/collapse</span></label>
        <input type="checkbox" id="expand-1"/>
        
        <section class="card" id="sec-1">
            <article>
                <h2>Blog Post One</h2>
                <time class="blog-time" datetime="2022-05-31 12:36">31-05-2022 12:36pm</time>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc nec ex tellus. Nulla et orci interdum, congue nisl in, ultricies massa. Pellentesque lobortis velit a faucibus ornare. Duis convallis tortor sem, sed ullamcorper felis laoreet in. Donec vitae porta nibh. Duis vestibulum tincidunt enim in lobortis. Fusce ut nunc eget enim condimentum tempus. Nunc erat velit, molestie vehicula ligula id, pellentesque ornare neque. Quisque placerat enim nec metus efficitur, id lobortis enim euismod.
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tellus lacus, placerat a semper ut, suscipit et mi. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Praesent ut velit id diam finibus dignissim. Maecenas nulla velit, commodo ac justo a, hendrerit vehicula ligula. Proin sit amet nunc fringilla, mollis diam ac, tincidunt elit. Cras id sem posuere, condimentum elit vel, volutpat sem. Donec sit amet sem et odio eleifend sollicitudin. Quisque convallis egestas nulla vel vehicula. Donec sodales diam turpis, facilisis congue est consequat nec. Quisque mauris dui, condimentum eleifend finibus eu, pretium at nisl. Nulla vel fringilla elit. Aenean in eros hendrerit orci vulputate viverra eu eget sapien. Curabitur placerat aliquet nisi sed ullamcorper.

                Ut eros diam, venenatis ut dignissim at, vehicula vel turpis. Interdum et malesuada fames ac ante ipsum primis in faucibus. Sed tincidunt id justo a posuere. Morbi consectetur ornare ornare. Sed eros dui, accumsan vel nibh sed, ultricies rhoncus lorem. Vestibulum varius, lorem posuere lobortis convallis, massa nibh sodales lorem, at rutrum neque lectus nec metus. Sed consectetur ante sit amet augue consequat porta. Integer risus nisl, venenatis nec commodo quis, maximus eget tellus. In dictum laoreet ligula, ut porta risus consequat at.

                Nulla vehicula tellus non dapibus sagittis. Maecenas luctus sagittis felis, ac tempus neque dictum ut. Vestibulum rhoncus, massa ac suscipit dapibus, sem ex eleifend dolor, vel commodo risus enim id velit. Ut ullamcorper turpis felis, non aliquam sapien varius ut. Nullam arcu nibh, sodales a ornare non, porta sit amet nulla. Etiam sed vulputate sem. Aliquam nulla mi, eleifend sit amet erat sed, dictum viverra dolor. Sed at turpis sagittis, consectetur est eget, ornare felis. Nunc congue dapibus venenatis. Sed consectetur dui vitae tortor elementum, sit amet pharetra elit maximus. Nam at eleifend tellus. Donec diam dui, fringilla nec pellentesque sit amet, eleifend et est.

                Phasellus finibus ornare felis ut dictum. Quisque dignissim arcu odio, vel pharetra erat dictum non. Aliquam posuere in massa auctor venenatis. Aliquam id sollicitudin eros. Integer ullamcorper magna vitae rhoncus varius. Quisque leo nulla, sollicitudin ut ante sit amet, condimentum facilisis ex. Praesent euismod odio elit, sed venenatis turpis vestibulum at. Cras at feugiat lorem, ac fermentum tortor. Nulla in commodo felis, non congue sem. Nulla scelerisque odio faucibus turpis malesuada, eu blandit est eleifend.

                Praesent fermentum, lacus sodales accumsan viverra, magna nulla molestie turpis, ut rutrum turpis dolor non metus. Pellentesque tempus varius augue, eget consectetur lacus. Nunc sed ex metus. Cras rutrum at urna eu efficitur. Vivamus eget venenatis tellus. Phasellus tincidunt sem ornare, dictum erat ut, suscipit lectus. Donec viverra laoreet leo, quis suscipit urna ultrices id. Donec vestibulum convallis facilisis. Integer ut lacus porta, lobortis mi id, consequat ex. Integer condimentum mauris eget faucibus mollis. Etiam volutpat dictum purus, a vehicula ipsum auctor quis. Integer mi magna, pellentesque non diam ac, ultrices facilisis quam. Nulla in velit tincidunt, congue urna porta, volutpat arcu. Aenean ultrices ligula eu suscipit ullamcorper. Aliquam aliquet, ipsum ut volutpat sodales, leo magna faucibus risus, sed scelerisque neque odio quis metus. Curabitur rutrum est ac tortor vulputate tincidunt.
            </p>
            </article>
        </section>

    </main>
    <footer>
        <form action="./contact.html">
            <input type="submit" value="Contact me" id="contact-button"/>
        </form>
    </footer>
    <script></script>
</body>
</html>