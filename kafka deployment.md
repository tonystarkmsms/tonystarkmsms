hi deploument of apche kafka
launch ec2 t2 medium    ami-004d038b7950c224c
sudo apt-get update 
sudo apt-get update && sudo apt-get -y install ca-certificates zip net-tools netcat
sudo apt-get install default-jdk -y
scp -i mkskey.pem mkskey.pem ubuntu@54.163.121.111:~/.ssh/
ssh -i Downloads/mkskey.pem ubuntu@54.163.121.111
