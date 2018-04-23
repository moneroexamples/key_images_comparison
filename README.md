# Comparison of key images between new v7 and old v6 chains

All transactions and their key images in the v7 chain were compared with those in the old v6 chain (blockchain which did not upgrade to v7). The comparison covers a period of about 2 weeks and 2 days; blocks from 1546000 (the Monero upgrade to v7) (1546000) till 1557549 (for v6) and 1557059 (for v7).

So far, there have been 17,263 identical key images and 1,739 identical transactions identified between the chains. For the v6 chain, these represent about 64.1% of total number of key images and 29.3% transactions since the Monero upgrade. For the v7 chain, the percentages are %9.4 and 2.2% respectively. Coinbase transactions were not counted.

#### Examples of identical key images

##### Example 1

- v7: https://xmrchain.net/tx/58afb249d54b1ee4557b89570805e5740176cb2916734b6b34a1b2ba53d79495

- v6: (temporary link, can be slow and go off-line anytime): https://iste.serveo.net/tx/04022aae72b1d2cf63db665d14ffbca49ada2d8d3ddd47f7bebf9f9802d5cd15

Screenshot: https://i.imgur.com/edz0qy6.png (a single shared ring member marked)

##### Example 2

- v7: https://xmrchain.net/tx/b251cffc25af55d27d499c2c5c69559d3cf51cb4784fd57e91303966bb28f7bd

- v6: (temporary link, can be slow and go off-line anytime): https://iste.serveo.net/tx/f9cfff0c012ec1dea9eb89044ab13c64a8a258d4a0eda1466d2c2a859ce67728

Screenshot: https://i.imgur.com/LBAuPa7.png (multiple shared ring members marked)

#### Examples of identical transactions

- v7: https://xmrchain.net/tx/69052e4f9801b0d53cdc2516b0e5dcc93076ff95962c25cda64bda478e386cec

- v6: (temporary link, can be slow and go off-line anytime): http://iste.serveo.net/tx/69052e4f9801b0d53cdc2516b0e5dcc93076ff95962c25cda64bda478e386cec

Screenshot: https://i.imgur.com/AJvGlR1.png (since these transactions are identical, except block number, key images and all ring members are same)

#### Full results  

The csv file with complete list of identical key images and transactions found:

- https://github.com/moneroexamples/key_images_comparison/blob/master/files/out_same_ki.csv.zip

Screenshot of a part of the csv file: https://i.imgur.com/IDljkrE.png

#### Note
Please take this analysis for what it is. I’m not claiming that these findings are good or bad for Monero, nor even that this analysis is accurate, reliable and mistake-free.

Possible future updates and/or corrections will be done at  https://github.com/moneroexamples/key_images_comparison
