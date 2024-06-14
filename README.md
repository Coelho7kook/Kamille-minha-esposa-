git remoto adicionar origem https://github.com/Coelho7kook/Kamille-minha-esposa-.git
 git branch -M main 
git push -u origin main


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz Dia dos Namorados, Kamille!</title>
    <style>
        body {
            color: #f0c2c2;
            font-family: 'Arial', sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
        }
        h1 {
            color: #ff007f;
        }
        button {
            background-color: transparent;
            border: none;
            margin: 10px;
            cursor: pointer;
            border-radius: 10px;
        }
        button img {
            width: 100px;
            height: 100px;
            border-radius: 10px;
        }
        .hidden {
            display: none;
            margin-top: 20px;
            max-width: 600px;
            text-align: center;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        .poem {
            margin: 20px;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
        }
        audio {
            display: none;
        }
        video#background-video {
            position: fixed;
            top: 50%;
            left: 50%;
            width: 100%;
            height: 100%;
            object-fit: cover;
            transform: translate(-50%, -50%);
            z-index: -1;
        }
        .content {
            position: relative;
            z-index: 1;
        }
    </style>
    <script>
        function showContent(id, audioId) {
            var elements = document.getElementsByClassName('hidden');
            for (var i = 0; i < elements.length; i++) {
                elements[i].style.display = 'none';
            }
            document.getElementById(id).style.display = 'block';
            
            var audios = document.getElementsByTagName('audio');
            for (var j = 0; j < audios.length; j++) {
                audios[j].pause();
                audios[j].currentTime = 0;
            }
            document.getElementById(audioId).play();
        }
    </script>
</head>
<body>
    <video id="background-video" autoplay muted loop>
        <source src="background.mp4" type="video/mp4">
        Seu navegador não suporta a tag de vídeo.
    </video>
    <div class="content">
        <h1>Feliz Dia dos Namorados, Kamille!</h1>
        <p>Você é minha inspiração e meu desejo. Clique nos botões abaixo para descobrir algo especial.</p>
        
        <button onclick="showContent('frase1', 'audio1')">
            <img src="imagem1.jpg" alt="Frase Romântica 1">
        </button>
        <button onclick="showContent('frase2', 'audio2')">
            <img src="imagem2.jpg" alt="Frase Romântica 2">
        </button>
        <button onclick="showContent('poema1', 'audio3')">
            <img src="imagem3.jpg" alt="Poema Sensual 1">
        </button>
        <button onclick="showContent('poema2', 'audio4')">
            <img src="imagem4.jpg" alt="Poema Sensual 2">
        </button>
        <button onclick="showContent('poema3', 'audio5')">
            <img src="imagem5.jpg" alt="Poema Sensual 3">
        </button>
        <button onclick="showContent('poema4', 'audio6')">
            <img src="imagem6.jpg" alt="Poema Sensual 4">
        </button>
        <button onclick="showContent('poema5', 'audio7')">
            <img src="imagem7.jpg" alt="Poema Sensual 5">
        </button>
        <button onclick="showContent('poema6', 'audio8')">
            <img src="imagem8.jpg" alt="Poema Sensual 6">
        </button>
        <button onclick="showContent('poema7', 'audio9')">
            <img src="imagem9.jpg" alt="Poema Sensual 7">
        </button>
        <button onclick="showContent('poema8', 'audio10')">
            <img src="imagem10.jpg" alt="Poema Sensual 8">
        </button>

        <audio id="audio1" src="musica1.mp3"></audio>
        <audio id="audio2" src="musica2.mp3"></audio>
        <audio id="audio3" src="musica3.mp3"></audio>
        <audio id="audio4" src="musica4.mp3"></audio>
        <audio id="audio5" src="musica5.mp3"></audio>
        <audio id="audio6" src="musica6.mp3"></audio>
        <audio id="audio7" src="musica7.mp3"></audio>
        <audio id="audio8" src="musica8.mp3"></audio>
        <audio id="audio9" src="musica9.mp3"></audio>
        <audio id="audio10" src="musica10.mp3"></audio>

        <div id="frase1" class="hidden">
            <p>"A cada dia que passa, meu amor por você só aumenta. Feliz Dia dos Namorados, minha eterna paixão."</p>
        </div>
        <div id="frase2" class="hidden">
            <p>"Seu sorriso ilumina meu mundo. Te amo mais do que palavras podem expressar. Feliz Dia dos Namorados, meu amor."</p>
        </div>
        <div id="poema1" class="hidden poem">
            <p>Te envolver em meus braços, sentir seu corpo se arrepiar,<br>
            Beijar seu pescoço, ouvir seus suspiros, gemidos de prazer.<br>
            O toque suave que faz sua pele estremecer,<br>
            Nosso amor é intenso, um êxtase a cada amanhecer.</p>
        </div>
        <div id="poema2" class="hidden poem">
            <p>Amarrarei suas mãos com delicadeza,<br>
            Seus olhos vendados, sua respiração acelerada.<br>
            Sentir seu corpo se contorcer, a expectativa no ar,<br>
            Nossos desejos se encontram, puro prazer e sedução.</p>
        </div>
        <div id="poema3" class="hidden poem">
            <p>Seu gemido suave me deixa em êxtase,<br>
            O sabor da sua pele, um convite ao desejo.<br>
            Beijos no pescoço, arrepios que causam prazer,<br>
            Nosso amor é uma dança, uma sinfonia de gemidos.</p>
        </div>
        <div id="poema4" class="hidden poem">
            <p>Te amarrar na cama, ver seu corpo se entregar,<br>
            Seus suspiros e gemidos, um balé de emoção.<br>
            Sentir cada arrepio, cada desejo realizado,<br>
            Nosso amor é um jogo de prazer e paixão.</p>
        </div>
        <div id="poema5" class="hidden poem">
            <p>Minha língua desliza suavemente pelo seu pescoço,<br>
            Cada toque causando arrepios de prazer.<br>
            Seus gemidos são a melodia que guia nossos movimentos,<br>
            Uma dança de corpos entrelaçados e desejos ardentes.</p>
        </div>
        <div id="poema6" class="hidden poem">
            <p>Minhas mãos exploram cada centímetro do seu corpo,<br>
            Sentindo a suavidade da sua pele.<br>
            Seus olhos fechados em expectativa,<br>
            Cada beijo, cada toque, levando-nos ao êxtase.</p>
        </div>
        <div id="poema7" class="hidden poem">
            <p>Seu corpo é meu templo, onde adoro cada detalhe,<br>
            Beijando, mordiscando, explorando sem pressa.<br>
            Seus suspiros e gemidos me guiam,<br>
            Uma sinfonia de prazer e paixão.</p>
        </div>
        <div id="poema8" class="hidden poem">
            <p>No calor da nossa entrega, nos perdemos na dor e no prazer,<br>
            O toque suave da luxúria se mistura com o ardor do sofrer.<br>
            Amarro suas mãos com a seda da submissão,<br>
            Seus olhos brilham com a excitação da rendição.</p>
            
            <p>Sussurro promessas de êxtase e de dor,<br>
            Cada chicoteada é um gemido de desejo, um clamor.<br>
            Seu corpo se contorce sob meu comando,<br>
            Cada marca, uma marcação de um amor profundo e insano.</p>
            
            <p>O prazer se entrelaça com a dor em nossa dança,<br>
            E o masoquismo se torna a nossa liberdade, nossa esperança.<br>
            Nossos corpos em harmonia, em um frenesi de paixão,<br>
            Até encontrarmos a calmaria após a intensa tempestade da nossa união.</p>
            
            <p>Em cada suspiro, em cada toque, somos dois em um só ser,<br>
            Uma simbiose de desejos que nos faz transcender.<br>
            A entrega completa, sem reservas, sem medo,<br>
            Num amor que se define pela intensidade do nosso enredo.</p>
            
            <p>Cada enlace é uma dança cósmica de emoção,<br>
            Onde o prazer se entrelaça com a dor em perfeita comunhão.<br>
            Cada instante é eternizado pelo fogo que nos consome,<br>
            Até que o êxtase se transforme em calma e nossos corpos se tornem um só nome.</p>
        </div>
    </div>
</body>
</html>
