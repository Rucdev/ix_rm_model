# Add Model

```
ansible-playbook -e rm_dest=<path/to/rucdev/ix> \
                 -e structure=collection \
                 -e collection_org=rucdev \
                 -e collection_name=ix \
                 -e model=<path/to/model/model.yaml> \
                site.yml
```