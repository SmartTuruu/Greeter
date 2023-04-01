Ялангуяа Cryptorelax сувгийн хувьд https://www.youtube.com/@Crypto-Relax
Манай телеграм: https://t.me/CRYPTORELAKS
ZkSync үеийн албан ёсны хөтөч: https://era.zksync.io/docs/dev/building-on-zksync/hello-world.html болон https://era.zksync.io/docs/api/hardhat/getting- start.html#learn-more
Goerli тогоруу: https://goerlifaucet.com/ ;
ZkSync тестийн тохиргоо: https://era.zksync.io/docs/dev/troubleshooting/important-links.html ;
zksync эрин туршилтын сүлжээнд шилжүүлэх гүүр: https://portal.zksync.io/bridge;
Гэрээ болон гүйлгээг шалгах Explorer: https://goerli.explorer.zksync.io/ ;
Үйлдлүүд:
Visual Studio кодыг татаж авах (хэрэв байхгүй бол): https://code.visualstudio.com/
Бид VSC (Solidity, npm Intellisense) дээр шаардлагатай өргөтгөлүүдийг нэмдэг, хэрэв VSC дээр ажиллах явцад алдаа гарч, баруун доод буланд багцуудыг татаж авахыг санал болгосон цонх гарч ирвэл бид зөвшөөрч байна (хүн бүр өөр өөр зүйлтэй байж болно), юу багцад байхгүй болно ( ip, node.js гэх мэт) гараар суулгана (Интернет дээр маш олон гарын авлага байдаг)
Энэ репозитороос VSC руу холбоос нэмнэ үү: https://github.com/sevRipen/Greeter
Метамаск бэлтгэ: ZkSync Era Testnet сүлжээг https://chainlist.org/?testnets=true&search=zksync+era+testnet эсвэл гараар нэмнэ үү.
Goerlis-ийн тестийг https://goerlifaucet.com/ хаягаар авна уу.
Бид Goerli ETH-ийг https://portal.zksync.io/bridge гүүрээр дамжуулан ZkSync Era Testnet руу илгээдэг (баруун доод талд ZkSync Era Goerli асаалттай байгаа эсэхийг шалгана.
Бид VSC руу буцаж очоод терминал дээр дараах тушаалыг бичнэ: ip init -y эсвэл npm init -y
Дараа нь бичнэ үү: sudo npm i -D typescript ts-node ethers@^5.7.2 zksync-web3@^0.13.1 hardhat @matterlabs/hardhat-zksync-solc @matterlabs/hardhat-zksync-deploy
Дараа нь: ip hardhat compile эсвэл npx hardhat compile
Deploy.ts дээр бид метамаскаас хувийн түлхүүрээ оруулдаг
Мөн сүүлчийн тушаал: ip hardhat deploy-zksync эсвэл npx hardhat deploy-zksync ба гэрээний байршуулалт дуусахыг хүлээнэ үү.
Бид гэрээг баталгаажуулдаг (видео үзэх)
Ухаалаг гэрээтэй харилцах (видео үзэх)
хөл хэсэг
© 2023 GitHub Inc.
хөлийн навигаци
Нөхцөл
нууцлал
аюулгүй байдал
Статус
баримт бичиг
GitHub-тэй холбоо барина уу
