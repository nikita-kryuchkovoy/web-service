docker exec -it faea563c638d bash

docker exec -it c35e58428775 python train_model.py

curl --header "Content-Type: application/json" --request POST --data '{"flower":"1,2,3,7"}' http://localhost:5000/iris_post