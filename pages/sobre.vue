<template>
    <div id="body">
        <h2>Os Gatos</h2>

        <p>Os gatos são os animais de estimação mais populares de todo o mundo. Apesar de domesticados, os gatos partilham todas as características dos felinos selvagens dos quais são parentes: são fortes, ágeis, dotados de grandes reflexos, sentidos apurados e instinto de caça, além de possuírem a personalidade vincada e individualista que lhes é característica.</p>
        <p>São brincalhões, muito independentes, curiosos e conseguem ser teimosos, mas são também extremamente amigáveis e afetivos: um dos gestos mais carinhosos dos gatos é a famosa turrinha, que dão entre si e aos seus donos. Outro sinal de afeição é o não menos famoso ronronar.</p>
        <h2>9 curiosidades sobre os gatinhos</h2>
        <ul id="curiosidades">
            <li>Em média um gato passa 2/3 do dia a dormir. Isso significa que em 9 anos de vida, apenas está acordado 3 anos.</li>
            <li>Os gatos não saboreiam o doce.</li>
            <li>Quando um gato persegue uma presa, ao contrário de um cão ou humano, mantém a cabeça sempre para baixo.</li>
            <li>As bolas de pelo que vomitamos chamam-se egagropilos.</li>
            <li>As gatas tendem a ser dextras, enquanto os gatos tendem a ser maioritariamente esquerdinos.</li>
            <li>Um gato faz cerca de 100 sons diferentes, enquanto um cão faz cerca de 10.</li>
            <li>O cérebro de um gato é biologicamente mais similar ao de um humano do que o cérebro de um cão. Ambos, humanos e gatos, têm uma região idêntica no cérebro responsável pelas emoções.</li>
            <li>Existem mais de 500 milhões de gatos domésticos no mundo, e aproximadamente 40 raças reconhecidas.</li>
            <li>O gato doméstico mais antigo foi encontrado numa sepultura no Chipre com mais de 9000 anos.</li>
        </ul>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Concert+One&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
  *{
    padding: 0;
    border: 0;
    margin: 0;
    font-family: "Roboto", sans-serif;
    font-weight: 300;
    font-style: normal;
  }
  #body{
    padding: 25px;
    display: flex;
    flex-direction: column;
    gap: 25px;
    
  }
  #curiosidades{
    display: flex;
    flex-direction: column;
    list-style: decimal;
  }

</style>