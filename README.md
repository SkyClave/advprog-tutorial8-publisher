# Questions

## How many data your publlsher program will send to the message broker in one run? 

Ada 5 data yang dikirimkan publisher ke message broker dalam 1 run. Pada fungsi main ada lima kali publish event yang masing-masing mengirimkan 1 event ke message broker.

## The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Publisher mengakses url yang sama dengan subscriber berarti keduanya berkomunikasi dengan message broker yang sama dengan protokol yang sama. Publisher dan subscriber dapat berkomunikasi dan pesan publisher dapat disampaikan kepada subsrciber melalui message broker yang sama.

## Running RabbitMQ

![Running RabbitMQ](/assets/images/rabbitmq1.jpg)