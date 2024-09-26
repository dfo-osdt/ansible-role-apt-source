# Ansible Role Apt Source

A simple role to configure the `sources.list` target on host systems. This role does not modify any files within `sources.list.d`.

## Variables

| Variable                        | Default Value                        |
|---------------------------------|--------------------------------------|
| `apt_source_repository`         | "http://archive.ubuntu.com/ubuntu"   |
| `apt_source_security_repository`| "http://security.ubuntu.com/ubuntu"  |
