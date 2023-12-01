Silent Stealth Address Protocols
secp256k1 Demo (Bitcoin/Ethereum)

Stealth address protocols make it possible to transact on cryptocurrency networks using encrypted addresses.

If Alice is paying cryptocurrency to Bob in the usual way, Alice sends coins directly to an address Bob controls.  When using a stealth protocol, Alice instead sends the coins to an encrypted address which she derives from Bob's stealth 'master address'.  To observers, an encrypted address is indistinguishable from a normal address, but Bob will know it was created for him and will be able to unlock the corresponding wallet.

Silent (steganographic) versions of stealth protocols feature censorship-resistance and improved privacy by making it possible for Alice to transact without revealing she is using a privacy protocol.  When using the sample silent protocol implemented here, Alice won't need to take any action other than just send the usual transaction, and interlopers won't be able to distinguish her transaction from a normal one.

Demo is live here (including commentary and references):

https://gregsidal.github.io/silentstealth/

All content public domain except noble_secp256k1.js, which includes its own license.
