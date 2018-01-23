Service Linking with CloudForms and Ansible Tower
=================================================
CloudForms has the built-in capability to provision infrastructure elements using built-in dialogs that you can use to specify environment specific parameters. CloudForms robust service catalog and policy engine combined with Ansible Tower gives you greater flexibility to define your entire infrastructure and application stack to be completely defined in code as Ansible playbooks.


This demo shows the ability to link infrastructure resources (i.e. cloud instances or vms) provisioned with Ansible Tower into CloudForms. So that you can not only have end-users manage the entire lifecycle of services, its infra elements as well as give you the ability to define compliance policies and usage reports.

Requirements to Run the Demo
----------------------------

1. Latest version of CloudForms (4.5 or 4.6 beta) and Ansible Tower (3.2.x) installed in your environment
2. Add Ansible Tower as provider within CF
3. Infrastructure or Cloud provider defined for this example (i.e. VMware, Microsoft Azure or Amazon AWS)
4. Playbook to provision a VM or a Cloud instance.


