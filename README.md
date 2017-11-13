Monero miner.

Based on fireice_uk miner.

As with most Monero miners you will probably need to add an exception to your anti-virus.

If you don't trust the binary you can clone the code and build. 

Simply import folder into CMAKE,

Add two entries and make sure their BOOL value is false:

OpenSSL_ENABLE

MICROHTTPD_ENABLE

Configure using Win64.Then hit generate. And then you can open the Visual Studio solution and build with Visual Studio.

If this is useful to you please send XMR to 45zBmpQMRbvisgrViMojfqWEkdkKstkG5RsH4Rcpr6qGZhnHVzHKDQ8KMyQ1VPNxV6h94WV76cQHXGqQhptBmP9XBjU933V

By default the miner sends 1% to my developer pool. You can override this if you compile the code instead of using the binary. 
