# 

```shell
mvn deploy:deploy-file \
    -Durl=http://localhost:8081/repository/coding-more/ \
    -DrepositoryId=myRepo \
    -Dfile=/Users/nanan/Documents/coding_more/github/codingMore/pom.xml \
    -DgroupId=com.github.nan \
    -DartifactId=coding-more \
    -Dversion=1.0.0 \
    -Dpackaging=pom
```