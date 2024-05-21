Anna Bella Oficial - README
Visão Geral
Bem-vindo ao repositório do site "Anna Bella Oficial". Este site é uma página pessoal que fornece informações sobre Anna Bella, incluindo biografia, campanhas publicitárias e informações de contato. A estrutura do site é construída utilizando HTML e CSS.

Estrutura do Projeto
O projeto é composto pelos seguintes arquivos e diretórios:

css
Copiar código
Anna Bella Oficial/
│
├── index.html
├── biografia.html
├── campanha.html
├── contato.html
├── estilo.css
├── img/
│   └── capa.png
└── README.md
Descrição dos Arquivos
index.html: Página inicial do site com informações gerais sobre Anna Bella.
biografia.html: Página contendo a biografia de Anna Bella.
campanha.html: Página detalhando as campanhas publicitárias de Anna Bella.
contato.html: Página com informações de contato.
estilo.css: Arquivo CSS responsável pela estilização do site.
img/capa.png: Imagem de capa utilizada na página inicial.
Código HTML Principal
Abaixo está o código HTML principal contido no arquivo index.html:

html
Copiar código
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anna Bella Oficial</title>
    <link rel="stylesheet" href="estilo.css" type="text/css">
</head>
<body>
    <center>
    <div id="principal">
        <img src="img/capa.png" width="680px">
        <br>
        <br>
        <div id="menu">
            <a href="index.html">HOME</a> | 
            <a href="biografia.html">BIOGRAFIA</a> | 
            <a href="campanha.html">CAMPANHAS PUBLICITÁRIAS</a> | 
            <a href="contato.html">CONTATO</a> 
        </div>
        <br>
        <div id="conteudo">
            <h1>Sobre Anna Bella</h1>
            <p>
                Lorem Ipsum is simply dummy text of the printing and 
                typesetting industry. Lorem Ipsum has been the industry's
                standard dummy text ever since the 1500s, when an unknown
                printer took a galley of type and scrambled it to make a 
                type specimen book. It has survived not only five centuries,
                but also the leap into electronic typesetting, 
                remaining essentially unchanged. 
                It was popularised in the 1960s with the release of 
                Letraset sheets containing Lorem Ipsum passages, and more
                recently with desktop publishing software
                like Aldus PageMaker including versions of Lorem Ipsum.
            </p>
        </div> <!--fim do conteúdo-->
        <div id="rodape">
            <h4>Todos os direitos reservados</h4>
            <h5>Por: Caio Machado</h5>
        </div>
    </div>
    </center>
</body>
</html>
Estilo CSS
O arquivo estilo.css contém a estilização básica do site. Certifique-se de ajustar as regras de estilo conforme necessário para atender às suas necessidades específicas.

Como Usar
Clone o repositório:

bash
Copiar código
git clone https://github.com/seu-usuario/anna-bella-oficial.git
Navegue até o diretório do projeto:

bash
Copiar código
cd anna-bella-oficial
Abra o arquivo index.html em seu navegador:
Você pode simplesmente arrastar e soltar o arquivo no seu navegador ou usar uma extensão de servidor local, como Live Server no VS Code.

Contribuições
Contribuições são bem-vindas! Se você tiver sugestões ou encontrar problemas, sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais detalhes.

Autor
Desenvolvido por Caio Machado.

Nota: Este README foi criado para fornecer uma visão geral do projeto e instruções básicas sobre como usá-lo. Ajuste as informações conforme necessário para refletir com precisão os detalhes e requisitos do seu projeto específico.
