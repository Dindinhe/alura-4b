sarah chalegra- 3C / 06/11/2024
@@ -101,7 +101,7 @@ <h2 class="carrossel__titulo">Novos lançamentos</h2>
        <!-- Additional required wrapper -->
        <!-- Additional required wrapper -->
        <div class="swiper-wrapper">
        <div class="swiper-wrapper">
          <!-- Slides -->
          <!-- Slides -->
          <div class="swiper-slide"><img src="img/Apachekafka.svg"
          <div class="swiper-slide"><img src="img/ApacheKafka.svg"
              alt="Livro sobre apache kafka e spring boot da alura books"></div>
              alt="Livro sobre apache kafka e spring boot da alura books"></div>
          <div class="swiper-slide"><img src="img/Liderança.svg"
          <div class="swiper-slide"><img src="img/Liderança.svg"
              alt="Livro sobre liderança em design design da alura books"></div>
              alt="Livro sobre liderança em design design da alura books"></div>
@@ -245,7 +245,7 @@ <h2 class="contato__titulo">Fique por dentro das novidades!</h2>
        Atualizações de e-books, novos livros, promoções e outros.
        Atualizações de e-books, novos livros, promoções e outros.
      </p>
      </p>
    </div>
    </div>
    <input type="email" placeholder="         Cadastre seu e-mail" class="contato__email" />
    <input type="email" placeholder="        Cadastre seu e-mail" class="contato__email">
  </section>
  </section>


  <hr />
  <hr />
@@ -335,8 +335,8 @@ <h2 class="rodapé__titulo">Grupo Alura</h2>
      spaceBetween: 10,
      spaceBetween: 10,
      slidesPerView: 3,
      slidesPerView: 3,
      pagination: {
      pagination: {
        el: ".swiper-pagination",
        el: '.swiper-pagination',
        type: "bullets",
        type: 'bullets',
      },
      },
    });
    });
  </script>
  </script>
‎styles/contato.css
+2
-4
Original file line number	Original file line	Diff line number	Diff line change
@@ -32,11 +32,10 @@
.contato__email::placeholder {
.contato__email::placeholder {
    font-family: var(--fonte-principal);
    font-family: var(--fonte-principal);
    color: var(--azul);
    color: var(--azul);
    background: url("../img/email.svg") no-repeat 5%;
    background: url("../img/Email.svg") no-repeat 5%;
    padding-left: 5em;
    padding-left: 2em;
}
}


@media screen and (min-width: 1024px) {
@media screen and (min-width: 1024px) {
    .contato {
    .contato {
        display: flex;
        display: flex;
@@ -58,7 +57,6 @@
    }
    }
}
}


@media screen and (min-width: 1728px) {
@media screen and (min-width: 1728px) {
    .contato {
    .contato {
        padding: 3em 20vw;
        padding: 3em 20vw;

        ..........................................................................................................................................................

        
