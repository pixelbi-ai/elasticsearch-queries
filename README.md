# Elasticsearch Queries

### Retrieved specific fields

Query retrives only first_name, last_name and city field inside address object
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
