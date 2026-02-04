<!DOCTYPE html>
<html lang="az">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KinoDünyası - Pulsuz Filmlər</title>
    <style>
        /* Ümumi qaranlıq tema */
        body {
            background-color: #0f0f0f;
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
        }
        /* Naviqasiya */
        header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #e50914;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        h1 { color: #e50914; margin: 0; text-transform: uppercase; letter-spacing: 2px; }
        
        /* Filmlərin düzülüşü */
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 40px 20px;
        }
        /* Film kartı */
        .movie-card {
            background-color: #1f1f1f;
            margin: 15px;
            width: 220px;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: pointer;
            border: 1px solid #333;
        }
        .movie-card:hover {
            transform: scale(1.08);
            box-shadow: 0 0 20px rgba(229, 9, 20, 0.6);
        }
        .movie-card img {
            width: 100%;
            height: 320px;
            object-fit: cover;
        }
        .movie-info {
            padding: 15px;
            text-align: left;
        }
        .movie-info h3 {
            font-size: 16px;
            margin: 0 0 5px 0;
            color: #fff;
        }
        .movie-info span {
            color: #e50914;
            font-weight: bold;
            font-size: 14px;
        }
        .genre {
            display: block;
            color: #888;
            font-size: 12px;
            margin-top: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>KinoDünyası</h1>
</header>

<div class="container">
    <div class="movie-card">
        <img src="https://image.tmdb.org/t/p/w500/q6y0Go1tsYKoBbtA2C9BVo97木.jpg" onerror="this.src='https://via.placeholder.com/220x320?text=Interstellar'" alt="Interstellar">
        <div class="movie-info">
            <h3>Interstellar</h3>
            <span>8.7 IMDB</span>
            <small class="genre">Elmi-Fantastika, Dram</small>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://image.tmdb.org/t/p/w500/8IB9S9vR7s3L9olS6p7Y7OgnYy5.jpg" onerror="this.src='https://via.placeholder.com/220x320?text=Inception'" alt="Inception">
        <div class="movie-info">
            <h3>Inception</h3>
            <span>8.8 IMDB</span>
            <small class="genre">Triller, Aksiyon</small>
        </div>
    </div>

    <div class="movie-card">
        <img src="https://image.tmdb.org/t/p/w500/qJ2tW6WMUDp9QmSbmrQvC2gACyc.jpg" onerror="this.src='https://via.placeholder.com/220x320?text=The+Batman'" alt="The Batman">
        <div class="movie-info">
            <h3>The Batman</h3>
            <span>7.8 IMDB</span>
            <small class="genre">Cinayət, Dram</small>
        </div>
    </div>
</div>

</body>
</html>
