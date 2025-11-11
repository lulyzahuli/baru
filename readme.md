FastAPI + Redis + JWT (with Admin Panel & Blacklist)

Dokumentasi dan kode lengkap contoh proyek FastAPI yang:

Signup/login dengan penyimpanan user di SQLite (SQLAlchemy)

Password hashing (bcrypt)

JWT access token dengan jti untuk tiap sesi

Redis menyimpan session (session:) dan blacklist (blacklist:)

Admin panel (HTML) untuk melihat user dan blacklist / ban user

Token disimpan di cookie access_token (httponly) dan juga bisa dipakai lewat header Authorization: Bearer ...



roject/
├── requirements.txt
├── src/
│ ├── main.py
│ ├── database.py
│ ├── models.py
│ ├── auth/
│ │ ├── jwt_handler.py
│ │ └── routes.py
│ ├── utils/
│ │ └── redis_client.py
│ └── templates/
│ ├── login.html
│ ├── signup.html
│ ├── dashboard.html
│ └── admin.html