#init

https://courses.education.pivotal.io/

https://console.run.pivotal.io/
java_buildpack

cf push movie-fun-app -p build/libs/moviefun-1.1.0-SNAPSHOT.war -b java_buildpack --random-route


cf push moviefun -p target/moviefun.war -b java_buildpack --random-route


./gradlew replatformingSpringBootification -PmovieFunUrl=https://moviefun-shy-bonobo.cfapps.io


https://moviefun-shy-bonobo.cfapps.io


git push origin master --tags

export VCAP_SERVICES='{"user-provided": [{"credentials": {"access_key_id": "AAAAAAAAA", "bucket": "moviefun", "secret_access_key": "SSSSSSSSS", "endpoint": "http://127.0.0.1:9000"}, "name": "photo-storage"}]}'


AKIAVT7FZ27LX3JUIYCN
k0JazFcjXMKrZjkJnM54YqWA93tHD1OAIwCyqkRQ


cf cups photo-storage -p '{"access_key_id":"AKIAVT7FZ27LX3JUIYCN","secret_access_key":"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","bucket":"leiyuzhang.k2workflow.com.cn"}'

./gradlew replatformingRemovingPersistenceToFileSystem -PmovieFunUrl=https://moviefun-shy-bonobo.cfapps.io

cf env moviefun

cf cups -?

logs5.papertrailapp.com:45339

gradle init --type pom

 ./gradlew clean build -xtest


lsof | grep 63306

kill -9 21816
