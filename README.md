# Create a new virtual environment:

   ```bash
   $ python -m venv azure-servicebus-venv
   $ # Linux:
   $ . azure-servicebus-venv/bin/activate
   $ # Windows:
   $ #. azure-servicebus-venv/Scripts/Activate
   ```

# Install requirements
```bash
$ pip install -r requirements.txt
```

# Executing examples
```bash
$ python examples/001.quickstart.py
```

# Send Message to Queue
```bash
$ python 001.send-message-to-queue.py 
```

# Receive Message from Queue
```bash
$ python 002.receive-message-from-queue.py 
```

# Send Message to Topic
```bash
$ python 003.send-message-to-topic.py 
```

# Receive Message from Topic
```bash
$ python 004.receive-message-from-topic.py 
```