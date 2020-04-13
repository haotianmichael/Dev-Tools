### Common Development Tools 



*  **OS:       macOS  Mojave10.14**

*  **EDITOR:      vim  +  ​Tmux​**
*  **SHELL:      On-my-zsh​**

*  **CVS:      Git​**



### Python管理
  

因为包管理器下载过很多版本的Python, 系统自带/usr/local/Cellar/python2.7  
其中下载过anaconda包管理器，最终决定使用该环境统一Python环境

add 'export PATH="/anaconda3/bin:$PATH"'  to .zshrc

其中vim必须使用系统再带Python2.7编译使用YCM插件，所以统一环境之后需要重新使用Python2.7编译YCM  
cd .vim/YCM/
python2 .install.py  






