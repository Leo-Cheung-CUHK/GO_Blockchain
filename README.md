# GO_Blockchain
Simple P2P Blockchain (Including POW) using GO

This code is try to combind several tutorial code into a p2p-with-all-function script.

You can find that mosts of the basic functions come from the tutorials below:

https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc
https://medium.com/@mycoralhealth/part-2-networking-code-your-own-blockchain-in-less-than-200-lines-of-go-17fe1dad46e1
https://medium.com/coinmonks/code-a-simple-p2p-blockchain-in-go-46662601f417

Thanks for the 'Blockchian tutorial' from 'Coral Health'.
You can find their all code in 
https://github.com/mycoralhealth/blockchain-tutorial 

Actually you should study and run the blockchain according to the tutorials above in order to get a better unstanding of my work. 


How to run:

Open terminal 1
Type: go run main_p2p.go -l 10000 -secio 
It will return the 

"2018/05/17 11:24:09 I am /ip4/127.0.0.1/tcp/10000/ipfs/QmXgqdTqsSeasKSiGF91GNQ7JjgUJHjdfDT9HKXBficZns
2018/05/17 11:24:09 Now run "go run main_p2p.go -l 10001 -d /ip4/127.0.0.1/tcp/10000/ipfs/QmXgqdTqsSeasKSiGF91GNQ7JjgUJHjdfDT9HKXBficZns -secio" on a different terminal
2018/05/17 11:24:09 listening for connections
"

Try to follow it.
And you can start to input the BPM and press Enter to send out.
