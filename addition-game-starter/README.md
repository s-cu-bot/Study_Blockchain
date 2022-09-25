<h2># addition-game-starter</h2>
<h5>Klaytn javascript native boilerplate</h5>

  </br>
  
### **사용기술 및 언어**
- solidity v0.4.25 (solc-js)
- truffle v4.1.15
- npm v6.4.1
- node v10.15.3  

</br>

### **기능**
<img src="https://user-images.githubusercontent.com/68038906/135716278-62efd0d8-9574-463c-b76d-2b2ecd5ed109.PNG"  width="600" height="300"/>

**①** Klaytn Wallet 업로드 및 로그인 (비밀번호 필요)  
**②** 3초안에 덧셈 문제 맞추기  
**③** 맞추면 컨트랙에 저장된 0.1 KLAY 제공 (test_net)     

</br>

  
### **수정사항**
- truffle.js의 PRIVATE_KEY 적용 필요
- keystore v3 -> v4 수정 적용 (keyring)
- deposit의 Owner wallet 비교 과정에서 toUpperCase 적용
- package.json의 caver-js version 수정 (keystore v4 복호화에 필요)
  
</br>

### **출처**
https://github.com/kkagill/addition-game-starter.git  
https://truffleframework.com/boxes
