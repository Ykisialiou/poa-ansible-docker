docker container with prerequsites, to run deployment-terraform playbooks
without additional actions

Expected to bu run with smth like this
`sudo docker run -v $(pwd):/ansible/ -it 0349dbbdc9d0 ansible-playbook ansible/azure/site.yml`
