# Clique_me_botao
EventsClick

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
 <body>
  <button>Clique me</button>
  <a href="https://github.com/isaquefragazani"> Clique me </a>
  <script>
    
    const button = document.querySelector("button")
    button.addEventListener("click", () => {
        console.log("clicou no botão")
    })

    const hyperlink = document.querySelector("a")
    hyperlink.addEventListener("clickk", (event) => {
        event.preventDefault()
        console.log("Clicou no meu hyperlink")

    })

  </script>
 </body>
</html>
