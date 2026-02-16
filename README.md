working on yugabyte deployment on k3s

gotten initially from wget https://raw.githubusercontent.com/YugaByte/yugabyte-db/master/cloud/kubernetes/yugabyte-statefulset.yaml

when you have masters up, go into one of the containers and do
./bin/yb-admin --master_addresses 10.42.0.43 list_all_masters
should show you the masters
