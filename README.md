# monteiro-fashion
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monteiro Fashion | Estilo e Elegância</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #fcfcfc;
            color: #333;
        }

        header {
            background-color: #fff;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #eee;
        }

        .logo {
            font-weight: bold;
            font-size: 24px;
            color: #e056fd;
        }

        .banner {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1441986300917-64674bd600d8?auto=format&fit=crop&w=1200&q=80') no-repeat center center/cover;
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .banner h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }

        .banner p {
            font-size: 18px;
            margin-bottom: 20px;
        }

        .btn-whats {
            background-color: #25d366;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 30px;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn-whats:hover {
            background-color: #1ebd59;
        }

        .vitrine {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .vitrine h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 28px;
            color: #222;
        }

        .grid-produtos {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .produto-card {
            background: white;
            border: 1px solid #eee;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            padding-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        .produto-card img {
            width: 100%;
            height: 300px;
            object-fit: cover;
        }

        .produto-card h3 {
            font-size: 18px;
            margin: 15px 0 5px 0;
        }

        .produto-card .preco {
            color: #e056fd;
            font-weight: bold;
            font-size: 18px;
            margin-bottom: 15px;
        }

        footer {
            background-color: #222;
            color: #ccc;
            text-align: center;
            padding: 30px 20px;
            margin-top: 50px;
        }

        footer p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Monteiro Fashion 🛍️</div>
    </header>

    <section class="banner">
        <h1>Nova Coleção de Inverno</h1>
        <p>As melhores tendências com o preço que você merece.</p>
        <a href="#" class="btn-whats">Falar com uma Vendedora no WhatsApp</a>
    </section>

    <section class="vitrine">
        <h2>Destaques da Semana</h2>
        
        <div class="grid-produtos">
            <div class="produto-card">
                <img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=500&q=80" alt="Look Casual">
                <h3>Look Casual Elegante</h3>
                <p class="preco">R$ 129,90</p>
                <a href="#" class="btn-whats">Gostei! Quero comprar</a>
            </div>

            <div class="produto-card">
                <img src="https://images.unsplash.com/photo-1485968579580-b6d095142e6e?auto=format&fit=crop&w=500&q=80" alt="Casaco Estiloso">
                <h3>Casaco Moderno Outono</h3>
                <p class="preco">R$ 189,90</p>
                <a href="#" class="btn-whats">Gostei! Quero comprar</a>
            </div>

            <div class="produto-card">
                <img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b?auto=format&fit=crop&w=500&q=80" alt="Vestido">
                <h3>Vestido Premium Floral</h3>
                <p class="preco">R$ 149,90</p>
                <a href="#" class="btn-whats">Gostei! Quero comprar</a>
            </div>
        </div>
    </section>

    <footer>
        <p><strong>Monteiro Fashion</strong></p>
        <p>📍 Centro, Monteiro - PB</p>
        <p>© 2026 Todos os direitos reservados. Criado por você!</p>
    </footer>

</body>
</html>
