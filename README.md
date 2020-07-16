# Hi :wavehand:
I don't know how I'm the owner of this repo, [@Aareon](https://github.com/Aareon) made this.
PS: For the script kiddies reading this code, I think the pass and shiz over there were local creds on his computer, so don't get too excited.

# Discord-Netcoin-Bot
The files included in this repo are intended to be used as "cogs" in the RED Discord Bot.
These files are intended to function as a multi-functional tipbot for "Netcoin"

# Requirements
* Python 2.7(+)
* phpMyAdmin (I'm using XAMPP to host)
* The Netcoin wallet w/ RPC enabled.

# Functions
* Display general wallet information
* Display individual user balances (broken AF)
* Store user balance/tipping information in database
* Generate new deposit addresses for users
* Automatically add users to database (broken, have to do !balance twice to display after creating user in DB)
* Allow users to withdraw coins from the wallet with respect to how many coins they have in the DB
* Parse through wallet transaction data on a per-user basis to update database information
