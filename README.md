# story-Upgradev0.10.1-README.rm

```
sudo systemctl stop story

```cd $HOME
wget https://story-geth-binaries.s3.us-west-1.amazonaws.com/story-public/story-linux-amd64-0.10.1-57567e5.tar.gz
tar -xzvf story-linux-amd64-0.10.1-57567e5.tar.gz

```
cp $HOME/story-linux-amd64-0.10.1-57567e5/story $HOME/go/bin
source $HOME/.bash_profile
story version

```
sudo systemctl restart story

# check logs:

```
sudo journalctl -u story -f -o cat


