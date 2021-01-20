NVM-CHINA-MIRROR（nvm中国镜象）
===

## 安装方式

一、使用`curl`或者`wget`安装

1. curl

```
curl -o- https://nvm-china-mirror.github.io/current/install.sh | bash
```

2. wget

```
wget -qO- https://nvm-china-mirror.github.io/current/install.sh | bash
```

二、在当前shell立即作用

需要运行下面的代码：

```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
