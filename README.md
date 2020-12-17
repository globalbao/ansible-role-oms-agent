# Ansible Role OMS Agent

This Role downloads and installs the 32/64-bit OMS Agent on Windows instances. 

## Role Variables

Defined in `./defaults/main.yml`

* `url_omsagentx32`
* `url_omsagentx64`
* `MMAInstallerName`
* `binary_tmpdir_windows`
* `oms_workspace_id`
* `oms_workspace_key`

## Task Tags

Defined in `./tasks/windows.yml`

* `download`
* `install`

## Usage Examples

* ansible-playbook tasks/main.yml -vvv -- --tags="download,install"

## Role Development on Windows targets (Azure)

For instructions to develop this role on `Windows targets in Azure` using the `Molecule-Azure driver` refer to [https://jloudon.com/cloud/Ansible-on-Azure-Part-3/](hhttps://jloudon.com/cloud/Ansible-on-Azure-Part-3/)
