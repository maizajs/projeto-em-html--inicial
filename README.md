# projeto-em-html--inicial
Projeto em Html inicial no visual Studio code
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#3498db"> <!-- Cor da barra de endereço -->
  <title>Equipamentos de informática</title>
</head>

<body style="font-family: Arial">
  <p style="color:rgb(255, 0, 149)">
  <h1 title="Testando atributo title" id="titulo">
    <div style="text-align: center;">
      <br>
      <h1>Equipamentos de informatica.</h1>
    </div>
  </h1>
  <div style="text-align: center;">
    <img width="900" height="300" style="object-fit: cover"
      src="https://www.allgo.com.br/imagens/informacoes/venda-acessorios-informatica-04.webp">
  </div>
  <p>
  <div>
    <p>
    <h3>Os materiais e equipamentos de informática são os dispositivos,
      componentes e acessórios usados para o funcionamento de computadores
      e outros equipamentos eletrônicos.</h3>
    </p>
  </div>
  <h1>Cadatre-se</h1>
  <div>
    <a href="./index.html">Inicio</a>
  </div>

  <form action="" method="post">
    <label for="nome">Nome*:</label>
    <input type="text" name="nome" id="nome" required> <br>

    <label for="email">Email*:</label>
    <input type="email" name="email" id="email" required> <br>

    <label for="senha">Senha*:</label>
    <input type="password" name="senha" id="senha" required> <br>

    <label for="telefone">Telefone</label>
    <input type="tel" name="telefone" id="telefone"> <br>

    <label for="dataNascimento">Data de Nascimento:</label>
    <input type="date" name="dataNascimento" id="dataNascimento"> <br>

    <label for="agendamento">Horário de Agendamento:</label>
    <input type="time" name="agendamento" id="agendamento"> <br>

    <label for="cor">Cor Favorita:</label>
    <input type="color" name="cor" id="cor"> <br>

    <label>Tipo de Conexão:</label>
    <input type="radio" name="conexao" value="Fibra Optica" id="fibra" required>
    <label for="fibra">Fibra Optica</label>

    <input type="radio" name="conexao" value="Satelite" id="satelite" required>
    <label for="satelite">Satelite</label>
    <br>

    <label>Recursos Adicionais:</label>
    <input type="checkbox" name="streming" value="Streming de Video" id="streming">
    <label for="streming">Streming de Video</label>

    <input type="checkbox" name="musica" value="Spotify" id="musica">
    <label for="musica">Spotify</label>
    <br>

    <label for="comentario">Comentário:</label>
    <textarea name="comentario" id="comentario"></textarea> <br>

    <label for="Forma de pagamento">Forma de pagamento*:</label>
    <select name="Forma de pagamento" id="Forma de pagamento" required>
      <option disabled selected value="">Selecione um plano</option>
      <option>Cartão de credito</option>
      <option>Pix</option>
      <option>Boleto Bancario</option>
    </select> <br>

    <button>Enviar</button>
    <button type="reset">Limpar</button>
    <button type="button">Reportar</button>
  </form>

  </p>
  <br>
  <h1>Atendente:Maiza Lavor</h1>
  <ul>
    <li>(88)997224723
    </li>
    <br>
    <li>lavor.maiza@gmail.com</li>
  </ul>
  <p>
  <p id="inicio">
    Os melhores preços! &lt; abc &gt; &copy; &spades;
  </p>
  <ol>
    <li>Computador</li>
    <li>Teclado</li>
    <li>Mouse</li>
    <li> Fone de Ouvindo</li>
    <li>Notebook Acer</li>
    <li>Intel Corel i7</li>
    <li>Impressora Multifucional</li>
    <li>Microfone</li>
  </ol>
  <div class="center">
    <h1>Uma Plataforma aonde podem encontrar os melhores equipamentos de tecnologia e preços que caber no seu bolso.
    </h1>
  </div>
  <div class="box">
    <figure>
      <img width="200" src="./imagens/unseen-studio-WvuTnXz1hSc-unsplash.jpg" alt="Computador de Mesa">
      <figcaption>Computador de Mesa</figcaption>
    </figure>
  </div>

  <div class="box">
    <figure>
      <img width="200" src="./imagens/barrett-ward-Ac9L5MrIPUQ-unsplash.jpg" alt="Teclado">
      <figcaption>Teclado</figcaption>
    </figure>
  </div>

  <div class="box">
    <figure>
      <img width="200"
        src="https://images.unsplash.com/photo-1527864550417-7fd91fc51a46?q=80&w=1167&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
        alt="Mouse">
      <figcaption>Mouse</figcaption>
    </figure>
  </div>

  <div class="box">
    <figure>
      <img width="200" src="./imagens/kenny-eliason-bE3_aFt85Y8-unsplash.jpg" alt="Fone de Ouvido">
      <figcaption>Fone de Ouvido</figcaption>
    </figure>
  </div>

  <div class="box">
    <figure>
      <img width="200" src="./imagens/anete-lusina-zwsHjakE_iI-unsplash (1).jpg" alt="Notebook Acer">
      <figcaption>Notebook Acer</figcaption>
    </figure>
  </div>

  <div class="box">
    <figure>
      <img width="200"
        src="https://images.tcdn.com.br/img/img_prod/1214924/processador_1155_intel_core_i7_3770_3_90ghz_oem_21342_1_7639342a9716f825015f380b0b0b6395.jpeg"
        alt="Processador Intel Core i7">
      <figcaption>Intel Core i7</figcaption>
    </figure>
  </div>
  <style>
    div.box {

      width: 100px;
      display: flex;
      margin: 100px;
      text-align: center;
      margin: 5%;
      display: flex;
      justify-content: space-between;
      height: auto;


    }

    div.center {
      text-align: center;
    }
  </style>
  </div>
  </dl>
  <table border="1" style="border-collapse: collapse">
    <thead>
      <tr>
        <th>Produto</th>
        <th>Preço</th>
        <th>Marcas</th>
      </tr>
    </thead>
    </tbody>
    <title>Tabela de Produtos</title>
    <style>
      table {
        width: 100%;
        border-collapse: collapse;
      }

      th,
      td {
        border: 1px solid #ddd;
        padding: 10px;
        text-align: left;
      }

      th {
        background-color: #f4f4f4;
        font-weight: bold;
      }
    </style>
    </head>

    <body>
      <div class="center">
        <h1>Tabela de Produtos</h1>
      </div>

      <table>
        <title>Tabela de Produtos</title>
        <style>
          table {
            width: 100%;
            border-collapse: collapse;
          }

          th,
          td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
          }

          th {
            background-color: #f4f4f4;
            font-weight: bold;
          }

          tr:nth-child(even) {
            background-color: #f9f9f9;
          }
        </style>
        </head>

        <body>
          <table>
            <tbody>
              <tr>
                <td>Computador de Mesa</td>
                <td>R$ 1.274,91</td>
                <td>Dell</td>
              </tr>
              <tr>
                <td>Teclado</td>
                <td>R$ 150,00</td>
                <td>Logitech</td>
              </tr>
              <tr>
                <td>Mouse</td>
                <td>R$ 75,00</td>
                <td>Microsoft</td>
              </tr>
              <tr>
                <td>Fone de Ouvido</td>
                <td>R$ 199,90</td>
                <td>JBL</td>
              </tr>
              <tr>
                <td>Microfone</td>
                <td>R$ 100,00</td>
                <td>Shure</td>
              </tr>
              <tr>
                <td>Notebook Acer</td>
                <td>R$ 2.899,00</td>
                <td>Acer</td>
              </tr>
              <tr>
                <td>Intel Core i7</td>
                <td>R$ 1.399,00</td>
                <td>Intel</td>
              </tr>
              <tr>
                <td>Impressora Multifuncional</td>
                <td>R$ 699,00</td>
                <td>HP</td>
              </tr>
              <tr>
                <td></td>
              </tr>
            </tbody>
          </table>

        </body>

</html>
