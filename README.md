# Object дотроос хайлт хийх

## Даалгавар

`index.js` дотор байгаа `search` функцыг дуусга.

search функц нь параметраар 1 string авна энэ нь дууны нэр бөгөөд дууны жагсаалт дотроос хайлт хийж тухайн үг өрсөн дууны id ийг буцаана Том жижиг үсгийг ялгаатай гэж үзэхгүй.



Жишээ нь 
* husel гэж оруулахад {'content': 'minii husel bol chi', 'id': 1}, {'id': 10, 'content': 'hamgiin ih Husel bol chi'} гэх үр дүнгүүд дотроос хамгийн эхэнд буюу хамгийн бага id дугаарыг буцаана => 1
* bodol {'content': 'bodol1', 'id': 7}, {'content': 'mini bodol2', 'id': 4} => 4 

**Хэрвээ олдохгүй бол -1 гэж буцаана**
Зөвхөн **search** гэсэн функцыг засахыг анхаарна уу!
