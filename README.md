# bug-bounty-tools

#Golang in Kali Linux

1. Start by open your web browser and visit https://golang.org/dl/
2. Download the latest version for Linux – “gox.xx.x.linux-amd64.tar.gz”
3. Open your terminal and navigate to your downloads folder 
	cd /root/Downloads
4. Extract the files
	tar -C /usr/local/ -xzf go1.13.6.linux-amd64.tar.gz
5. Add variables for GO by modifying “~/.bashrc”
	nano ~/.bashrc

Add the following paths to the end of the file__
	export GOPATH=/root/go-workspace
	export GOROOT=/usr/local/go
	PATH=$PATH:$GOROOT/bin/:$GOPATH/bin

6. Now we need to refresh the bashrc to get the updated variables
	source ~/.bashrc

7. go version


#anew tool in kali linux

1. sudo go install -v github.com/tomnomnom/anew@latest && sudo cp /root/go/bin/anew /usr/bin/
2. You can check the installation by running: anew -h command.







