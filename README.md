# SHA1-SHA2
使用c语言实现用SHA-1,SHA2

# 运行方式
需要在代码中修改加密文件的路径和需要解密的文件路径，也可以修改密钥。

# 代码运行结果（含截图）
加密压缩文件大小
<img width="348" alt="image" src="https://user-images.githubusercontent.com/52338965/154854197-02b04c3c-d87f-44ee-82ce-6d44e11ebb39.png">

1.SHA-1
运行结果
<img width="415" alt="image" src="https://user-images.githubusercontent.com/52338965/154854217-d82ab0bb-3a6c-4f1f-bd22-237e042588c7.png">

用命令行来测试sha-1值是否相同
<img width="415" alt="image" src="https://user-images.githubusercontent.com/52338965/154854225-cd3b47af-d024-4c7f-a41b-40aef1e38c7b.png">
二者的值相同，速度为40-50Mb/s。

2.SHA512
运行结果
<img width="416" alt="image" src="https://user-images.githubusercontent.com/52338965/154854265-a45b0e57-6224-4ea0-a34e-c344588089ad.png">
用命令行测试正确性
<img width="416" alt="image" src="https://user-images.githubusercontent.com/52338965/154854279-5fe57160-3e7f-4147-83ad-bb33b7b5a8f6.png">
运行结果正确，速度为18-20Mb/s
