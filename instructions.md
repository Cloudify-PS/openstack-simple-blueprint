Part 1

Download the repo to a machine that has cloudify CLI 4.6

1. Configure the CLI to work with the manager
2. Upload the openstack-vm-blueprint.yaml
> `cfy blueprints upload openstack-vm-blueprint.yaml`

3. Create deployment
4. Run the install workflow


 Part 2
1. Modify the Blueprint
- Remove the inputs and hardcode the values
- Make the BP create 2 server: FrontEnd BackEnd
2. Upload the Blueprint
3. Create deployment
4. Run the install workflow for the deployment
5. Scale UP the Front End server
6. Run Heal workflow on the backend (node instance)
