# KEYLOGGER

## 📁 Project Structure

```text
typing-auth-project/
├─ src/
│  ├─ __init__.py
│  ├─ app_gui.py            # GUI: Tkinter application (view + simple controller)
│  ├─ collector.py          # KeyEvent, TypingSession, session collection logic
│  ├─ datastore.py          # SQLite storage, export, delete
│  ├─ features.py           # Feature extraction pipeline & normalization
│  ├─ model.py              # Training/evaluation/persistence (joblib)
│  ├─ utils.py              # helpers (timers, serializers, constants)
│  └─ tests/
│     ├─ test_collector.py
│     ├─ test_datastore.py
│     ├─ test_features.py
│     └─ test_model.py
├─ requirements.txt
├─ README.md
|-- data/typing_auth.db
└─ .github/
   └─ workflows/python-app.yml


