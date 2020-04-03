Get geth from https://drive.google.com/open?id=1Hpvi0LNEHjb1ioWWK3Ogoyr8Kc2hYgZx

Steps to run geth node

Step 1: Run 'init.bat' (Run only once during first setup)

Step 2: Run 'run.bat' (Used to run the geth node)

Step 3: Run below commands in geth console

	a)personal.newAccount() (Provide a password)
	b)personal.unlockAccount(eth.accounts[0], null, 2000) (Enter the earlier provided password)
	c)eth.defaultAccount = eth.accounts[0]
	d)miner.start(2)
	
	
