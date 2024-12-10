# SSO-Film <html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <title>KinoSeans</title>
    <link rel="stylesheet" href="lab7t1.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    
    <header>
        <img src="unnamed.jpg" alt="Logo">
        <h1>SSO Kino</h1>
    </header>

    
    <nav>
        <a href="lab7t1.html">Басты бет</a>
        <a href="raspisania.html">Расписание кино</a>
        <div class="dropdown">
            <a href="#">Билеты</a>
            <div class="dropdown-content">
                <a href="task1.html">сегодня</a>
                <a href="task1.html">завтра</a>
                <a href="task1.html">на 30.11.24</a>
            </div>
        </div>
    </nav>
    
    
    <input type="checkbox" id="sidebarToggle">
    <label for="sidebarToggle" class="toggle-label">Меню</label>

    <input type="checkbox" id="sidebarToggle">
    <label for="sidebarToggle" class="toggle-label">Меню</label>

    
    <div class="sidebar" id="sidebar">
        <div class="sidebar-content">
           <div style="border: width: 1px; color:black;">
            <nav>
                <a href="#home">Басты бет</a>
                <a href="raspisania.html">Расписание кино</a>
                    <a href="#">Билеты</a>
                </nav></div>
        </div>
        <h2 style="text-align: center; padding-top: 20px;">Тегтер</h2>
    <div class="tags-section">
        <a href="takj3.html" class="tag">Комедия</a>
        <a href="takj3.html" class="tag">Драма</a>
       
        <a href="takj3.html" class="tag">Триллер</a>
        <a href="takj3.html" class="tag">Ғылыми-фантастика</a>
        <a href="takj3.html" class="tag">Романтика</a>
     
    </div>
    <div class="input-container">
        <input type="text" placeholder="Іздеу">
        <button>Іздеу</button>
    </div>
    
    </div>

    <script>
        
        const sidebar = document.getElementById('sidebar');
        const toggle = document.getElementById('sidebarToggle');

        
        sidebar.addEventListener('mouseleave', () => {
            toggle.checked = false; 
        });
    </script>

    
    <h2 style="text-align: center;">Популярные афишы</h2>
    <div class="categories">
        <div class="category">
            <h2>Кино</h2>
            <img src="https://avatars.mds.yandex.net/get-ott/236744/2a00000178c65f01e5a10b5c7bc9d63bf6b0/256x384" alt="Интерстеллар">
            <p>Интерстеллар</p>
        </div>
        <div class="category">
            <h2>Мультфильм</h2>
            <img src="https://avatars.mds.yandex.net/get-ott/1652588/2a00000178accfc40a2e8a5ebc5defb32e42/256x384" alt="Сериал 1">
            <p>Король лев</p>
        </div>
        <div class="category">
            <h2>Сериал</h2>
            <img src="https://avatars.mds.yandex.net/get-entity_search/8076986/687347293/S134x201_2x" alt="Сериал 1">
            <p>Игра пристолов</p>
        </div>
        
    </div>
    <h2 align="center"> Рейтинг фильмов</h2>
    <section>
        <div class="progress-bar">
            <div class="progress blue" style="width: 10%;"></div>
        </div>
        <div class="progress-bar">
            <div class="progress green" style="width: 25%;"></div>
        </div>
        <div class="progress-bar">
            <div class="progress cyan" style="width: 40%;"></div>
        </div>
        <div class="progress-bar">
            <div class="progress yellow" style="width: 50%;"></div>
        </div>
        <div class="progress-bar">
            <div class="progress red" style="width: 80%;"></div>
        </div>
    </section>
   
    <h2 style="text-align: center;">Кино жаңалықтары</h2>
    <div class="news-section">
        
        <div class="news-item">
            <h3>Жаңа фильмнің премьерасы</h3>
            <p>2024 жылдың ең көп күтілген фильмдері туралы соңғы жаңалықтар...</p>
            <a href="C:\Users\ersul\OneDrive\Рабочий стол\sabaq\cods\web\lab6\musal.html">Толығырақ</a>
        </div>
        <div class="news-item">
            <h3>Фильм рецензиялары</h3>
            <p>Қазіргі таңда экранда жүрген фильмдерге кәсіби шолулар...</p>
            <a href="C:\Users\ersul\OneDrive\Рабочий стол\sabaq\cods\web\lab6\musal.html">Толығырақ</a>
        </div>
        
    </div>
    
<hr><h2 align="center">Кинотеатры <em>Алматы</em></h2>
<div class="kinoteatr">
    <ul style="list-style-type: disc; display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-evenly; padding: 40px; margin: 0; font-family: Arial, sans-serif;">
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Chaplin ADK</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Chaplin Mega Alma-Ata</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Chaplin MegaPark</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Cinemax Dostyk Multiplex</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Halyk IMAX Kinopark 16</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinoforum 10 (TPL Forum)</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 11 Esentai IMAX</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 4 Globus</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 5 Atakent</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 5 Premium Forum</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 6 Sputnik</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinopark 8 Moskva</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinoplexx 6 Almaty Mall</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinoplexx 7 Aport</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Kinoplexx 7 Sary-Arka</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Lumiera Cinema</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">OPEN CINEMA ALMATY</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Алатау</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Арман Азия Парк</a></li>
        <li style="margin: 5px 0;"><a href="kinoteatr.html" style="color: black; text-decoration: none;">Арман Достык</a></li>
    </ul>
</div>

        <div class="share-button-container">
            <button class="share-button">
                &#x1F4E4;
            </button>
            <div class="share-menu">
                <a href="https://facebook.com" target="_blank">
                    <img src="https://avatars.mds.yandex.net/i?id=20c52274b6c9391c53e899936c459bdc8b91394a-5666813-images-thumbs&n=13" alt="Facebook" width="20" height="20">
                    <span>Facebook</span>
                </a>
                <a href="https://twitter.com" target="_blank">
                    <img src="https://avatars.dzeninfra.ru/get-zen_doc/3397162/pub_62ab23b442d9a130e8357817_62ab24762f34757208ebb829/scale_1200" alt="Twitter" width="20" height="20">
                    <span>Twitter</span>
                </a>
                <a href="https://whatsapp.com" target="_blank">
                    <img src="https://avatars.mds.yandex.net/i?id=7f19b898d53d6df47e3c00cd2a15d10fae9079ea-9874010-images-thumbs&n=13" alt="WhatsApp" width="20" height="20">
                    <span>WhatsApp</span>
                </a>
            </div>
        </div></div>
       
        
        

        
    <footer>
        
    
        <p>Байланыс ақпарат: ersul</p>
        <p> 2024 Жаңалықтар Сайты. Барлық құқықтар қорғалған.</p>
       
    </footer>
       
