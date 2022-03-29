# ASY
ASYAGRO token
ASYAGRO (ASY)  TECHNICAL DOCUMENTATION
############################################
name : "ASYAGRO"
symbol : "ASY"
decimals : 18
totalSupply : 7500,000,000
#############################################

Locks And Working:

1.	Transfer Locked token
Call TransferWithLock()
Input: TargetAddress, Amount, Time In Days

2.	Unclock token from wallet once locking period ends
Call unlockToken()
Input: targetAddress

Note: 
1.	All Input amount in the form of (amount X 10^18) where 18 is decimals in side token.
2.	Rest function works as usual as per standard smart contract.

	


