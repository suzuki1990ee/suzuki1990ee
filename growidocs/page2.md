## １．サーバーの準備
VMwareをインストール

## ２．ＯＳの準備
### Ubuntu serverをインストール

### GUIにしたい
- GUIをインストール  
多少のLinuxコマンドはわかるけど、どうみてもGUIの方が見やすい＆わかりやすいので  
  
1.UPDATE  
$ sudo apt-get update  
2.desktop-package install  
$ sudo apt-get -y install ubuntu-desktop  

### ブラウザをインストール  
今回はBraveというブラウザをインストール  
※トラッカーや広告をわりとカットしてくれるらしい。ついでに仮想通貨もたまる  
[Brave_linux](https://brave.com/linux/)  

１．  
sudo apt install apt-transport-https curl  
２．  
sudo curl -fsSLo /usr/share/keyrings/brave-browser-archive-keyring.gpg https://brave-browser-apt-release.s3.brave.com/brave-browser-archive-keyring.gpg  
３．  
echo "deb [signed-by=/usr/share/keyrings/brave-browser-archive-keyring.gpg arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main"|sudo tee /etc/apt/sources.list.d/brave-browser-release.list  
４．  
sudo apt update   
５．  
sudo apt install brave-browser  
６．起動  
brave-browser  


## ３、その他準備
