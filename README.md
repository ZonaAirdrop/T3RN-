# T3rn-Node
T3rn-Node Setup

### Claim Faucet BRN https://faucet.brn.t3rn.io/
### Check Explorer https://brn.explorer.caldera.xyz/address

 In addition, you need to prepare a Faucet in 4 Chain
 arbitrum-sepolia,base-sepolia,blast-sepolia,optimism-sepolia

 After Run Complete. Go To Discord Claim Role role executor and send Proof of Running Your Node On Server T1rn-Testnet

## General Instructions

Follow these steps to set up the T3rn Node Executor on your Ubuntu system.

### 1. Create and Navigate to the Directory

First, create a directory for the setup and navigate into it:

```bash
mkdir -p $HOME/T3rn-Node
cd $HOME/T3rn-Node
```

### 2. Update the System
Update your system packages to ensure you have the latest updates and security patches:

```bash
sudo apt update && sudo apt upgrade -y && sudo apt install screen
```

### 3. Download the Setup Script
To download the setup script, use one of the following commands:

```bash
curl -L -o buro-setup-t3rn-executor.sh https://github.com/CryptoBuroMaster/T3rn-Node/raw/main/buro-setup-t3rn-executor.sh
```


### 4. After downloading the script, make it executable:

```bash
chmod +x buro-setup-t3rn-executor.sh
```

### 5. Start a New screen Session

Create a new screen session with a name, e.g., t3rn-node:

```bash
screen -S t3rn-node
```

### 6. Run the Script
Execute the script to start the setup process:

```bash
./buro-setup-t3rn-executor.sh
```

Here's how you can add the README content to provide instructions for general settings, private keys, privacy, and network configuration:


### T3RN Executor Setup by CryptoBuro

This guide will help you set up the T3RN Executor with the `buro-setup-t3rn-executor.sh` script. Please follow the instructions carefully.

### GENERAL SETTINGS

1. Set your preferred Node Environment. 
   Example: export NODE_ENV
   
   ```bash
   testnet
   ```

## PRIVATE KEYS

1. Set the `PRIVATE_KEY_LOCAL` variable of your Executor, which is the private key of the wallet you will use. The example below is a fake generated key that should **not** be used in production:

## Executor Privacy

Read more about [Executor Privacy and Security](https://docs.t3rn.io/executor/become-an-executor/binary-setup) to ensure your setup is secure and private.

## NETWORKS & RPC

1. **Add your preferred networks to operate on.**  
   Example: export ENABLED_NETWORKS
   
   ```bash
   arbitrum-sepolia,base-sepolia,optimism-sepolia,l1rn
   ```



### 7. Check T3rn Node Status 

To reattach to the screen session later and check on the progress, use:

``` bash
screen -r t3rn-node
```
### Y/N = N ###

For more detailed information and advanced configurations, refer to the [T3RN Executor Setup Guide](https://docs.t3rn.io/executor/become-an-executor/binary-setup).

### Join Chanel For Update https://t.me/ZonaAirdr0p
