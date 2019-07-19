# MasternodeScript

If you have old script, you have to remove it first for updated wallet installation.

rm masternodeinstall.sh

wget -q https://raw.githubusercontent.com/ClearNode/MasternodeScript/blob/master/masternodeinstall.sh

sudo chmod +x masternodeinstall.sh

./masternodeinstall.sh

When prompted to Enter your ClearCoin Masternode GEN Key.

Paste your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain. For check enter below command.

clr-cli getinfo

When Node Fully Synced enter below command for check masternode status.

clr-cli masternode status
