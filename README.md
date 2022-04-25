# vscode
VScode configuration for C++ dev

- Download zsh<br>
https://github.com/ohmyzsh/ohmyzsh
- Download plugin for vscode: https://github.com/valentinocossar/vscode<br>
    <code>git clone https://github.com/valentinocossar/vscode.git ~/.zsh/vscode</code>
- Copy contents of .zshrc to your ~/.zshrc 
<code><p>source ~/.zsh/vscode/vscode.plugin.zsh<br>
export ZSH="$HOME/.oh-my-zsh"<br>
ZSH_THEME="agnoster"<br>
plugins=(<br>
  git<br>
  docker<br>
  vscode<br>
)<br>
source $ZSH/oh-my-zsh.sh</p></code>

- Add language package
apt-get install -y language-pack-en
update-locale

- In VScode
F1 > "Terminal: Select Default Shell" > zsh

- Copy contents of .vscode to .vscode
    - c_cpp_properties.json
    - cmake-kits.json
    - launch.json
    - settings.json
    - tasks.json 
