admission_assistant_bot/
├── bot/
│   ├── __init__.py
│   ├── main.py                   # Точка запуска
│   ├── handlers/
│   │   ├── __init__.py
│   │   ├── common.py             # /start и обычные команды
│   │   ├── menu_router.py        # Роутинг по кнопкам
│   │   └── ai_handler.py         # /ai команда
│   ├── keyboards/
│   │   └── main_menu.py          # Reply клавиатура
│   ├── services/
│   │   └── llm_service.py        # OpenAI (или др.)
│   ├── texts/
│   │   ├── how_to_apply.txt
│   │   ├── documents.txt
│   │   ├── ent_scores.txt
│   │   ├── deadlines.txt
│   │   ├── submission.txt
│   │   └── contacts.txt
│   └── config.py
├── .env
├── requirements.txt
└── run.py"# AdmissionBot" 
"# AdmissionAIChatBot" 
#   A d m i s s i o n A I C h a t B o t  
 