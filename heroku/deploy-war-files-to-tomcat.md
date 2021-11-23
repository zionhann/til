# 톰캣 서버에 war 파일 배포

## java plugin 설치
```powershell
$ heroku plugins:install java
```

## 배포
```powershell
$ heroku war:deploy FILENAME.war --app DOMAINNAME
```

## 확인
```powershell
$ heroku open -a DOMAINNAME
```

## Reference
[Heroku CLI Plugin for Java](https://github.com/heroku/plugin-java)