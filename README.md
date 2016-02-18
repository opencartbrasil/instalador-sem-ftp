### Resumo

Esta modificação foi desenvolvida no formato OCMod (substituto do VQMod), e incrementa a possibilidade de instalar extensões sem utilizar o FTP no OpenCart, porém, mantém a função FTP funcionando.

Uma das grandes vantagens desta modificação é permitir que, ao montar sua loja em ambiente local (no seu pc ou servidor local), você possa instalar extensões através do Instalador de Extensões do OpenCart, sem a necessidade da utilização do FTP.

Caso deseje doar um valor para contribuir com este trabalho continuo e sempre gratuito, clique no botão abaixo:

[![alt tag](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7G9TR9PXS6G5J)

### Instalação

 1. Baixe a modificação no link: https://github.com/opencartbrasil/instalador-sem-ftp/archive/master.zip
 2. Ao baixar, descompacte o conteúdo do arquivo zip e localize o arquivo "instalador-sem-ftp.ocmod.xml".
 3. Na administração da loja acesse o menu Extensions->Extension Installer (Extensões->Instalador).
 4. Na página do instalador, clique no botão Upload e selecione o arquivo 'instalador-sem-ftp.ocmod.xml' (que você baixou deste repositório), e aguarde a conclusão da instalação automática.
 5. Após a instalação, acesse o menu Extensions->Modifications (Extensões->Modificações) e clique no botão Refresh (Atualizar), para que a modificação instalada seja incrementada na loja, lembrando que não é o botão "Atualizar" do navegador, e sim o botão "Atualizar" na cor azul ao lado do botão laranja e vermelho na tela do próprio OpenCart.

### Configuração

Acesse a administração da loja e vá no menu System->Settings (Configurações->Lojas), clique no botão Edit (Editar), clique na ba FTP, localize o campo "Enable FTP" (Ativar FTP?), marque a opção "No" (Não), e clique no botão Save (Salvar).

### Desinstalação

Para desinstalar a modificação, na administração da loja, acesse o menu Extensions->Modifications (Extensões->Modificações) e selecione a modificação com o nome 'Instalador sem FTP', depois clique no botão Delete (Excluir), e no botão Refresh (Atualizar).

### Atualização

Acesse a administração da loja e execute o procedimento de Desinstalação, depois execute o procedimento de Instalação.

### Dúvidas

O OCMod (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMod, para mais informações sobre o OCMod, segue o link:

https://github.com/opencart/opencart/wiki/Modification-System

### O arquivo alterado virtualmente através do OCMod é:

admin/controller/extension/installer.php

### Como contribuir

 1. Faça um Fork do projeto e edite os arquivos que desejar.
 2. Faça um Pull para que suas sugestões de melhorias sejam avaliadas e aceitas, caso aprovadas.
 3. Abra uma Inssue com sua dúvida ou sugestão.

### Licença

[GNU General Public License version 3 (GPLv3)](https://github.com/opencartbrasil/instalador-sem-ftp
/blob/master/LICENSE)
