# 4.4.9_Postman
1.Создал POST запрос для регистрации пользователя. Указал в BODY usernam / email / password - kartashyanArtem / artemkartashyan@mail.ru / 777 URL https://blog.kata.academy/api/users
Результат: 
{
    "user": {
        "username": "kartashyanartem",
        "email": "artemkartashyan@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1Mzk1YWU5ZmYzY2M4MWIwMGRhY2ExMCIsInVzZXJuYW1lIjoia2FydGFzaHlhbmFydGVtIiwiZXhwIjoxNzAzNDQxOTA2LCJpYXQiOjE2OTgyNTc5MDZ9.OQf74GAdIEcbaV1vBmJsQtPbLexCe1afF5hVi-ES4Mg"
    }
}


2.Залогинил созданного пользователя с помощью POST запроса. Указал данные email / password y.nefedoff.wm@gmail.com / 333 URL https://blog.kata.academy/api/users/login
Результат:
{
    "user": {
        "username": "kartashyanartem",
        "email": "artemkartashyan@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1Mzk1YWU5ZmYzY2M4MWIwMGRhY2ExMCIsInVzZXJuYW1lIjoia2FydGFzaHlhbmFydGVtIiwiZXhwIjoxNzAzNDQxOTA2LCJpYXQiOjE2OTgyNTc5MDZ9.OQf74GAdIEcbaV1vBmJsQtPbLexCe1afF5hVi-ES4Mg"
    }
}

{
  "user": {
    "email": "artemkartashyan@mail.ru",
    "password": "777"
  }
}



3.GET запрос для получения данных об авторизованном пользователе Указал токен выше URL https://blog.kata.academy/api/user
Результат: 
{
    "user": {
        "username": "kartashyanartem",
        "email": "artemkartashyan@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY1Mzk1YWU5ZmYzY2M4MWIwMGRhY2ExMCIsInVzZXJuYW1lIjoia2FydGFzaHlhbmFydGVtIiwiZXhwIjoxNzAzNDQxOTA2LCJpYXQiOjE2OTgyNTc5MDZ9.OQf74GAdIEcbaV1vBmJsQtPbLexCe1afF5hVi-ES4Mg"
    }
}
