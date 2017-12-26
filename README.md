* about
* achievements
* blockhashes


# about
This project provides blockhashes for the ChessCoin blockchain, and with this tries to give more trust into the blockchain.

Why?
* for 18 months there was no new checkpoint made :-(
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
  * never trust my bot either, best is to check several sources for the same block/hash
* also it's good to find out when the hashes differ when this fork/manipulation/... attempt may have started

Our goal:
* over time to make this very github project which you are reading right now "obsolete" by using another, better approach
* but until we add a [new checkpoint](https://github.com/COINFORCHESS/ChessCoin/issues/1) (and that regularly) this project will live on

# achievements of this project

* Dec 12/13: identify that a block explorer was on a fork + bring them back to the main chain, see [here](https://github.com/chess-fan/MCT/issues/15)

<br>

# random blockhashes (blocknumber and then hash):
* 900410: 5d3d0ab771e011696478fc6a35976609dc3c681943d607961d357f76ba574dc8
* 900390: b6255ffd3d93309343b93248877b4fda17b82dcd08d9d87e08c9d2611c0bec3a (Dec 26)
* 894841: dcd7065369694148bbf7130235fcc833184d56065e9bf6c6281da7f86f49fe4c
* 894821: c09a1961056337a550f6b134752cfd625c5e7bcd05046af8828f57aac01dfb15 (Dec 23)
* 890059: 51e404336c0bbc728824a007bfc8e62ea4daee76968a1b8431d78e23d1e45b4b
* 890039: d056dfdca4e5164b58dd4b0e0d6f5372b18a03e39d4938280db7e236c8627992 (Dec 20)
* 885752: 1658ce668a2b32ef4989956e12d02619334442d66c66efbe100dd5d422a641c8
* 885732: 102060a56bfb0b00b6ebbdfa56d2e6cffd471d057e1b8a57adedffeb3d9d0aa8 (Dec 18)
* 882242: 9da09086a6541eb44003de768c2949f918aba91df3a251722b819ae11cad1ee8
* 882222: 96901c4b2574a4f692ea17900c6b1410cf66e3fea7cbd3eee29cfdcde02301b4 (Dec 16)
* 877317: 8e0e1d972b2a39594e5bd16c5071de92f2b83dd23dab76f8554801129ea840a9 (Dec 13)
* 877300: 91170d2885e4c24305624700992752982a62177a04bc98f5366033e08d3f1d0e (Dec 13)
* 877286: 0fe448381232d4d52e3c8c606dbf08b1d20613f59aec270a58d99d330b2bdadb (Dec 13)
* 877256: 9825298cde92ffa64ea07a20908a9e62e1b64772e6917d9f885dc7244ce31e6d (Dec 13)
* 877215: b895a1eeb46bddb311e530345f881bd1114cd4bc4749f633de0c6a177a555c55 (Dec 13) - see [here](https://github.com/chess-fan/MCT/issues/15): at height 877216 a fork situation happened
* 877200: b30a0b1b3fcaa5ef63416e4668de925e8765687b0f833be5eebcde2e3d00a05e (Dec 13)
* 876099: 599bd06b583993429e8837ec7cbc4d65c9eaa5b79c48c3f792bc89d5f0f79940 (Dec 12)
* 876079: 4d0d8bb02a2804dc8de8c54df5999e07dbfca84e7c07e7c10c7271050aa76894 (Dec 12)
* 874590: 52e7c264b99d597ad6824a2401e4251637b63ec41b2f90eb4af45650c957fcdc (Dec 11)
* 874570: 111f84ef0929c2ab8ab9c2753481158d6151941bc1f5cd49e6ba8582155552f3 (Dec 11)
* 873128: 016e42801d2dcff8b3003fc5e23c5281a6d456bb70fc61d6bb930f487487ded5 (Dec 10)
* 873108: 6411e9eebddabca7e7712fd45907edf967e40b9b26dcfd6e3b62f9c7c19bff24 (Dec 10)
* 872137: c4a6af325869fe479f6ef2f1b876c422ec83d16f68be30fb4614ab7d1cab0260 (2017 Dec 9)
* 872127: 7b7b747b619d75a25fa35c8ecb6c18d33b8938bee5133fed5c6a80690df4dbce (2017 Dec 9)
* 862153: 5cd7a0620ffeeaa0bff85a0fe0cc952cf23d3ce4cf8e6aa2a098ca578ecfdc7b (2017 Dec 3)
* 861705: 763a4d0414019751ca03e4044cab78a383afddea736f6e7a52d6a163cc7180ae (2017 Dec 3)
* 407446: b9497356dd69b5134c9c6d344e6caf0eded4571acaa3448929f2b2029bb98016 (2017 Feb 22, see also [issue #1](https://github.com/chess-fan/blockhashes-of-ChessCoin/issues/1))
* 407425: f69d5b36e5748dc9944be0789bf032129d2e5f1f05ab93e7bf7aef0776e3b20a (2017 Feb 22, see also [issue #1](https://github.com/chess-fan/blockhashes-of-ChessCoin/issues/1))
