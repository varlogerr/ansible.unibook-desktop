# ansible.unibook-desktop

```
mkdir -p ~/Projects/unibook \
  && cd ~/Projects/unibook \
  && git clone <repo-url> ./roles \
  && cp -R roles/_assets/installer ./ \
  && cp -R roles/_assets/ansible/* ./ \
  && sudo installer/mint-sylvia
```
Edit `unibook.yml` and `vars.yml` and run
```
sudo ansible-playbook unibook.yml
```
