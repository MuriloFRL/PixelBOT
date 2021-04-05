Pixel BOT - bRO @ Thor/Valhalla

Autor: Murilo FRL

Instalação via YouTube: https://youtu.be/NXGO-fqgY-0

Técnologias utilizadas:

Blue Eye Macro https://www.blueeye-macro.com/

GRF Editor https://rathena.org/board/files/file/2766-grf-editor/

brow edit https://github.com/Borf/browedit


O PixelBOT atualmente funciona por reconhecimento de imagem RGB
e posição dos pixels na tela do PC, ele atua procurando os monstros
teleportando, atacando, recolhendo loot, teleportando quando próximo
de portal e por fim enviando o loot via RODEX quando acima do peso.

Instalação:

	1- Criar cópia da pasta do RO.
	
	2- Instalar GRF Editor.
	
	3- Abrir o data.grf do RO no GRF Editor.
	
	4- Merge data.grf com tilemap.grf dentro da pasta grf do PixelBOT.
	
	5- Dentro da pasta grf do PixelBOT encontra-se diversos arquivos como btn_ok, btn_ok_a, etc.. arraste-os para dentro da pasta data > texture > À¯ÀúÀÎÅÍÆäÀÌ½º no grf editor.

	6- Editar mobs e drops que deseja com os arquivos da pasta atk-loot-verde/atk-loot-roxo, basta alterar o nome desses arquivos pelo nome dos mobs e substituir no GRF Editor
	7- Dentro da pasta editor-mapas edite o arquivo RO que se encontra em data/configs/RO, substitua o caminho onde estão data.grf e rdata.grf pelo caminho do seu RO.
	
	8- Abra o browedit, FILE > OPEN FROM GRF, escolha o mapa em que seu PixelBOT vai atuar depois vá em WINDOWS > TEXTURES > RO > 3 pasta abaixo de SPLEN e selecione o arquivo hu_patab02, edite os portais que você deseja evitar e após isso de um save as na pasta pixelbot-frl/mapas.
	
	9- Na pasta mapas selecione os 4 arquivos que foram gerados pelo browedit e arraste para o GRF Editor na pasta DATA.
	
	10- Recorte o arquivo UserKeys da pasta pixelbot-frl para a sua pasta do RO/savedata.
	
	11- Inicie o Blue Eye Macro, importe os macros da pasta bRO v1.0.0, edite o macro FONTE, vá até a função name e altere para o nome do seu mercador que irá receber o RODEX e salve.
	
	12- Utilizando a função pesquisar do windows procure por Alterar a resolução de exibição, modifique para 1920x1080 caso ainda não esteja e aumente para 175% a escala e layout.
	
	13- Abra os clients do RO, a cada client utilize o atalho ALT+1, ALT+2, ALT+3 para alteração do nome das janelas do RO.
	
	14- Após ter aberto todos os clients retorne para 100% a escala e layout de exibição do windows.
	
	15- Logue nas contas, arraste o inventário para o canto inferior direito, coloque o teleporte no atalho F9, ative o comando /q1 e basta ativar o macro FONTE pelo atalho ALT+0.# PixelBOT
