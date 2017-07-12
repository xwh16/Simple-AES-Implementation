1.Encryptor AES加密机 顶层电路已封装。

2.Decryptor AES解密机 顶层电路已封装，由于电路规模较大在Logisim中容易出现错误，当错误发生时应尝试重新打开。

3.test.circ 基于AES加解密机的通信演示电路，可以设置128比特明文输入和128比特初始密钥。按Ctrl+K自动进行加解密。

4.SBox,SBox(r) AES加解密算法S盒LUT(Look Up Table)，已导入加解密电路ROM当中。

***若解密数据错误应尝试重新加载电路.-|-
