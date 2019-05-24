OSSEC Agent Deployment for OSSIM server

1. -> Goto the hosts file and enter the IP address of the hosts which is added as an agent based on its OS_Distribution

2. -> then edit roles/ossec/templates/add_agent and enter the host ip address,hostname and unique id for each agent one by one

3. -> After that run "ansible-playbook -i hosts ossec-agent.yml"

4. -> It install OSSEC Agent and deploy key for all agent.

5. -> Wait 10-15 minutes in OSSIM Dashboard and see whether the agent is in Active mode.
