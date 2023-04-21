# PAYLOAD TO INTEGRATE THE API

GET METHOD http://127.0.0.1:8000/studentapi/

GET METHOD http://127.0.0.1:8000/studentapi/ID/

POST METHOD http://127.0.0.1:8000/studentapi/

All field is required =>
BODY = {
    "name": "Sonam",
    "roll": 101,
    "city": "Ranchi"
}

PUT METHOD http://127.0.0.1:8000/studentapi/ID/

All field is required =>
BODY = {
    "name": "Sonam",
    "roll": 101,
    "city": "Ranchi"
}
PATCH METHOD http://127.0.0.1:8000/studentapi/ID/

More then 0 field is required
BODY = {
    "name": "Sonam",
    "roll": 101,
    "city": "Ranchi"
}

DELETE METHOD http://127.0.0.1:8000/studentapi/ID/

