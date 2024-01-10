[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![CI](https://github.com/grycap/ansible-role-horovod/workflows/CI/badge.svg)](https://github.com/grycap/ansible-role-horovod/actions?query=workflow%3ACI)

Horovod Ansible role
=====================

Install Horovod.

Role Variables
--------------

The variables that can be passed to this role and a brief description about them are as follows.

	# gpu_support: false
	# horovod_install_env_vars:
	#   HOROVOD_WITH_MPI: 1
	#   HOROVOD_WITH_PYTORCH: 1
	#   HOROVOD_WITH_TENSORFLOW: 1
	#   HOROVOD_WITHOUT_MXNET: 1

Example Playbook
----------------
```
  - hosts: all
  roles:
  - { role: 'grycap.horovod' }
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
