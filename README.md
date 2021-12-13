# IoT_cap_9
# Integrantes
> Luz Pilco Pancca 

> Erika Sejje Condori

# Ejecucion

## Data Access APIs
![Data Access APIs](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure10.png?raw=true)

> curl -X GET "http://localhost:1880/get/topicLike/timestamp/payloadLike/payload/last/5"

> curl -X GET "http://localhost:1880/get/topicLike/timesta*/payloadLike/*/last/2"

> curl -X GET "http://localhost:1880/get/topicLike/timesta*/payloadLike/*88*/last/2"

![curl](https://github.com/esejjec/IoT_Cap9/blob/main/img/curl_topicLike.png?raw=true)

![Data Access APIs](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure11.png?raw=true)

## Adding Time-Based Filters
![Adding Time-Based Filters](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure20.png?raw=true)
> curl -X GET "http://localhost:1880/get/timestamp/last/7"

> curl -X GET "http://localhost:1880/get/timestamp/before/1638085554.286/last/5"

> curl -X GET "http://localhost:1880/get/timestamp/after/1638085554.286/last/5"

> curl -X GET "http://localhost:1880/get/timestamp/during/1638085554.286/last/5"
![curl](https://github.com/esejjec/IoT_Cap9/blob/main/img/curl_topicLike.png?raw=true)
![Adding Time-Based Filters](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure21.png?raw=true)

## Data Deletion APIs
![Deletes](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure30.png?raw=true)
> curl -X GET "http://localhost:1880/get/timestamp/last/5"
> curl -X GET "http://localhost:1880/delete/timestamp/id/4"
![curl](https://github.com/esejjec/IoT_Cap9/blob/main/img/curl_delete.png?raw=true)
![Delete](https://github.com/esejjec/IoT_Cap9/blob/main/img/figure31.png?raw=true)
