# This repository is practice purposes only. 

Deploying ota server 
ota update for different profiles
db: mariadb mysql



https://hub.docker.com/_/mariadb
http://www.electrode.io/docs/what_is_electrode.html


mariadb

docker-compose up -d





Deployment keys (dokümanda geri bu kısım, terminalde prompt ediliyor)

code-push app add client-ios ios react-native
code-push app add client-android android react-native

output: deployment keys


code-push app add ota-server



 code-push release-react client-ios ios --deploymentName Production -m
 code-push release-react Client ios --deploymentName Staging -m
code-push release-react client-android android --deploymentName Production -m 

code-push release-react client-ios  ios  -d Staging -m

list deployments 

code-push deployment ls [AppName] -k

code-push release-react client-ios  ios  -d Production -m --targetBinaryVersion "1.2.2"
code-push release-react client-ios  ios  -d Staging -m --targetBinaryVersion "1.2"

# auth hapijs

github alternatives

https://hapi.dev/module/bell/providers/#gitlab


http://localhost:9001/update_check?deployment_key=FJXivrMlcedDOQTpPYBTWlKhcTpPtYIVCUbRCGaF&app_version=1.2.1&package_hash=403a7419acbfb412f67836d2b034f83811b6b306aad22f4e060c25b995ceee79&client_unique_id=C63EE486-2A13-4ECB-8393-87F2EB555F9A