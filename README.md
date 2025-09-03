# pagina-da-web
projeto


<html lang="pt-BR">

<head>
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap"
        rel="stylesheet">
    <title>Aluraflix</title>
</head>

<body>
    <header>ALURAFLIX</header>

    <section>
        <div class="chamada-texto">
            <h1>ATRAVÉS DO ARANHAVERSO</h1>
            <p>#homem-aranha</p>
        </div>

        <div>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/gt_fAE1Eg2Q?si=EEv-tsY_b1B2OwKE"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
        </div>
    </section>

</body>

</html>



body {
    color: white;
    background: black;
    margin: 0px;
    font-family: "Chakra Petch", sans-serif;
}

header {
    border-bottom: solid 2px rgb(42, 122, 228);
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
}

section {
    background: rgb(128, 17, 10);
    padding-bottom: 80px;
    padding-top: 80px;
    display: flex;
    justify-content: center;
}

.chamada-texto {
    margin-right: 5%;
}

h1 {
    font-size: 40px;
}

p {
    font-size: 20px;
}
