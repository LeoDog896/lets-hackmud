Adopted from https://hackmud.fandom.com/wiki/Security_Levels

## HIGHSEC

HIGHSEC scripts can get your balance (`accts.balance`), transactions (`accts.transactions`), upgrades (`sys.upgrades`), and your upgrade log (`sys.upgrade_log`)

## MIDSEC

Scripts are `MIDSEC` are capable of transferring GC out of your user's accts balance with `accts.xfer_gc_to`, can retrieve a list of every chat channel you are in with `chats.channels` (as well as join and leave them with `chats.join` and `chats.leave`) and can manage upgrades with `sys.manage`. 
