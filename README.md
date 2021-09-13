# -crypto-price-quote--widget
The default code makes the request of 6 cryptocurrencies, Ada, Bitcoin, Monero, Litecoin, Dogecoin and Ethereum, 
to make changes, just change the request that is made within the php code snippet present in the head of the index.php file.

The project was developed to be used as a widget on wordpress pages, where the CSS style is automatically adapting to the space where it is inserted.

The project was designed to update crypto prices on page load, this can be changed by  associating with some other event to have a more constant update, at the end of the index.php file there is a snippet of javascript code that associates the captured values by coingecko api in their respective locations.
