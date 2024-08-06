# 1) Organizando ícones nas redes sociais
Imagine que você está trabalhando em um projeto pessoal onde deseja incluir links para suas redes sociais com ícones correspondentes. Você já tem um link para o GitHub com um ícone, mas precisa adicionar outros dois: LinkedIn e Twitch. Utilize o seguinte trecho de código HTML como ponto de partida:

<main class="apresentacao">
    <section class="apresentacao__conteudo">
        <div class="apresentacao__links">
            <h2 class="apresentacao__links__subtitulo">Acesse minhas redes:</h2>
            <a class="apresentacao__links__link" href="https://github.com/seunome">
                <img src="./assets/github.png">
                Github
            </a>
            <!-- Adicione os links do LinkedIn e Twitch aqui -->
        </div>
    </section>
    <img src="./assets/imagem.png" alt="Foto da Joana Santos programando">
</main>
<footer></footer>
</body>
</html>

# 2) Centralizando ícones e textos nos botões
Imagine que você está trabalhando em um projeto de site onde precisa alinhar ícones de redes sociais com seus respectivos textos dentro de botões. O desafio é utilizar Flexbox para centralizar tanto o ícone quanto o texto dentro dos botões. Comece acessando o arquivo style.css e encontre a classe .apresentacao__links__link. Sua tarefa é adicionar as propriedades display: flex, justify-content: center e gap: 16px nesta classe, respeitando a ordem e posição corretas entre as outras propriedades existentes.

# 3) Espaçamento entre ícones e textos
Neste desafio, você precisa ajustar o espaçamento entre os ícones e os textos dentro dos botões de redes sociais no mesmo projeto do site. Primeiro, consulte o Figma do projeto para identificar o valor exato do espaçamento em pixels entre o ícone e o texto. Depois, volte ao arquivo style.css e adicione a propriedade gap com o valor encontrado no Figma à classe .apresentacao__links__link. Certifique-se de que o gap esteja posicionado corretamente dentro da declaração da classe.

# 4) Personalizando o efeito Hover
Você está desenvolvendo uma página de portfólio e quer criar um efeito visual atraente. O objetivo é fazer com que, ao passar o mouse sobre os botões, eles se destaquem com uma borda azul. Para isso, utilize a classe .apresentacao__links__link já existente no seu código CSS. Seu desafio é adicionar o efeito Hover a essa classe, fazendo com que a borda do botão mude para a cor azul (#0000FF) quando o cursor passar sobre ele.

# 5) Alterando o cursor e o fundo dos botões
Na sua página de portfólio, você observou que, ao passar o mouse sobre um botão, o cursor se transforma em uma mão com o indicador levantado. Além disso, você deseja que o fundo do botão mude para um tom de preto levemente mais claro (#272727) ao passar o mouse. Seu desafio é editar a classe .apresentacao__links__link:hover no seu arquivo CSS para alterar o cursor para o estilo 'pointer' e mudar a cor de fundo do botão ao passar o mouse sobre ele.