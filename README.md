GO RABBIT MQ:

http://localhost:15672/#/

Terminal ERORRS:
PS C:\> refreshenv
Refreshing environment variables from the registry for powershell.exe. Please wait...
Finished
PS C:\> go version
go version go1.18.4 windows/amd64

admin:

docker ps
docker exec -it 60a bash
rabbitmqadmin publish exchange=amq.default routing_key="TestQueue" payload="Hello world"


Git:Set User
 git remote set-url origin https://IskenT@github.com/IskenT/go-rabbitmq.git