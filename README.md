**admin login**:http://127.0.0.1:8000/admin/
**add new user** http://127.0.0.1:8000/admin/auth/user/add/

**Get all books:**-  method :- Get 
http://127.0.0.1:8000/bookservices/book/
[
  {
    "id": 2,
    "name": "aaaaaa",
    "qty": 44,
    "price": 500
  }
]
**Add new book:-** Method:- post
http://127.0.0.1:8000/bookservices/book/
{
  "id": 3,
  "name": "My commands over SQL",
  "qty": 40,
  "price": 1060
}
**get book by id:-** method:-get
http://127.0.0.1:8000/bookservices/book/3/
{
  "id": 3,
  "name": "My commands over SQL",
  "qty": 40,
  "price": 1060
}
**Delete book by id:-** method :- delete
http://127.0.0.1:8000/bookservices/book/2/
 **update book:-** method:- put
 http://127.0.0.1:8000/bookservices/book/3/
 {
  "id": 3,
  "name": "PPPPPPP",
  "qty": 500,
  "price": 565
}