# IoT_cap_9
# Integrantes
> Luz Pilco Pancca 

> Erika Sejje Condori

# Ejecucion

## Data Access APIs
https://raw.githubusercontent.com/esejjec/IoT_Cap9/main/img/figure10.png

> curl -X GET "http://localhost:1880/get/topicLike/timestamp/payloadLike/payload/last/5"

> curl -X GET "http://localhost:1880/get/topicLike/timesta*/payloadLike/*/last/2"

> curl -X GET "http://localhost:1880/get/topicLike/timesta*/payloadLike/*88*/last/2"


> curl -X GET "http://localhost:1880/get/timestamp/last/7"
> curl -X GET "http://localhost:1880/get/timestamp/before/1638085554.286/last/5"
> curl -X GET "http://localhost:1880/get/timestamp/after/1638085554.286/last/5"
> curl -X GET "http://localhost:1880/get/timestamp/during/1638085554.286/last/5"

Delete

> curl -X GET "http://localhost:1880/get/timestamp/last/5"
> curl -X GET "http://localhost:1880/delete/timestamp/id/4"
