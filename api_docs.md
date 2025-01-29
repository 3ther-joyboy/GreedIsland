# Objects
## card
```JSON
{
  "id":long,
  "created_by":{user},

  "name":string,
  "description":string,
  "story":string,
  "rarity":char,

  "type": {type},
  "passive": [passive],
  "edition":[edition],

  "red":int,
  "green":int,
  "white":int,
  "blue":int,
  "multi":int,
}
```
## type
### type
```JSON
{
  "id":long,
  "created_by":{user},

  "name":string,
  "sub_type":{sub_type}
}
```
### sub_type
```JSON
{
  "id":long,
  "created_by":{user}

  "name":string,
  "description":string
}
```
## edition
```JSON
{
 "id":long,
  "created_by":{user},

  "name":string
}
```
## passive
```JSON
{
  "id":long,
  "created_by":{user}

  "name":string,
  "description":string
}
```
# Rest API
