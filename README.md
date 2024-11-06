# Yago_Projeto2
>
<HTML->>

<cabeça>
  <meta conjunto de caracteres="UTF-8">
  <meta nome="janela de visualização"contente="largura=largura-do-dispositivo, escala-inicial=1.0">
  <título>Livros Alura</título>
  <link rela="folha de estilo"href="redefinir.css">
  <link rela="pré-conexão"href="https://fonts.googleapis.com">
  <link rela="pré-conexão"href="https://fonts.gstatic.com"origem cruzada>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;700&display=swap"rela="folha de estilo">
  <link href="https://fonts.googleapis.com/css?family=Josefin+Sans:wght@400;700&display=swap"rela="folha de estilo">
  <link rela="folha de estilo"href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
  <link rela="folha de estilo"href="estilos.css">
</cabeça>

<corpo>
  <cabeçalho aula="cabeçalho">
    <dividir aula="recipiente">
      <entrada tipo="caixa de seleção"eu ia="menu"aula="container__botao">
      <rótulo para="menu"aula="container__rotulo">
        <extensão aula="cabeçalho__menu-hamburguer container__imagem"></extensão>
      </rótulo>
      <o aula="lista-menu">
        <eu aula="lista-menu__titulo">Categorias</eu>
        <eu aula="lista-menu__item">
          <um href="#"aula="lista-menu__link">Programação</um>
        </eu>
        <eu aula="lista-menu__item">
          <um href="#"aula="lista-menu__link">Front-end</um>
        </eu>
        <eu aula="lista-menu__item">
          <um href="#"aula="lista-menu__link">Infraestrutura</um>
        </eu>
        <eu aula="lista-menu__item">
          <um href="#"aula="lista-menu__link">Negócios</um>
        </eu>
        <eu aula="lista-menu__item">
          <um href="#"aula="lista-menu__link">Design e UX</um>
        </eu>
      </o>
      <imagem fonte="img/Logotipo.svg"alt="Logo da Alurabooks"aula="imagem_do_container">
      <h1 aula="container__titulo"><b aula="container__titulo--negrito">Alura</b>Livros</h1>

      <o aula="opções">
        <entrada tipo="caixa de seleção"eu ia="opções-menu"aula="opções__botão" />
        <rótulo para="opções-menu"aula="opções__rotulo">
          <eu aula="opções__item">Categorias</eu>
        </rótulo>

        <o aula="lista-menu">
          <eu aula="lista-menu__item">
            <um href="#"aula="lista-menu__link">Programação</um>
          </eu>
          <eu aula="lista-menu__item">
            <um href="#"aula="lista-menu__link">Front-end</um>
          </eu>
          <eu aula="lista-menu__item">
            <um href="#"aula="lista-menu__link">Infraestrutura</um>
          </eu>
          <eu aula="lista-menu__item">
            <um href="#"aula="lista-menu__link">Negócios</um>
          </eu>
          <eu aula="lista-menu__item">
            <um href="#"aula="lista-menu__link">Design e UX</um>
          </eu>
        </o>
        <eu aula="opções__item"><um href="#"aula="opções__link">Favoritos</um></eu>
        <eu aula="opções__item"><um href="#"aula="opções__link">Minha propriedade</um></eu>
      </o>

    </dividir>
    <dividir aula="recipiente">
      <um href="#"><imagem fonte="img/Favoritos.svg"alt="Meus favoritos"
          aula="container__imagem container__imagem-transparente"></um>
      <um href="#"aula="link_do_container">
        <imagem fonte="img/Compras.svg"alt="Carrinhos de compras"aula="imagem_do_container">
        <p aula="container__texto">Minha sacola</p>
      </um>
      <um href="#"aula="link_do_container">
        <imagem fonte="img/Usuário.svg"alt="Meu perfil"aula="imagem_do_container">
        <p aula="container__texto">Meu perfil</p>
      </um>
    </dividir>
  </cabeçalho>

  <seção aula="bandeira">
    <h2 aula="banner__titulo">Já sabe por onde começar?</h2>
    <p aula="banner__texto">Encontre em nossa estante o que precisa para seu desenvolvimento!</p>
    <entrada tipo="procurar"aula="banner__pesquisa"espaço reservado="Qual será sua próxima leitura?">
  </seção>

  <seção aula="carrossel">
    <h2 aula="carrossel__titulo">Novos lançamentos</h2>

    <dividir aula="carrossel__container">
      <!-- Contêiner principal do controle deslizante -->
      <dividir aula="deslizador">

        <dividir aula="paginação de swiper"></dividir>
        <!-- Wrapper adicional necessário -->
        <dividir aula="envoltório-do-swiper">
          <!-- Slides -->
          <dividir aula="deslizador-deslizante"><imagem fonte="img/ApacheKafka.svg"
              alt="Livro sobre apache kafka e spring boot da alura books"></dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Liderança.svg"
              alt="Livro sobre liderança em design design da alura books"></dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Javascript.svg"alt="Livro sobre javascript assertivo da alura books">
          </dividir>
          <dividir aula="deslizador-deslizante">
            <imagem fonte="img/Guia Front-end.svg"alt="Front end do Livro Guia" />
          </dividir>
          <dividir aula="deslizador-deslizante">
            <imagem fonte="img/Portugol.svg"alt="Livro sobre portugol" />
          </dividir>
          <dividir aula="deslizador-deslizante">
            <imagem fonte="img/Acessibilidade.svg"alt="Livro sobre acessibilidade" />
          </dividir>
        </dividir>

        <!-- Se precisarmos de botões de navegação -->
        <dividir aula="botão-deslizador-anterior"></dividir>
        <dividir aula="botão-deslizante-próximo"></dividir>

      </dividir>

      <dividir aula="cartão">
        <dividir aula="card__descrição">
          <dividir aula="descrição">
            <h3 aula="descrição__titulo">Talvez você também se interesse por...</h3>
            <h2 aula="descrição__titulo-livro">Angular 11 e Firebase</h2>
            <p aula="descrição__texto">
              Construindo uma aplicação integrada com a plataforma do Google.
            </p>
          </dividir>
          <imagem fonte="imagem/Angular.svg"aula="descrição__imagem" />
        </dividir>
        <dividir aula="card__botões">
          <o aula="botões">
            <eu aula="botões__item">
              <imagem fonte="img/Favoritos.svg"alt="Favoritar livro" />
            </eu>
            <eu aula="botões__item">
              <imagem fonte="img/Compras.svg"alt="Adicionar no carrinho de compras" />
            </eu>
          </o>
          <um href="#"aula="botões__ancora">Saiba mais</um>
        </dividir>
      </dividir>
    </dividir>

  </seção>

  <seção aula="carrossel">
    <h2 aula="carrossel__titulo">Mais vendidos</h2>

    <dividir aula="carrossel__container">
      <dividir aula="deslizador">
        <!-- Wrapper adicional necessário -->
        <!-- Se precisarmos de paginação -->
        <dividir aula="paginação de swiper"></dividir>

        <dividir aula="envoltório-do-swiper">
          <!-- Slides -->
          <dividir aula="deslizador-deslizante"><imagem fonte="img/ApacheKafka.svg"
              alt="Livro sobre apache kafka e spring boot da alura books"></dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Liderança.svg"alt="Livro sobre liderança em design da alura books">
          </dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Javascript.svg"alt="Livro sobre javascript assertivo da alurabooks">
          </dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Guia Front-end.svg"alt="Front end do Livro Guia"></dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Portugol.svg"alt="Livro sobre portugol"></dividir>
          <dividir aula="deslizador-deslizante"><imagem fonte="img/Acessibilidade.svg"alt="livro sobre acessibilidade"></dividir>
        </dividir>

        <!-- Se precisarmos de botões de navegação -->
        <dividir aula="botão-deslizador-anterior"></dividir>
        <dividir aula="botão-deslizante-próximo"></dividir>
      </dividir>

      <dividir aula="cartão">
        <!-- 1ª linha -->
        <dividir aula="card__descrição">
          <!-- 1ª coluna -->
          <dividir aula="descrição">
            <imagem fonte="img/Estrelinhas.svg"alt="Avaliação 5 estrelas">
            <h3 aula="descrição__titulo">Autora do Mês</h3>
            <h2 aula="descrição__titulo-livro">Juliana Agarikov</h2>
            <p aula="descrição__texto">Analista de sistemas e escritora, Juliana é especialista em
              Front-end.
            </p>
          </dividir>
          <!-- 2ª coluna -->
          <imagem fonte="img/Escritora.svg"aula="descrição__imagem">
        </dividir>

        <!-- 2ª linha -->
        <dividir aula="card__botões">
          <!-- 1ª coluna -->
          <o aula="botões">
            <eu aula="botões__item"><imagem fonte="img/Favoritos.svg"alt="Favoritar livro"></eu>
            <eu aula="botões__item"><imagem fonte="img/Compras.svg"alt="Adicionar no carrinho de compras"></eu>
          </o>
          <!-- 2ª coluna -->
          <um href="#"aula="botões__ancora">Saiba mais</um>
        </dividir>
      </dividir>
    </dividir>


  </seção>

  <seção aula="tópicos">
    <h2 aula="tópicos__titulo">TÓPICOS VISITADOS RECENTEMENTE</h2>
    <o aula="tópicos__lista">
      <eu aula="tópicos__item"><um href="#"aula="tópicos__link">Andróide</um></eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">Marketing Digital</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">Ágil</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">Startups</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">HTML e CSS</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">Pitão</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">OO</um>
      </eu>
      <eu aula="tópicos__item">
        <um href="#"aula="tópicos__link">Java</um>
      </eu>
    </o>
  </seção>

  <seção aula="contato">
    <dividir aula="contato__descrição">
      <h2 aula="contato__titulo">Fique por dentro das novidades!</h2>
      <p aula="contato__texto">
        Atualizações de e-books, novos livros, promoções e outros.
      </p>
    </dividir>
    <entrada tipo="e-mail"espaço reservado="        Cadastre seu e-mail"aula="contato__email">
  </seção>

  <hora/>

  <rodapé aula="rodapé">
    <h2 aula="rodapé__titulo">Grupo Alura</h2>
    <o aula="lista-rodapé">
      <eu aula="lista-rodapé__titulo">Educação</eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/Caelum.svg"alt="Logo da Caelum" />
        <um href="#"aula="lista-rodapé__link">Celum</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/CasaDoCodigo.svg"alt="Logo da Casa do Código" />
        <um href="#"aula="lista-rodapé__link">Casa do Código</um>
      </eu>
    </o>

    <o aula="lista-rodapé">
      <eu aula="lista-rodapé__titulo">Educação online</eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/Alura.svg"alt="Logo da Alura" />
        <um href="#"aula="lista-rodapé__link">Alura</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/AluraEmpresas.svg"alt="Logo da AluraParaEmpresas" />
        <um href="#"aula="lista-rodapé__link">Alura para Empresas</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/AluraLATAM.svg"alt="Logo da Alura Latam" />
        <um href="#"aula="lista-rodapé__link">Alura LATAM</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/AluraStart.svg"alt="Logo da Alura START" />
        <um href="#"aula="lista-rodapé__link">Início Alura</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/MusicDot.svg"alt="Logo da Music Dot" />
        <um href="#"aula="lista-rodapé__link">Ponto de música</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/AluraLingua.svg"alt="Logo da Alura Lingua" />
        <um href="#"aula="lista-rodapé__link">Alura Língua</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="imagem/PM3.svg"alt="Logo da PM3" />
        <um href="#"aula="lista-rodapé__link">PM3</um>
      </eu>
    </o>

    <o aula="lista-rodapé">
      <eu aula="lista-rodapé__titulo">Comunidade</eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/HipstersTech.svg"alt="Logo do Hipsters ponto Tech" />
        <um href="#"aula="lista-rodapé__link">Hipsters ponto Tech</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/ScubaDev.svg"alt="Logo do Scuba Dev" />
        <um href="#"aula="lista-rodapé__link">Desenvolvimento de mergulho</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/CamadasTech.svg"alt="Logo do Layers ponto Tech" />
        <um href="#"aula="lista-rodapé__link">Camadas ponto Tech</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/LikeABoss.svg"alt="Logo do Like a Boss" />
        <um href="#"aula="lista-rodapé__link">Que nem um chefe</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/CarreiraSemFronteira.svg"alt="Logo do Carreira sem fronteiras" />
        <um href="#"aula="lista-rodapé__link">Carreira sem fronteiras</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="img/HipstersJobs.svg"alt="Logo do Hipsters ponto empregos" />
        <um href="#"aula="lista-rodapé__link">Hipsters ponto empregos</um>
      </eu>
      <eu aula="lista-rodapé__item">
        <imagem fonte="imagem/GUJ.svg"alt="Logo da GUJ" />
        <um href="#"aula="lista-rodapé__link">GUJ</um>
      </eu>
    </o>
  </rodapé>

  <roteiro fonte="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></roteiro>
  <roteiro>
    constante deslizador = novo Deslizador(".deslizador", {
      espaçoEntre:10,
      slidesPorVisualização:3,
      paginação:{
        o:'.swiper-paginação',
        tipo:'balas',
      },
    });
  </roteiro>
</corpo>

</HTML->>
