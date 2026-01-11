# EuroRosTrans — Render All-in-one (Liquid Glass UI)
Один домен: сайт + API + регистрация/роли.

## Render
Создай **Web Service**:
- Root Directory: `server`
- Build: `npm install`
- Start: `node server.js`

Environment:
- JWT_SECRET = длинный секрет
- DB_PATH = ./data.sqlite
- LOGIST_INVITE_CODE = код логиста (если нужен)

Проверка:
- /api/health -> {"ok":true}
- / -> сайт
