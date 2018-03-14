# Cash


Cash is a library which permit to convert an amount of a currency to another. 

##Installation 

* Open a shell in your cash folder
* Run the following command to install the library 

```sh
? npm install
```

##How to use the library

These are the structure of the command line.

```sh
 $ cash <amount> <currency>

 $ cash <command>
```

Here are the commands you can use:

--save,  -s       Save currencies as default currencies
--help,  -h       Display help message
--version,  -v     Display version number

###For example

Here we are using the node server to run the index.js file, where the library is. 
If you want to convert 30 euros in usd, here is the right command line :

```sh
node index.js 30 eur usd
```
 You can find the list of currencies in the currencies.json file in the lib folder.


