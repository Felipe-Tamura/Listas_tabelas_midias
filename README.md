<h1 align="center">Listas, tabelas e mídia</h1>

Adicionando alguns projetos e aprendizagens que estou desenvolvendo na faculdade de Análise e Desenvolvimento de Sistemas da Estácio. Aqui mostro um pouco sobre Listas, tabelas e mídias, espero que gostem! 

 **[Listas](#listas)**

- [Ordenadas](#ordenadas)
- [Não ordenadas](#não-ordenadas)
- [Definição](#definição)

**[Tabelas](#tabelas)**

- [Estrutura das tabelas](#estrutura-das-tabelas)

**[Midias](#mídia)**

- [Vídeo e áudio](#vídeo-e-áudio)

## Listas
### Ordenadas
- &lt;ol&gt; - Tag container. Usada para representar dados com ordenação numérica;
- &lt;li&gt; - Tag de item.

### Não ordenadas
- &lt;ul&gt; - Tag container. Usada quando não há ordenação nos dados;
- &lt;li&gt; - Tag de item.

### Definição
- &lt;dl&gt; - Tag container. Usada quando precisamos listar itens e atribuir descrição.
- &lt;dt&gt; - Tag de item.
- &lt;dd&gt; - Tag de descrição.

<p align="center"><img src="src/listas.png" alt="Imagem de exemplo de listas"></p>

## Tabelas
### Estrutura das tabelas
- &lt;table&gt; - Container principal da tabela;
- &lt;tr&gt; - Representa a linha, sendo composta por tag de coluna;
- &lt;td&gt; - Representa a coluna, inserida dentro da tag de linha;
- &lt;th&gt; - Representa a coluna, usada para exibir o titulo da coluna, assim com a tag &lt;&gt; é usada dentro da tag de linha, possuindo estilo próprio e função semântica;
- &lt;thead&gt; - Armazena o cabeçalho da tabela, sendo composta por linhas e colunas. Possuindo semântica em termo de estruturação de conteúdo;
- &lt;tfood&gt; - Rodapé da tabela, possuindo também função semântica em termo de estruturação.

<p align="center"><img src="src/tabela.png" alt="Imagem de exemplo de tabela"></p>

## Mídias
### Vídeo e Áudio
- &lt;video&gt; - Usada para apresentar um vídeo;
- &lt;audio&gt; - Usada para apresentar um áudio.

Assim como na tag de imagem, os atributos nestas tags são de suma importância, são eles:
- src - Usado para adicionar o caminho/link do arquivo (audio, video ou imagem);
- alt - Usado para caso a midia não seja carregada no navegador caso o mesmo não possua suporte para tal midia;
- controls - Controle de ações de midia (audio e video);
- autoplay - Autoexplicativo. Mais usado em audios;
- loop - Também autoexplicativo. Mais usado em audios.

<p align="center"><img src="src/midias.png" alt="Imagem de exemplo de midias"></p>