Blockchain in GO.

To test:

go run main.go
<br/> 
curl http://localhost:8080/
<br/>
curl -X POST -d @data.json http://localhost:8080/


Requires a .env file set with the PORT you wish to use. By default it's 8080.


Example result:

[
 {
  "Index": 0,
  "Timestamp": "2024-07-04 18:00:30.6609103 -0400 EDT m=+0.003060801",
  "BPM": 0,
  "Hash": "",
  "PrevHash": ""
 },
 <br/> 
 {
  "Index": 1,
  "Timestamp": "2024-07-04 18:00:41.6036448 -0400 EDT m=+10.945795301",
  "BPM": 50,
  "Hash": "2fa675b69bf6e6cdee74750e01009252f013895649886ee753ffd967350991fb",
  "PrevHash": ""
 },
 <br/> 
 {
  "Index": 2,
  "Timestamp": "2024-07-04 18:00:43.1002978 -0400 EDT m=+12.442448301",
  "BPM": 50,
  "Hash": "fa6dac2252af0dd459f55cae5a569d72ae580ba3bf833c72b76bd2d67309e019",
  "PrevHash": "2fa675b69bf6e6cdee74750e01009252f013895649886ee753ffd967350991fb"
 },
 <br/> 
 {
  "Index": 3,
  "Timestamp": "2024-07-04 18:00:43.8950183 -0400 EDT m=+13.237168801",
  "BPM": 50,
  "Hash": "dca63880b244e4e260910d13d5e22856533d326cc157ae0ee97bfe1c6efdc223",
  "PrevHash": "fa6dac2252af0dd459f55cae5a569d72ae580ba3bf833c72b76bd2d67309e019"
 },
 <br/> 
 {
  "Index": 4,
  "Timestamp": "2024-07-04 18:00:44.5919859 -0400 EDT m=+13.934136401",
  "BPM": 50,
  "Hash": "166ebbba4aa6995221f18a324d372e163598937c35c9fc0a036ce08e28b2383b",
  "PrevHash": "dca63880b244e4e260910d13d5e22856533d326cc157ae0ee97bfe1c6efdc223"
 },
 <br/> 
 {
  "Index": 5,
  "Timestamp": "2024-07-04 18:00:45.1625468 -0400 EDT m=+14.504697301",
  "BPM": 50,
  "Hash": "4006e414e18bd76986fe1f725ac3f6f04a64f45ce5b29bb09678df6472553e6b",
  "PrevHash": "166ebbba4aa6995221f18a324d372e163598937c35c9fc0a036ce08e28b2383b"
 }
]
