# rabbitmq-tutorial
a very simple rabbitmq code samples from official tutorial using pika library

#### Requirements
- Erlang
- RabbitMQ
- Python3
- Pika library

#### Installing

```bash
git clone git@github.com:hiorws/rabbitmq-tutorial.git
cd rabbitmq-tutorial/
virtualenv --python python3 venv
source venv/bin/activate
pip3 install -r requirements.txt
```

#### Running samples
```bash
cd tutorial1/
python receive.py
```

in another terminal
```bash
cd tutorial1/
python send.py
```

All the source codes taken from [RabbitMQ website](https://www.rabbitmq.com/tutorials/tutorial-one-python.html).
