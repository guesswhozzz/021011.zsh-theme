# 021011.zsh-theme — theme and settings for Z shell

## **Preview**

![item zsh prompt](https://github.com/guesswhozzz/guezwhoz-scheme/blob/main/demos/zsh-theme-demo-min.png?raw=true)

---

## **Overview**
### Theme includes prompt settings, vsc_info settings, and zsh completion settings.
### **Prompt**

Essentially, the shell prompt is split into three separate lines. The first line helps to visually 
divide the previous output from the next prompt. The second line contains all about path and
split into three **path segments**. The third is the input line. 

### **Path segments**

- **ssh connection** - The badge indicates whether the ssh connection is currently established
- **directory** - Current working directory
- **vsc status line** - This segment displays all about the status of the branch in the working directory

---

## **Installation**

For Installation you need git

### **Manual**

*TBA*

### **Oh My Zsh**

1. Cloning the repo

```shell
% git clone https://github.com/guesswhozzz/021011.zsh-theme ~/021011-tools
```

2. Creating a symbolic link to oh-my-zsh's theme folder

```shell
% ln -s ~/021011-tools/021011.zsh-theme $ZSH/themes/021011.zsh-theme
```

3. Go to your `~/.zshrc` file and set `ZSH_THEME=021011`

---

## **Recommended Settings**

- [Color scheme for term](https://github.com/guesswhozzz/guezwhoz-scheme/blob/main/color-scheme/guezwhoz-scheme.yaml)

  > Mac Os users can set color scheme for iTerm2 from [repo](https://github.com/guesswhozzz/guezwhoz-iterm2-theme)


---

## **Extra**

You can find this color scheme for other terminal emulators in the [mbadolato](https://github.com/mbadolato/iTerm2-Color-Schemes) color scheme repository

---

License [MIT](https://github.com/guesswhozzz/guezwhoz-vscode-theme/blob/master/LICENSE) © [Egor Lem](https://github.com/guesswhozzz)
