# ОБЯЗАТЕЛЬНО, иначе ошибка

переходим по данному адресу венв\Lib\site-packages\pytubefix\sabr\core\server_abr_stream.py
дальше редактируем: 

class PoTokenStatus(enum.Enum):
     OK = 1
     PO_TOKEN_REQUIRED = 2
     PO_TOKEN_EXPIRED = 3
     PO_TOKEN_INVALID = 4
     PENDING_MISSING = 5
     
чтобы было так
