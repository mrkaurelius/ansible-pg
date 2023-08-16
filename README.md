# ansible playground

```sh
$ ansible-playbook -i inv.yml misc/ntp.yml # run ntp playbook
$ ansible-playbook -i inv.yml playbook/ansible-examples.yml --tags 'compose' # run plays with specific tag
```