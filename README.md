# Member-Managed-LLCDAO
- Framework and guide to, as privately as possible, putting an LLC on chain

## Disclaimer!!!
This is not legal advice. I'm not telling you this is how you *should* do this,
I'm telling you how I did it.


## 1) Registered Agent 
- Its your responsiblity to find a registered agent / lawyer you can trust.
When you go to wyoming secertary of state and search the DAOs that have been published,
most ppl have doxxed themselves. You probably want to limit your dox surface to things 
that arent in the public record. I talked to my registered agent and altho they sign the
documents and their website requires a person to be listed as the managing member, 
I was able to put them down as the managing memeber through their UI, but Wyoming r
ecognized the contract address  

## 2) Operating Agreement
- Theres lots of ways to go about this and you definitely should consult a lawyer
or if youre an idiot like me yolo an internet search but I dont reccomend that 
- The one thing I can say for sure is that you must specify the wallet/contract 
that is either the managing member, or in **this repo**, a proxy for upgrading
the managing member.
  - There may be some legalise involved for specifying that the address ___
   is a proxy and not the member itself. I specified it and it was probably
   a bad idea not to consult a lawyer on this but I got an EIN at the end
   of the day (thats what i needed to register the business with services)
   

## 3) Ownership Proxy
- This ownership proxy is pretty simple and I included a backup address.
- A member managed LLC is either an EOA or a contract like a multisig,
  if you want to upgrade to a token controlled entity, or 
  *algorithmically maanged* entity, then its probably a good idea to 
  publish an amendment to your operating agreement before/after(consult lawyer)
  changing the owner of the proxy to an algorithmicly managed contract
  



