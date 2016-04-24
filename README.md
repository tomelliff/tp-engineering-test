# TP Engineering Test

```Your challenge is to write a piece of automation to run against a remote Ubuntu server. This should patch the server, install and enable UFW. Finally reboot the server and display the servers up time.```

### Running instructons:

- Edit `inventory` file to change the IP/hostname of the destination Ubuntu box (and optionally the user to login as)
- Run `ansible-playbook -i inventory test.yml`
