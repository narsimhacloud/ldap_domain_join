# ldap_domain_join

we need to create the variables group in the Azure library. so in that we can define the variables in the Variable group.

      ANSIBLE_VERSION: $(ansible.version)
      ANSIBLE_USERNAME: $(DemoVm.admin)
      DemoVm.admin_password: $(DemoVm.admin_password)
      VM_IP: $(DemoVm.VM_IP) 
      REALM_USER_PRINCIPAL: $(DemoVm.realm_user_principal)
      REALM_USER_PRINCIPAL_PASSWORD: $(DemoVm.realm_user_principal_password)
