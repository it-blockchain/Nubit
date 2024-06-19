# Nubit Light Node Guide

![alt text](https://raw.githubusercontent.com/it-blockchain/Nubit/main/images/67.png)

# Official Nubit Documentation
https://docs.nubit.org/nubit-da/run-a-node

# Hardware for node
![alt text](https://raw.githubusercontent.com/it-blockchain/Nubit/main/images/2024-06-19%2018_10_34-Run%20a%20Node%20(Advanced)%20_%20Nubit.png)


To install the node, you only need to enter a single script. The node is installed with just one script.
# Output and Save PUBKEY and AUTHKEY: Run a Light Node with One Command
```bash

curl -sL1 https://nubit.sh | bash

```
# Output and Save PUBKEY and AUTHKEY:
The script outputs the generated PUBKEY and AUTHKEY, which are essential for node operations and security.

Ensure these keys are saved securely.
![alt text](https://raw.githubusercontent.com/it-blockchain/Nubit/main/images/2024-06-19%2019_00_51-Ubuntu.NODE%20CRYPTO%20-%20VMware%20Workstation.png)

# How shall I confirm my node is running correctly?
After running: 
```bash

curl -sL1 https://nubit.sh | bash

```
you should see the following message:
![alt text](https://raw.githubusercontent.com/it-blockchain/Nubit/main/images/2024-06-19%2019_06_12-Run%20a%20Node%20-%20FAQ%20_%20Nubit.png)
For further check:
```bash

$HOME/nubit-node/bin/nubit das sampling-stats --node.store $HOME/.nubit-light-nubit-alphatestnet-1

```
You will receive a response similar to the following to verify that your node is running successfully:
![alt text](https://raw.githubusercontent.com/it-blockchain/Nubit/main/images/13.png)
