commands

-> start kafka cluster: docker-compose -f common.yml -f kafka_cluster.yml up

-> kafkacat: docker pull confluentinc/cp-kafkacat

             kafkacat -L -b localhost:19092

-> setting the network host: docker run -it --network=host confluentic/cp-kafkacat kafkacat -L -b localhost: 19092