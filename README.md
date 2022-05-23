# almaops.zookeeper
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)


# Requirements

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Dependencies
Java is required on target hosts.  

# Example playbook
```
- hosts:
    - servers
  become: true
  roles:
    - role: almaops.zookeeper
```

# License
[MIT](./LICENSE)

# Contributors
- [Valentin Gostev](https://github.com/ussrlongbow)

