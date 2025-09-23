# SSH Remote Server Setup
Setting up a basic remote Linux server and configure it also including, fail2ban to prevent brute force attacks.

# Steps

### 1. Create a Remote Server
Register and setup a remote linux server on any provider e.g. a simple droplet on DigitalOcean which gives you $200 in free credits with the link. Alternatively, use AWS or any other provider.

- Log into your VPWS provider's control panel. In my case, simple droplet
- Create a new server.

### 2. Generate SSH Key Pairs
On your local machine, generate an SSH key pair to use for secure access to the server.

```bash
ssh-keygen
```

- 
- 
