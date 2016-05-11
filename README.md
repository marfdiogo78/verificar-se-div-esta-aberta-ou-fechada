# verificar-se-div-esta-aberta-ou-fechada
verificar se div esta aberta ou fechada (Para iniciantes)

    $(".modal").on("show", function () {
      //adiciona class se tiver aberto
      $("body").addClass("modal-open");
    }).on("hidden", function () {
      //remove class se tiver fechado
      $("body").removeClass("modal-open")
    });
