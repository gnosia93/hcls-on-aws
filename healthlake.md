### CLI 환경 설정 ###

* healthlake 를 사용하기 위해서는 aws cli version 2 로 업그레이드 해야 한다.

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

### 테스트 ###
```
$ aws --profile hlake healthlake list-fhir-datastores
{
    "DatastorePropertiesList": []
}
```
