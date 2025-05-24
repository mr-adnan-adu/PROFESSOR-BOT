# Option 1: Basic (your current setup)
web: python bot.py

# Option 2: Worker process (recommended for bots)
worker: python bot.py

# Option 3: Both web and worker
web: python bot.py
worker: python bot.py

# Option 4: With Gunicorn (if using webhooks)
web: gunicorn --bind 0.0.0.0:$PORT app:app
worker: python bot.py

# Option 5: Multiple workers
web: python bot.py
worker: python bot.py
scheduler: python scheduler.py
