# Команды конфигурации Git

## git config

Сотни вещей в Git работают без всякой конфигурации, используя параметры по умолчанию. Для большинства из них вы можете задать иные умолчания, либо вовсе использовать собственные значения. Это включает в себя целый ряд настроек, начиная от вашего имени и заканчивая цветами в терминале и вашим любимым редактором. Команда ```config``` хранит и читает настройки в нескольких файлах, так что вы можете задавать значения глобально или для конкретных репозиториев.

```
git config
```
---
## настройка git под конкретный редактор

```
git config core.editor
```
_таблица со списком команд настройки **git** в зависимости от редактора_

| Редактор                                                      | Команда                                                                                                                     |
|---------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| Atom                                                          | ```git config --global core.editor "atom --wait"```                                                                         |
| BBEdit (Mac, with command line tools)                         | ```git config --global core.editor "bbedit -w"```                                                                           |
| Emacs                                                         | ```git config --global core.editor emacs```                                                                                 |
| Gedit (Linux)                                                 | ```git config --global core.editor "gedit --wait --new-window"```                                                           |
| Gvim (Windows 64-bit)                                         | ```git config --global core.editor "'C:\Program Files\Vim\vim72\gvim.exe' --nofork '%*'"```                                 |
| Kate (Linux)                                                  | ```git config --global core.editor "kate"```                                                                                |
| nano                                                          | ```git config --global core.editor "nano -w"```                                                                             |
| Notepad (Windows 64-bit)                                      | ```git config core.editor notepad```                                                                                        |
| Notepad++ (Windows 64-bit)                                    | ```git config --global core.editor "'C:\Program Files\Notepad\notepad.exe' -multiInst -notabbar -nosession -noPlugin" ```   |
| Scratch (Linux)                                               | ```git config --global core.editor "scratch-text-editor"```                                                                 |
| Sublime Text (macOS)                                          | ```git config --global core.editor "/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl --new-window --wait"``` |
| Sublime Text (Windows 64-bit)                                 | ```git config --global core.editor "'C:\Program Files\Sublime Text 3\sublime_text.exe' -w"```                               |
| TextEdit (macOS)                                              | ```git config --global --add core.editor "open -W -n"```                                                                    |
| Textmate                                                      | ```git config --global core.editor "mate -w"```                                                                             |
| Textpad (Windows 64-bit)                                      | ```git config --global core.editor "'C:\Program Files\TextPad 5\TextPad.exe' -m```                                          |
| Vim                                                           | ```git config --global core.editor "vim"```                                                                                 |
| Visual Studio Code                                            | ```git config --global core.editor "code --wait"```                                                                         |
| VSCodium (Free/Libre Open Source Software Binaries of VSCode) | ```git config --global core.editor "codium --wait"```                                                                       |
| WordPad                                                       | ```git config --global core.editor '"C:\Program Files\Windows NT\Accessories\wordpad.exe"'"```                              |

---

## git help
Команда ```git help``` служит для отображения встроенной документации Git о других командах. И хотя мы приводим описания самых популярных команд в этой главе, полный список параметров и флагов каждой команды доступен через ```git help <command>```.

```
git help
```