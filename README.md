### Resumo

Esta modificação foi desenvolvida no formato OCMod (substituto do VQMod), e incrementa a possibilidade de instalar extensões sem utilizar o FTP no OpenCart, porém, mantém a função FTP funcionando.

Caso deseje doar um valor para contribuir com este trabalho continuo e sempre gratuito, clique no botão abaixo:

[![alt tag](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7G9TR9PXS6G5J)

### Instalação

 1. Na administração da loja acesse o menu Extensions->Extension Installer (Extensões->Instalador).
 2. Na página do instalador, clique no botão Upload e selecione o arquivo 'instalador-sem-ftp.ocmod.xml' (que você baixou deste repositório), e aguarde a conclusão da instalação automática.
 3. Após a instalação, acesse o menu Extensions->Modifications (Extensões->Modificações) e clique no botão Refresh (Atualizar), para que a modificação instalada seja incrementada na loja.
 4. Para desinstalar a modificação, acesse o menu Extensions->Modifications (Extensões->Modificações) e selecione a modificação com o nome 'Instalador sem FTP', e clique no botão Delete (Excluir), depois no botão Refresh (Atualizar).

### Dúvidas

O OCMod (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMod, para mais informações sobre o OCMod, segue o link:

https://github.com/opencart/opencart/wiki/Modification-System

O único arquivo alterado virtualmente através do OCMod é o arquivo abaixo:

admin/controller/extension/installer.php

### Como contribuir

 1. Faça um Fork do projeto e edite os arquivos que desejar.
 2. Faça um Pull para que suas sugestões de melhorias sejam avaliadas e aceitas, caso aprovadas.
 3. Abra uma Inssue com sua dúvida ou sugestão.

### Licença

[GNU General Public License version 3 (GPLv3)](https://github.com/opencartbrasil/instalador-sem-ftp
/blob/master/LICENSE)
