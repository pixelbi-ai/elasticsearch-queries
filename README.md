# Elasticsearch Queries

### Retrieved specific columns


```
GET localhost:9200/users/_search

{
    "_source": [
        "first_name",
        "last_name",
        "address.city"
    ]
}
```
