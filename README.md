Blockchain Explorer

This is a simple blockchain explorer that gets the most recent block
number and displays it in a web page.

First install the dependencies by running (from the root or top level folder):

npm install

Next, run the app from the command line:

npm start

This project uses Alchemy SDK as its main library.

e.q. alchemy.core.getBlockNumber()

NOTE: Use an environment variable for apiKey by creating an .env file. This will
be needed to connect to an Ethereum node on the Alchemy network.
