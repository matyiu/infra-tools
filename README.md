# Infra tools 🥵
A set of tools to save time doing cool stuff with machines 😎🔥

## Setup VPS ⚙
- Update repos
- Upgrade Ubuntu (Arch still not supported btw 😭)
- Install Docker
- Setup SSH keys (I know my way is not the best for security reasons)

### Instructions
1. Run the following command: `./setup --username your_username --password your_password --ip your_machine_ip`

> [!NOTE]
> In case you already have your SSH key set up you don't need to put your password on the command


## Harbor ⚓
The install script is used to download and setup Harbor by setting up some environment variables related to your server and default passwords you provide.

### Instructions
1. Copy the `.env.example` and fill all the variables
2. Run the script `./install`

### Todo
- [ ] Remove comments from `harbor.yml` file
- [ ] Create script to get an SSL certificate from Let's Encrypt
- [ ] Give the user the option to generate a custom certificate or generate one from Let's Encrypt
- [ ] Download `ca.crt` file after generating the certificates
