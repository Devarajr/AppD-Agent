# AppD-Agent


#Run the playbook with extrnal-vars for each environment ( PIT | MOT | DDM | PRD ) 

ansible-playbook ansible-appd-agent.yml --extra-vars "env_name=MOT"
