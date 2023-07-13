# kafka-project
Creating Kafka pipeline where there are 3 services: (1) Producer, (2) Consumer/Producer, and (3) Consumer. The messages will be sent from (1) service to (3) service through topics and (2) service. Below is the illustration of the pipeline:

(1) Producer -> topic purchase -> (2) Consumer/Producer -> topic next-purchase -> (3) Consumer

Error log:
 - Cannot produce a delivery log in Consumer/Producer
