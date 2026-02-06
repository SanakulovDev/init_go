# Go Clean Architecture Initializer (init_go)

Ushbu script Go tilida yangi loyihalarni professional **Clean Architecture** (Toza arxitektura) strukturasi asosida tezkorlik bilan yaratish uchun mo'ljallangan.

## 🏗 Loyiha Strukturasi

Script ishga tushganda quyidagi papkalar iyerarxiyasini avtomatik quradi:

```text
├── cmd/                # Dasturga kirish nuqtasi (main.go)
├── internal/           # Loyihaning ichki kodi (Tashqaridan import qilib bo'lmaydi)
│   ├── controller/     # HTTP Handlerlar (Gin, Fiber va h.k.)
│   ├── service/        # Biznes mantiq (Logika qatlami)
│   ├── repository/     # Ma'lumotlar bazasi bilan ishlash qatlami
│   └── model/          # Ma'lumot qoliplari (Structs)
├── go.mod              # Loyiha modullari
└── README.md           # Loyiha hujjati
````

## ⚡️ Tezkor ishlatish (O'rnatmasdan)

Scriptni yuklab o'tirmasdan, to'g'ridan-to'g'ri ishlatish uchun terminalga quyidagi buyruqni yozing:

```bash
curl -sL https://raw.githubusercontent.com/SanakulovDev/init_go/main/init_go.sh | bash
