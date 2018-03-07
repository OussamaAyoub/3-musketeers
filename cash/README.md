# CASH

![Currency image](https://github.com/OussamaAyoub/3-musketeers/blob/master/cash/images/currency-converter.png)

Cash is a currency converter. 

## Table of content

- [Installation](#installation)
- [Usage](#usage)
    - [Commands](#commands)
    - [Currencies](#currencies)

## Installation

Download the library then install all the packages in the folder like below :
```
$ npm install 
```


## Usage

### Commands

Go to the bin folder.

The default command is :

```
$ node index.js <amount>
```

This command will convert the amount from USD to three default currency (EUR,GBP,PLN).

The next command use another argument :

```
$ node index.js <amout> <currency>
```

This command will convert the amount from the "currency" to the three default currency.

You can put in arguments all the currencies you target :

```
$ node index.js <amout> <currency> <target1> <target2>...
```

![Currency image](https://github.com/OussamaAyoub/3-musketeers/blob/master/cash/images/multiple-currencies-command.png)



### Currencies

They are 32 possible currencies in this library:

![Currency image](https://github.com/OussamaAyoub/3-musketeers/blob/master/cash/images/currencies.png)

