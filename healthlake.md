* config 파일에 아래 프로파일 정보를 추가한다. 
```
[profile hlake]
region = us-west-2
```

* credentails 파일에도 프로파일 정보를 추가한다. 
```
[hlake]
aws_access_key_id = <yours>
aws_secret_access_key = <yours>
```

```
$ aws --profile hlake healthlake list-fhir-datastores
{
    "DatastorePropertiesList": []
}
```
