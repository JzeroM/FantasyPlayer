多人网页在线观影

前端播放器套装使用开源的DPlayer https://github.com/DIYgod/DPlayer
使用socket.io实现同步交互，使用nodejs作为后端
服务器部分很简单：
第一步:打开服务器的3000端口
第二步：服务器配置nodejs、npm和git环境 sudo apt install nodejs npm -y && sudo apt install git
第三步：git项目到服务器git clone https://github.com/JzeroM/FantasyPlayer.git
第四步:进入项目文件夹cd FantasyPlayer
第五步:下载项目使用的包 npm install
第六步:启动后端服务 node server.js
访问地址http://你的服务器公网IP:3000即可
