## Samples that shows how to deploy EC2 Instances using Cloudformation and using Systems Manager to configure the EC2 Instances.

**[AnsibleAssociation.yaml](AnsibleAssociation.yaml)** - This template demonstrates how you can use Ansible with CloudFormation and AWS Systems Manager to deploy Nginx. This CFN Template grabs the Ansible Playbook from a Github repo. Target is based on Instance ID. 

**[AnsibleAssociationTags.yaml](AnsibleAssociationTags.yaml)** - This template demonstrates how you can use Ansible with CloudFormation and AWS Systems Manager to deploy Nginx. This CFN Template grabs the Ansible Playbook from a Github repo. Target is based on tags.

**[BashScriptAssociation.yaml](BashScriptAssociation.yaml)** - This template demonstrates how you can run a bash script with CloudFormation using State Manager. Target is based on Instance ID. 

**[BashScriptAssociationTags.yaml](BashScriptAssociationTags.yaml)** - This template demonstrates how you can run a bash script with CloudFormation using State Manager. Target is based on Tags.

**[BashScriptSSMAutomation.yaml](BashScriptSSMAutomation.yaml)** - This template demonstrates how you can run a bash script with CloudFormation using State Manager and Automation for a more complex workflow with multiple steps. Target is based on Instance ID.

**[BashScriptSSMAutomationTags.yaml](BashScriptSSMAutomationTags.yaml)** - This template demonstrates how you can run a bash script with CloudFormation using State Manager and Automation for a more complex workflow with multiple steps. Target is based on Tags.

**[WinAssociationDomainJoin.yaml](WinAssociationDomainJoin.yaml)** - This template demonstrates how you can join a Windows AD Domain with CloudFormation using State Manager. Target is based on Tags.

**[WinAssociationDomainJoinAutomation.yaml](WinAssociationDomainJoinAutomation.yaml)** - This template demonstrates how you can join a Windows AD Domain with CloudFormation using State Manager and Automation for a more complex workflow with multiple steps. Target is based on Tags.

## License

This library is licensed under the MIT-0 License. See the [LICENSE](LICENSE) file.
