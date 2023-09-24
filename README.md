# Infra tools 🥵
A set of tools to save time doing cool stuff with machines 😎🔥

## Setup VPS ⚙
- Update repos
- Upgrade Ubuntu (Arch still not supported btw 😭)
- Install Docker
- Setup SSH keys (I know my way is not the best for security reasons)

## Harbor ⚓
The install script is used to download and setup Harbor by setting up some environment variables related to your server and default passwords you provide.

### Todo
[ ] Remove comments from `harbor.yml` file
[ ] Create script to get an SSL certificate from Let's Encrypt
[ ] Give the user the option to generate a custom certificate or generate one from Let's Encrypt
[ ] Download `ca.crt` file after generating the certificates
