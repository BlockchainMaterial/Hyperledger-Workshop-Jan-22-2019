# Hyperledger-Workshop-Jan-22-2019

# Hyperledger Fabric Blockchain Prerequisites  
**Local MacOS set up** 

1. Download cURL latest version. 
- You can do this by installing [Homebrew](https://brew.sh) by running in your terminal : `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Run in CLI `brew install curl`
- Check if you have cURL installed by typing the following in your terminal: `curl -V`. The version should pull up. 
2. Install by clicking on [Docker for MacOS](https://docs.docker.com/docker-for-mac/install/) or update Docker to latest version if you already have it. It’s easy to do this, just open Docker and it will prompt you to update to latest version.
- Run `docker --version` . Docker version 17.06.2-ce or greater is required.
- Run `docker-compose --version`. Docker Compose version 1.14.0 or greater required. 
3. Download Golang for MacOS [here](https://golang.org/doc/install?download=go1.11.4.darwin-amd64.pkg).
-  Run `go` in your terminal to verify set up. The message “Go is a tool for managing Go source code” should show up. 
- Next run `export GOPATH=$HOME/go`. This sets the environment variable `GOPATH` to point at the Go workspace containing the downloaded Fabric code base. 
- You should (again, in the appropriate startup file) extend your command search path to include the Go `bin` directory. Run `export PATH=$PATH:$GOPATH/bin`.
4. Download Node by typing in: `brew install node`. 
- Note: If you already have node, run `brew upgrade node`
5. Download \[Python2\](https://hackercodex.com/guide/python-development-environment-on-mac-osx/) `brew install python@2` . 
- Check if you have it installed by running `python --version`.  Python 2.7 is required.

**Microsoft OS set up** 

See document here by scrolling down to Windows Extras: https://hyperledger-fabric.readthedocs.io/en/release-1.4/prereqs.html#id1

**IBM Cloud Blockchain Platform set up**

- Register for IBM Cloud (free): https://console.bluemix.net/
- Sign in and nagivate to IBM Blockchain Platform (first 30 days free): https://console.bluemix.net/catalog/services/blockchain
- More Info About Blockchain Platform: https://ibm.biz/Bd2Z5w

**References**

- Official Hyperledger Doc Prerequisites: https://hyperledger-fabric.readthedocs.io/en/release-1.4/prereqs.html 
- Docker: https://docs.docker.com/docker-for-mac/install/
- Golang: https://golang.org/dl/
- Homebrew: https://brew.sh/
- NPM: https://medium.com/@kkostov/how-to-install-node-and-npm-on-macos-using-homebrew-708e2c3877bd
- Python2: https://hackercodex.com/guide/python-development-environment-on-mac-osx/




 
 

