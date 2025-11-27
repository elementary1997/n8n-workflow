# Плейсхолдеры для воркфлоу n8n

В данном json используются следующие переменные — их необходимо заменить на свои значения:

| Плейсхолдер                |  Где использовать                           | Как получить                                 |
|----------------------------|---------------------------------------------|----------------------------------------------|
| GOOGLE_TASKS_CREDENTIAL_ID | credentials Google Tasks                    | В n8n, ID вашей учётки Google Tasks          |
| GOOGLE_SHEETS_CREDENTIAL_ID| credentials Google Sheets                   | В n8n, ID вашей учётки Google Sheets         |
| TELEGRAM_CREDENTIAL_ID     | credentials Telegram                        | В n8n, ID вашей учётки Telegram Bot          |
| GOOGLE_SHEETS_DOC_ID       | Google Sheets documentId                    | Из URL Google Sheets (между /d/ и /edit)     |
| GOOGLE_SHEETS_SHEET_ID     | Google Sheets sheetName (gid)               | Из URL Google Sheets (gid=...)               |
| TELEGRAM_CHAT_ID           | Telegram node → chatId                      | Ваш ID чата/группы для бота                  |
| N8N_INSTANCE_ID            | meta.instanceId (опционально)               | Уникальный ID вашей n8n инстанции            |