<!DOCTYPE html>
<html lang="it">
<head>
    <link rel="icon" href="logo3.ico.ico" type="image/x-icon">

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biscotteria Pinocchio</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, footer {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav {
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        main {
            padding: 20px;
            margin-left: 50px; 
        }
        .dimensioni-immagine {
            width: 300px;
            height: 600px;
            margin-top: 30px; 
            margin-left: -1130px;
        }
        header h1 {
            margin-left: -1150px;
        }
        .background-image {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-size: cover;
            pointer-events: none;
            opacity: 0.12;
        }
        .carousel-item img {
    width: 100%;
    height: 70%; /* Imposta l'altezza al 100% dell'elemento padre */
    object-fit: cover; /* Copre completamente l'area senza distorcere l'immagine */
}

    </style>
</head>
<body>
    <header>
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="biscotti-al-burro.jpg" alt="biscotti confezionati">
                    <div class="carousel-caption">
                        <h3>Biscotti Confezionati</h3>
                        <p>Descrizione dei biscotti confezionati</p>
                    </div>
                </div>
        
                <div class="carousel-item">
                    <img src="preferiti.jpg" alt="biscotti artigianali">
                    <div class="carousel-caption">
                        <h3>Biscotti Artigianali</h3>
                        <p>Descrizione dei biscotti artigianali</p>
                    </div>
                </div>
        
                <div class="carousel-item">
                    <img src="sfondo.jpg" alt="biscotti fuori produzione">
                    <div class="carousel-caption">
                        <h3>Biscotti Fuori Produzione</h3>
                        <p>Descrizione dei biscotti fuori produzione</p>
                    </div>
                </div>
            </div>
            <a class="carousel-control-prev" href="#myCarousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#myCarousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
        
    </header>    
    <nav>
        <a href="home.html">Home</a>
        <a href="servizi.html">Servizi</a>
        <a href="contatti.html">Contatti</a>
    </nav>
    <main>
        <h2>come mangiare i biscotti</h2>
        <p>salve qui vi spiegherò come si mangiano i biscotti</p>
    </main>
    <footer>
        <p>...---...</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
    <script>
        $(document).ready(function(){
            $('#myCarousel').carousel({
                interval: 8000000
            });
        });
    </script>
</body>
</html>
