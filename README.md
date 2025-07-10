# Инструкция по изменению файла server_abr_stream.py

## Шаги для изменения:

1. Перейдите по следующему пути:
     venv\Lib\site-packages\pytubefix\sabr\core\server_abr_stream.py
2. Найдите класс `PoTokenStatus` и измените его содержимое на:
     ```python
     class PoTokenStatus(enum.Enum):
      OK = 1
      PO_TOKEN_REQUIRED = 2
      PO_TOKEN_EXPIRED = 3
      PO_TOKEN_INVALID = 4
      PENDING_MISSING = 5
