# Minecraft Simple Tutorial 

### Requirements
- open-jdk
- pytorch
- gym
- minerl

###  1. Minecraft RL 환경 설치
마인크래프트 게임은 Java Platform에서 동작합니다. 때문에 JDK 1.8 버전을 설치해야 합니다. 

(Windows)  
oracle 홈페이지에서 회원가입 후 다운받아서 설치할 수 있습니다. 
https://www.oracle.com/kr/java/technologies/javase/javase8-archive-downloads.html

(Mac)  
brew tap AdoptOpenJDK/openjdk  
brew install --cask adoptopenjdk8  

(Ubuntu)  
sudo add-apt-repository ppa:openjdk-r/ppa  
sudo apt-get update  
sudo apt-get install openjdk-8-jdk  

### 2. Pytorch 설치

https://pytorch.org/

위 링크에서 자신의 환경에 맞게 설치해주세요.  

### 3. gym, minerl 설치

```
pip install gym==0.19.0
pip install minerl==0.3.7
```