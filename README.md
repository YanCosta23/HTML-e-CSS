<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/leme.ico" type="image/x-icon">
    <title>Teste</title>
    <style>
    mark {
        background-color: blue;
    }
     </style>


</head>
<body>
    <h1>Testando carga e imagens</h1>
    <p>Abaixo você vai ver uma imagem que está na mesma pasta</p>
    <img src="imagens/lemeforense.png" alt="Logo leme">
    <h2>Principais Formatações</h2>
    <p>Nesta frase, temos um <strong>Termo em destaque</strong>usando a tag Strong</p>
    <p>Nesta frase, temos um <em>Termo em itálico</em>, usando a tag EM</p>
    <h2>Texto Marcado</h2>
    <P>Podemos criar também <MARK>um texto marcado </MARK>usando a tag MARK </P>
    <p>E no outro parágrafp, temos <mark>outro texto marcado</mark> no final</p>
    <h2>Terto Grande e Pequeno</h2>
    <P><big>Temos aqui uma frase grande</big>, <small>e aqui uma frase menor</small></P>
    <h2>Texto Deletado</h2>
    <p>Podemos <del>marcar um texto como excluído</del> para indicar que ele deve ser lido, mas não considerado</p>
    <h2>Texto Inserido</h2>
    <p>`podemos <ins>marcar um texto inderido</ins> para dar ênfase e indicar que ele foi adicionado depois</p>
    <h2>Texto Sobrescrito</h2>
    <p>Para inderir coisas do tipo x<sup>2</sup>+3</p>
    <h2>Texto subscrito</h2>
    <p>Para inserir coisas do tipo h<sub>2</sub>0</p>

    <h1>Código Fonte</h1>
    <p><code>O comando document.getElementByid('teste') é escrito em linguagem JavaScript</code></p>
    <h2>Citações</h2>
    <p>Como diria o pai de um amigo: <q>O computador é um burro muito rápido</q></p>

    <h1>Trabalhando com Listas</h1>
    <h2>Listas Ordenadas</h2>
    <ol type="I" >  <!-- 1  A  a I i-->
        <li>Acordar
        <li>Ligar para o João
        <li>Tomar café
        <li>Escovar os dentes
        <li>Ir para a faculdade
        <li>Almoçar
        <li>Ir para o trabalho
        <li>Voltar para casa
        <li>Jantar</li>
        <li>Dormir</li>
    </ol>

    <H2>Listas não Ordenadas</H2>
    <ul type="square">  <!-- disc circle square-->
        <li>Pão</li>
        <li>Leite</li>
        <li>Tomate</li>
        <li>Alfaçe</li>
        <li>Manteiga</li>
        <li>Arroz</li>
        <li>Feijão</li>


    </ul>
    
    <h2>Minhas linguagens favoritas</h2>
    <ol>
        <li>Antigas</li>
        <ol type="a">
            <li>Clipper</li>
            <li>Visual Basic</li>
            <li>Fortran</li>
            <li>Delphi</li>
        </ol>
        <li>Novas</li>
        <ol type="a" start="5">
            <li>PHP</li>
            <li>Python</li>
            <li>JavaScript</li>
            <li>Kotlin</li>
        </ol>
    </ol>
    <H2>Meus jogos favoritos</H2>
    <ol>
        <li>NES</li>
        <ul type="square">
            <li>Mario Bros</li>
            <ul type="circle">
                <li>Mario Bross 3</li>
                <li>Mario: Lost Levels</li>
            </ul>
            <li>Ninja Gaiden</li>
        </ul>

        <li>SNES</li>
        <ul type="square">
            <li>Mario</li>
            <li>Donkey Kong</li>
        </ul>
        <li>PlayStation</li>
        <ul type="square">
            <li>Final Fantasy</li>
            <li>Castlevania</li>
        </ul>
    </ol>

    <h2>Lista de Definições</h2>
    <dl>
        <dt>HTML</dt>
        <dd>Linguagem de marcação para a criação do contepudo de um site</dd>
        <dt>CSS</dt>
        <dd>Linguagem de marcação para a criação do design de um sie.</dd>
        <dt>JavaScript</dt>
        <dd>Linguagem de programação para a interatividade de um site.</dd>

    </dl>
</body>
</html>
