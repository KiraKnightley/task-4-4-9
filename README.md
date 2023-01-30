Post запрос по ссылке https://blog.kata.academy/api/users /n
body: 
{
"user": {
    "username": "KirillSavin",
    "email": "kirill@mail.ru",
    "password": "1234"
  }
}
ответ:
{
    "user": {
        "username": "kirillsavin",
        "email": "kirill@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDdlYzA0NmY4YmVlMWIwMDU1MTg3ZCIsInVzZXJuYW1lIjoia2lyaWxsc2F2aW4iLCJleHAiOjE2ODAyNzkwNDQsImlhdCI6MTY3NTA5NTA0NH0.iIQ64TDMxSqb0KLqWTGiCDGlxMq3H_zuwBUxrczm5Ns"
    }
}


Post запрос со ссылке https://blog.kata.academy/api/users/login
body:
{
  "user": {
    "email": "kirill@mail.ru",
    "password": "1234"
  }
}
ответ:
{
    "user": {
        "username": "kirillsavin",
        "email": "kirill@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDdlYzA0NmY4YmVlMWIwMDU1MTg3ZCIsInVzZXJuYW1lIjoia2lyaWxsc2F2aW4iLCJleHAiOjE2ODAyNzkyOTYsImlhdCI6MTY3NTA5NTI5Nn0.SV8R8c4JP_QMZ-kg8fL4LXLDv6asz6dLV0R1Zbkd56c"
    }
}




Get запрос по ссылке https://blog.kata.academy/api/user
authorization: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDdlYzA0NmY4YmVlMWIwMDU1MTg3ZCIsInVzZXJuYW1lIjoia2lyaWxsc2F2aW4iLCJleHAiOjE2ODAyNzkyOTYsImlhdCI6MTY3NTA5NTI5Nn0.SV8R8c4JP_QMZ-kg8fL4LXLDv6asz6dLV0R1Zbkd56c

ответ:
{
    "user": {
        "username": "kirillsavin",
        "email": "kirill@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzZDdlYzA0NmY4YmVlMWIwMDU1MTg3ZCIsInVzZXJuYW1lIjoia2lyaWxsc2F2aW4iLCJleHAiOjE2ODAyNzk0MDIsImlhdCI6MTY3NTA5NTQwMn0.rqMZid3QUAtBJpuyDO0dDHz_Z26qPn-5omBj0vF-c7c"
    }
}
