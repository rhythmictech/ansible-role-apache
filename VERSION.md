v1.0.0
---------------------------
- Add AlmaLinux 9 and 10 support
- Add MPM selection support (prefork, worker, event) for all Apache 2.4 distros
- Add apache_modular_config variable to replace brittle version checks in templates
- Modernize Ansible syntax: FQCNs, YAML dict syntax, quoted file modes
- Switch from ansible.builtin.yum to ansible.builtin.package for broad distro compatibility
- Remove lock_timeout from package tasks
- Update httpd.conf to use Apache 2.4 directive names (MaxRequestWorkers, MaxConnectionsPerChild)
- Bump minimum Ansible version to 2.10

v0.3.0
---------------------------
Significant changes for OracleLinux - Use HTTPD24 packages from Oracle Software Collection instead of httpd

v0.0.2
---------------------------
Added collectd support

v0.0.1
---------------------------
Initial Commit - working version
