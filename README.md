# macOS Dotfiles
(Se você está procurando os dotfiles do meu Manjaro i3 Community Edition, eles estão [aqui](https://github.com/guiemi/i3wm-dotfiles).)

![](https://raw.githubusercontent.com/guiemi/mac-dotfiles/master/.screenshots/dotfiles-iterm.png)

## O que são Dotfiles?

Como o nome já sugere, dotfiles são **arquivos** que têm como característica principal serem nomeados com um ponto  (**dot** em inglês). O ponto faz com que esses arquivos fiquem escondidos, evitando, assim, alterações ou exclusões acidentais. Outra característica deles é que eles geralmente são criados na pasta **home** do seu sistema de arquivos. O `.bashrc` é certamente o dotfile mais popular atualmente, pois ele é responsável pelas configurações do Bash (*Bourne-again shell*).

Usuários de sistemas *Unix-like* utilizam dotfiles organizados em repositórios (como no GitHub, GitLab ou BitBucket, por exemplo) para manterem um esquema de versionamento de seus arquivos de configuração e um backup simples de ser ativado em caso de acidentes ou em máquinas novas. Outra utilidade de disponibilizar em repositórios públicos esses arquivos e screenshots é inspirar outros usuários a fazerem o mesmo e ampliar o conhecimento sobre essa técnica simples mas que poupa tempo e dor de cabeça de muitas pessoas diariamente.

## Saiba mais sobre Dotfiles

Para construir este README dos meus dotfiles, me inspirei basicamente nos do Derek Taylor e nos dotfiles que eu mesmo construí, só que para o **Manjaro Linux i3wm**. No site [dotfiles.github.io](https://dotfiles.github.io/) tem uma lista enorme de outros para você se inspirar (ou simplesmente sair usando!, pois é possível usar a configuração feita por outra pessoa através de um script de [bootstrap](https://stackoverflow.com/a/1254561)).

* Link para os dotfiles do Derek: https://gitlab.com/dwt1/dotfiles/tree/master.
* Link para os meus dotfiles do Linux: https://github.com/guiemi/i3wm-dotfiles

## Vim

![dotfiles-vimrc](https://github.com/guiemi/mac-dotfiles/blob/master/.screenshots/dotfiles-vimrc.png)

O Vim (acrônimo de Vi Improved) é um editor de texto keyboard-driven lançado em 1992 como um fork do Vi (acrônimo de Visual Interface). 

## iTerm

### Tema: Broadcast

![iterm-broadcast-theme](https://github.com/guiemi/mac-dotfiles/blob/master/.screenshots/dotfiles-nord-theme-iterm.png)

## Visual Studio Code (VSCode)

![](https://github.com/guiemi/mac-dotfiles/blob/master/.screenshots/dotfiles-vscode.png)

* Tema: [Plastic](https://marketplace.visualstudio.com/items?itemName=will-stone.plastic)
* Keymaps:
* Enhancement para HTML e CSS:
* Colorizador de parênteses:
* Terminal interno:
* Mostrador de cores em códigos de cores:
* Pacote de idioma:
* Plugin para Python:
* Pacote de ícones


## Localização de cada arquivo de configuração

(Pois alguns têm o mesmo  nome, então navegar por entre as pastas pode não ser muito intuitivo.)

* [Neofetch](https://github.com/guiemi/mac-dotfiles/blob/master/.config/neofetch/config.conf)
* [Git](https://github.com/guiemi/mac-dotfiles/blob/master/.gitconfig)
* [Vim](https://github.com/guiemi/mac-dotfiles/blob/master/.vimrc)
* [Shell (ZSH)](https://github.com/guiemi/mac-dotfiles/blob/master/.zshrc)
* [Terminal (iTerm2)](https://github.com/guiemi/mac-dotfiles/blob/master/com.googlecode.iterm2.plist)
* Visual Studio Code
  *  [snippets](https://github.com/guiemi/mac-dotfiles/blob/master/snippets/python.json)
  * [keybindings](https://github.com/guiemi/mac-dotfiles/blob/master/keybindings.json)
  * [configurações](https://github.com/guiemi/mac-dotfiles/blob/master/settings.json)

## Bibliografia

* **Tutorial**: Manage Dotfiles With a Bare Git Repository (Harfang's Perch): https://harfangk.github.io/2016/09/18/manage-dotfiles-with-a-git-bare-repository.html
* **Dotfiles**: Derek Taylor's Dotfiles (GitLab): https://gitlab.com/dwt1/dotfiles
* **Tutorial**: The best way to store your dotfiles: A bare Git repository (Atlassian): https://www.atlassian.com/git/tutorials/dotfiles
* **Video tutorial**: [Git Bare Repository - A Better Way To Manage Dotfiles (DistroTube)](https://www.youtube.com/watch?v=tBoLDpTWVOM)