ssh -i ~/.ssh/id_rsa -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null -o ProxyCommand="ssh -i ~/.ssh/id_rsa -W %h:%p -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null aiscuser@aisc-prod-eastus2-cpml-lnx-3.federation.singularity.azure.com" aiscuser@node-0.1000ed99-2eec-4c85-a746-22f795ba8a86


ssh -i ~/.ssh/id_rsa -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null -o ProxyCommand="ssh -i ~/.ssh/id_rsa -W %h:%p -o StrictHostKeyChecking=no -o UserKnownHostsFile=/dev/null aiscuser@aisc-prod-eastus-cpml-lnx-36.federation.singularity.azure.com" aiscuser@node-0.ccf8d993-6739-4a00-9b2d-229f289286db
