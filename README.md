# Pir-Gruvbox · Visual theme only / Somente o tema visual

[English](#english) · [Português](#português)

## English

This is the visual-only edition of [Gruvbox Cinnamon Completo](https://github.com/82py/gruvbox-cinnamon-completo).

Version **1.1.0-visual**, assembled from the final Gruvbox Cinnamon 1.1.0 assets. This is a theme to copy manually: application appearance, window borders, Cinnamon panel/menu styling, icons and cursor. It contains no installer, applets, extensions, services, Rain or independent-workspace automation. Existing panel layout, applet configuration and keyboard shortcuts are not applied by copying a theme.

### Copy with the file manager

1. Extract the entire TAR.GZ using Mint's Archive Manager. TAR.GZ preserves the relative symlinks used by icons and cursors.
2. Open your home folder and press **Ctrl+H** to show hidden folders. Create `.themes` and `.icons` if needed.
3. Copy the **Pir-Gruvbox** folder from this package's `themes` folder into `.themes`.
4. Copy **all three folders** from this package's `icons` folder into `.icons`: `Pir-Gruvbox-Base`, `Pir-Gruvbox-Icons` and `Pir-Gruvbox-Cursors`. The Base folder supplies most of the artwork and must stay beside Icons.
5. Copy the folders themselves, not just their contents. If one of these Pir-Gruvbox folders already exists, save it under a different name before replacing it. Existing Mint/Gruvbox themes use different names and can stay in place. No sudo is required.

Final layout:

```text
~/.themes/Pir-Gruvbox/index.theme
~/.themes/Pir-Gruvbox/cinnamon/cinnamon.css
~/.icons/Pir-Gruvbox-Base/index.theme
~/.icons/Pir-Gruvbox-Icons/index.theme
~/.icons/Pir-Gruvbox-Cursors/index.theme
```

### Select on Linux Mint Cinnamon

Open **System Settings → Themes**. If a simplified page is shown, open its advanced settings. Select:

| Setting | Choice |
| --- | --- |
| Applications / Controls | Pir-Gruvbox |
| Window borders | Pir-Gruvbox |
| Desktop / Cinnamon | Pir-Gruvbox |
| Icons | Pir-Gruvbox-Icons |
| Mouse pointer | Pir-Gruvbox-Cursors |

A cursor size of **24** matches the original preset. Close and reopen Themes if the entries do not appear; logging out and back in also refreshes applications. For regular colored category icons, the standard Cinnamon menu may offer a **Use symbolic icons for categories** option: turn it off if present. This is optional menu configuration, not an applet installation.

Manual copying follows the [Cinnamon theme instructions](https://cinnamon-spices.linuxmint.com/themes/popular/1); individual choices are available through [Mint advanced theme settings](https://www.linuxmint.com/rel_victoria_cinnamon_whatsnew.php).

### Other Mint editions and scope

The underlying visual assets were used on **Linux Mint 22.3, Cinnamon 6.6.x, X11**. The renamed visual bundle is checked for file integrity, internal links, GTK CSS and icon lookup. Other Mint releases and editions have not been validated; this does not guarantee identical appearance on every Mint.

In **MATE**, choose Pir-Gruvbox controls/window borders and the icon/cursor themes under Appearance/Customize. In **Xfce**, choose the GTK theme and icons under Appearance, Pir-Gruvbox under Window Manager, and the cursor under Mouse and Touchpad. Xfwm decorations are included. The Cinnamon panel/menu CSS applies only to Cinnamon. References: [MATE guide](https://guide.ubuntu-mate.org/) and [Xfce Appearance documentation](https://docs.xfce.org/xfce/xfce4-settings/appearance).

Some microphone, MintUpdate and other indicators may remain monochrome because the full customization uses extensions to override symbolic rendering. Those extensions are intentionally absent. Programs whose launchers use an absolute icon path, app-specific PWA IDs, Flatpak isolation, or their own themes may retain their icons/appearance. GTK4/libadwaita applications may ignore the GTK2/3 theme. Older GTK2 applications can require the Murrine/Pixmap engines from the Mint repositories.

No videos, wallpaper images, profile photo, documents or saved personal profile are included. To reproduce those choices, restore your own media and settings separately. The `SOURCES` folder preserves the original cursor source and build recipe for licensing; it is not copied into `.themes` or `.icons` and is not needed for manual installation.

### Remove

Select another theme, icon set and cursor first. Then delete only the four Pir-Gruvbox folders listed above. This does not remove or reset your original themes. Keep any backup made before replacing a previous copy.

See [credits and licenses](CREDITS.md). Provided **as is**, without warranty; third-party licenses continue to apply.

---

## Português

Esta é a edição somente visual do [Gruvbox Cinnamon Completo](https://github.com/82py/gruvbox-cinnamon-completo).

Versão **1.1.0-visual**, montada com as artes finais do Gruvbox Cinnamon 1.1.0. É um tema para copiar manualmente: aparência dos aplicativos, bordas de janelas, visual do painel/menu Cinnamon, ícones e cursor. Não contém instalador, applets, extensões, serviços, Rain ou automação de espaços independentes. Copiar um tema não aplica posições do painel, configurações de applets ou atalhos de teclado.

### Copiar pelo gerenciador de arquivos

1. Extraia o TAR.GZ inteiro pelo Gerenciador de Arquivos Compactados do Mint. Esse formato conserva os links relativos dos ícones e cursores.
2. Abra sua pasta pessoal e pressione **Ctrl+H** para mostrar as pastas ocultas. Crie `.themes` e `.icons` caso não existam.
3. Copie a pasta **Pir-Gruvbox**, que está dentro de `themes` neste pacote, para `.themes`.
4. Copie **as três pastas** de `icons` para `.icons`: `Pir-Gruvbox-Base`, `Pir-Gruvbox-Icons` e `Pir-Gruvbox-Cursors`. A pasta Base fornece a maior parte dos desenhos e precisa ficar ao lado de Icons.
5. Copie as pastas inteiras, sem despejar seu conteúdo diretamente em `.themes` ou `.icons`. Se já existir alguma dessas pastas Pir-Gruvbox, guarde uma cópia com outro nome antes de substituir. Os temas originais do Mint/Gruvbox têm nomes diferentes e podem continuar no lugar. Não precisa usar sudo.

A estrutura final deve ficar assim:

```text
~/.themes/Pir-Gruvbox/index.theme
~/.themes/Pir-Gruvbox/cinnamon/cinnamon.css
~/.icons/Pir-Gruvbox-Base/index.theme
~/.icons/Pir-Gruvbox-Icons/index.theme
~/.icons/Pir-Gruvbox-Cursors/index.theme
```

### Selecionar no Linux Mint Cinnamon

Abra **Configurações do Sistema → Temas**. Se aparecer uma página simplificada, abra as configurações avançadas. Selecione:

| Opção | Tema |
| --- | --- |
| Aplicativos / Controles | Pir-Gruvbox |
| Bordas das janelas | Pir-Gruvbox |
| Área de trabalho / Cinnamon | Pir-Gruvbox |
| Ícones | Pir-Gruvbox-Icons |
| Ponteiro do mouse | Pir-Gruvbox-Cursors |

O tamanho **24** do cursor corresponde ao preset original. Se os temas não aparecerem, feche e reabra Temas; sair da sessão e entrar novamente também atualiza os programas. Para categorias coloridas com ícones regulares, o menu padrão do Cinnamon pode oferecer **Usar ícones simbólicos nas categorias**: desative essa opção, caso exista. Isso é uma configuração opcional do menu existente, não a instalação de um applet.

A cópia manual segue as [instruções de temas do Cinnamon](https://cinnamon-spices.linuxmint.com/themes/popular/1); as escolhas individuais ficam nas [configurações avançadas de temas do Mint](https://www.linuxmint.com/rel_victoria_cinnamon_whatsnew.php).

### Outras edições do Mint e alcance

As artes de origem foram usadas no **Linux Mint 22.3, Cinnamon 6.6.x, X11**. Este pacote visual com nomes próprios tem conferência de integridade, links internos, CSS GTK e localização dos ícones. Outras versões e edições do Mint não foram validadas; não há garantia de aparência idêntica em todo Mint.

No **MATE**, escolha controles/bordas Pir-Gruvbox e os ícones/cursor em Aparência/Personalizar. No **Xfce**, selecione o tema GTK e os ícones em Aparência, Pir-Gruvbox no Gerenciador de Janelas e o cursor em Mouse e Touchpad. As bordas Xfwm acompanham o pacote. O CSS do painel/menu Cinnamon só se aplica ao Cinnamon. Referências: [guia do MATE](https://guide.ubuntu-mate.org/) e [documentação de Aparência do Xfce](https://docs.xfce.org/xfce/xfce4-settings/appearance).

Alguns indicadores de microfone, MintUpdate e outros podem continuar monocromáticos: a personalização completa usa extensões para mudar a renderização simbólica, e elas não acompanham este pacote. Aplicativos com caminho absoluto para o ícone, PWAs com identificadores próprios, isolamento Flatpak ou tema próprio podem manter sua aparência. Aplicativos GTK4/libadwaita podem ignorar o tema GTK2/3. Programas GTK2 antigos podem precisar dos mecanismos Murrine/Pixmap dos repositórios do Mint.

Não inclui vídeos, imagens de fundo, foto, documentos nem um perfil pessoal salvo. Para recuperar essas escolhas, restaure suas mídias e configurações separadamente. A pasta `SOURCES` conserva o código-fonte e a receita de compilação originais do cursor por causa de sua licença; ela não é copiada para `.themes` ou `.icons` e não é necessária para a instalação manual.

### Remover

Primeiro selecione outro tema, conjunto de ícones e cursor. Depois apague somente as quatro pastas Pir-Gruvbox listadas acima. Isso não remove nem redefine os temas originais. Conserve a cópia de segurança feita antes de substituir uma versão anterior.

Veja [créditos e licenças](CREDITS.md). Fornecido **no estado em que se encontra (as is)**, sem garantias; as licenças de terceiros continuam válidas.
