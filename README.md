* about
* blockhashes


# about
This project provides blockhashes for the ChessCoin blockchain.

Why?
* there is currently no uptodate checkpoint :-(
  * see section in my blog: [2017 Dec 10: no uptodate synccheckpoint leaves your house open for manipulation attempts + does not help newcomers in terms of sync speed](https://github.com/chess-fan/thoughts)
  * and [this](https://github.com/COINFORCHESS/ChessCoin/issues/1) bug report

![cp](https://user-images.githubusercontent.com/34405095/33800354-b02b1f50-dd3e-11e7-9aed-5d61f48e9b89.png)


A bot will randomly post a current block hash of the ChessCoin network into here.
* Why randomly?
  * So it can not be manipulated time-wise when I cross-check with block explorers. I am paranoid... to block explorers (their site/DB may get hacked in a coordinated attempt, ...) and other services/clients...

You're invited to also post your own hashes
* the more people do that the more trustworthier this project becomes
* in your ChessCoin wallet type: _getblockhash HereYourBlockNumber_
  * this shows you then the hash (make a test and compare with one of the hashes from below)

Normally it would be enough to provide the newest blockhash since the new blockhash depends on the old ones
* but to also cross check my bot it's good to have a history (by the time stamp of this README file)
* also it's good to find out when the hashes differ when this fork/manipulation/... attempt may have started

Our goal:
* over time to make this very github project which you are reading right now "useless" by using another, better approach
* but until we add a [new checkpoint](https://github.com/COINFORCHESS/ChessCoin/issues/1) (and that regularly) this project will live on

# random blockhashes (blocknumber and then hash):
* 861705: 763a4d0414019751ca03e4044cab78a383afddea736f6e7a52d6a163cc7180ae
* 862153: 5cd7a0620ffeeaa0bff85a0fe0cc952cf23d3ce4cf8e6aa2a098ca578ecfdc7b
* 872127: 7b7b747b619d75a25fa35c8ecb6c18d33b8938bee5133fed5c6a80690df4dbce
* 872137: c4a6af325869fe479f6ef2f1b876c422ec83d16f68be30fb4614ab7d1cab0260
