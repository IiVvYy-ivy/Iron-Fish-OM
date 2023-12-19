# Iron-Fish-OM

Web3 Iron Fish Strategy

# Select Mining Pool

Link : https://ironfish.network/use/ecosystem?category=mining-pools

# Select Available Miners for Mining Pool

Link : https://ironfish.network/use/get-started/mining

# Example For Rigel

Link : https://github.com/rigelminer/rigel/releases/

# Start your Miner

sudo tar -xvf rigel-1.11.0-linux.tar.gz

cd rigel-1.11.0-linux

sudo vim iron.sh

##### Change configuraion in iron.sh 

./rigel -a **<algorithm_you_want>** -o stratum+tcp://**<mining_pool_host>**:**<mining_pool_port>** -u **<wallet_address>** -w my_rig --log-file logs/miner.log
