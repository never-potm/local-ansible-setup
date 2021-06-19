# How to run Ansible locally

- We can run the ansible file using; `sudo ansible-pull -U <git http clone url>`.
- We need to give name of a playbook to run while running ansible-pull; `sudo ansible-pull -U <git http clone url> local.yml`
- By default; ansible tries to find a playbook called as local.yml in the repository.
