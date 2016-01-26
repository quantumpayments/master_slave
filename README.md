# master_slave
master slave is a form of sync that allows replication between data stores

https://en.wikipedia.org/wiki/Master/slave_(technology)

# Replication

* mysql

http://dev.mysql.com/doc/refman/5.7/en/replication.html

# Sum of parts strategy

The `sum of parts` strategy is to have several smaller wallets that act idependently and feed into a master wallet.  For example a workbot could have a balance of 500k bits, and then have two wallets with a balance of 250k bits operating to `bubble` up credits without a fear of overflow.
