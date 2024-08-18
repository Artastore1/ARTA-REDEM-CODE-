<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Montu Hosting</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        .container {
            padding: 20px;
        }
        .header {
            text-align: center;
            padding: 20px;
            font-size: 2em;
            font-weight: bold;
            color: #FFD700;
        }
        .list {
            margin: 20px 0;
        }
        .list-item {
            background-color: #1e1e1e;
            margin: 10px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px purple;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .list-item h3 {
            margin: 0;
            color: #FFD700;
        }
        .list-item p {
            margin: 5px 0;
        }
        .buy-button {
            background-color: #FFD700;
            color: #121212;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .buy-button:hover {
            background-color: #FFA500;
        }
        .moving-list {
            display: flex;
            overflow: hidden;
            white-space: nowrap;
            animation: scroll 10s linear infinite;
        }
        .moving-list .list-item {
            display: inline-block;
            width: 300px;
            margin: 0 10px;
        }
        .controls {
            text-align: center;
            margin: 20px 0;
        }
        .controls button {
            background-color: #FFD700;
            color: #121212;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
            margin: 0 10px;
        }
        .controls button:hover {
            background-color: #FFA500;
        }
        @keyframes scroll {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
    </style>
    <script>
        function buy(package) {
            window.location.href = 'https://wa.me/6289530292518?text=I%20want%20to%20buy%20' + encodeURIComponent(package);
        }
        function stopScroll() {
            document.querySelector('.moving-list').style.animationPlayState = 'paused';
        }
        function startScroll() {
            document.querySelector('.moving-list').style.animationPlayState = 'running';
        }
    </script>
</head>
<body>
    <div class="container">
        <div class="header">LIST JUALAN MONTU HOSTING</div>

        <div class="list">
            <h2>PANEL BOT WA</h2>
            <div class="list-item">
                <div>
                    <h3>PAKET 1</h3>
                    <p>PANEL 1GB</p>
                    <p>RAM 1GB</p>
                    <p>CPU 60%</p>
                    <p>ANTI DELAY</p>
                    <p>HARGA: 1K</p>
                </div>
                <button class="buy-button" onclick="buy('PAKET 1')">Beli</button>
            </div>
            <div class="list-item">
                <div>
                    <h3>PAKET 2</h3>
                    <p>PANEL 2GB</p>
                    <p>RAM 2GB</p>
                    <p>CPU 100%</p>
                    <p>ANTI DELAY</p>
                    <p>HARGA: 2K</p>
                </div>
                <button class="buy-button" onclick="buy('PAKET 2')">Beli</button>
            </div>
            <div class="list-item">
                <div>
                    <h3>PAKET 3</h3>
                    <p>PANEL 3B</p>
                    <p>RAM 3GB</p>
                    <p>CPU 130%</p>
                    <p>ANTI DELAY</p>
                    <p>HARGA: 3KK</p>
                </div>
                <button class="buy-button" onclick="buy('PAKET 3')">Beli</button>
            </div>
            <div class="list-item">
                <div>
                    <h3>PAKET 4</h3>
                    <p>PANEL UNLIMITED</p>
                    <p>RAM UNLIMITED</p>
                    <p>CPU UNLIMITED</p>
                    <p>ANTI DELAY</p>
                    <p>ANTI DDOS</p>
                    <p>SC BOT AMAN</p>
                    <p>HARGA: 20K</p>
                </div>
                <button class="buy-button" onclick="buy('PAKET 4')">Beli</button>
            </div>
        </div>

        <div class="list">
            <h2>Hosting SAMP</h2>
            <div class="moving-list">
                <div class="list-item">
                    <div>
                        <h3>PAKET 1</h3>
                        <p>SLOT 55</p>
                        <p>RAM 18GB</p>
                        <p>CPU 100%</p>
                        <p>OPEN PORT</p>
                        <p>HARGA: 5K</p>
                    </div>
                    <button class="buy-button" onclick="buy('PAKET 1')">Beli</button>
                </div>
                <div class="list-item">
                    <div>
                        <h3>PAKET 2</h3>
                        <p>SLOT 100</p>
                        <p>RAM 25GB</p>
                        <p>CPU 100%</p>
                        <p>OPEN PORT</p>
                        <p>HARGA: 10K</p>
                    </div>
                    <button class="buy-button" onclick="buy('PAKET 2')">Beli</button>
                </div>
                <div class="list-item">
                    <div>
                        <h3>PAKET 3</h3>
                        <p>SLOT 150</p>
                        <p>RAM 35GB</p>
                        <p>CPU 100%</p>
                        <p>OPEN PORT</p>
                        <p>HARGA: 15K</p>
                    </div>
                    <button class="buy-button" onclick="buy('PAKET 3')">Beli</button>
                </div>
                <div class="list-item">
                    <div>
                        <h3>PAKET 4</h3>
                        <p>SLOT 220</p>
                        <p>RAM UNLIMITED</p>
                        <p>CPU UNLIMITED</p>
                        <p>OPEN PORT</p>
                        <p>HARGA: 20K</p>
                    </div>
                    <button class="buy-button" onclick="buy('PAKET 4')">Beli</button>
                </div>
            </div>
            <div class="controls">
                <button onclick="stopScroll()">Stop</button>
                <button onclick="startScroll()">Start</button>
            </div>
        </div>
    </div>
</body>
</html>
