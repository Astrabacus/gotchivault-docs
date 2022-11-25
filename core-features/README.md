# Core features

### Features of the Gotchi Vault <a href="#_5qtvy945nhwp" id="_5qtvy945nhwp"></a>

The Gotchi Vault consists of two smart contracts that allow the Vault Managers to safely manage your assets. With Gotchi Vault, you can maximize the return on (1) your GHST, and (2) your Aavegotchis.

#### GHST staking <a href="#_4qwstq4sjziu" id="_4qwstq4sjziu"></a>

With Gotchi Vault, you and hundreds of other community members deposit your GHST into the contract and receive back a corresponding amount of **vGHST**, a receipt token that represents a share of all the GHST held by the contract. Once you deposit your GHST, everything else is handled automatically on-chain, in a way that ensures that no one can compromise your funds. This bears repeating: **once you deposit your GHST into the Vault, no one can ever withdraw your funds except for you, not even the Vault Managers.**

Currently, the vGHST contract stakes all deposited GHST for wapGHST (wrapped Aave Polygon GHST), and stakes its wapGHST for $GLTR at [Aavegotchi.com](https://app.aavegotchi.com/stake-gltr).  The earned $GLTR is sold daily for more $GHST, resulting in direct $GHST yield for vGHST holders.   Additionally, wapGHST itself earns lending fees from [Aave](https://app.aave.com).

#### Aavegotchi/ERC721 staking <a href="#_1o9gylriaxml" id="_1o9gylriaxml"></a>

Aavegotchi users may not always have time to pet their Aavegotchi, and they may not have the resources or technical no-how to set up their own petting bot. Users may miss a [Snapshot vote](https://wiki.aavegotchi.com/en/dao#voting), or may not have the time to read up on a [SigProp or CoreProp proposal](https://wiki.aavegotchi.com/en/dao#type-of-proposals) before voting. As a result, users’ Aavegotchis may fall behind in their kinship or XP accrual. And with Gotchiverse Aavegotchi rentals, this is a whole other aspect of asset management an Aavegotchi owner needs to be familiar with to fully optimize their yield.

With Gotchi Vault, our smart contracts and designated bots take care of all of that, again in a decentralized, protected, and on-chain way. Using redundant petting methods (we use a combination of Orium's petting service and our own petting bot running on a secure server), we can ensure that your Aavegotchis never miss a pet, and maximize their kinship. And because our contract is [EIP-1271-compliant](https://eips.ethereum.org/EIPS/eip-1271) (see technical details below), the Vault Managers can vote _**on behalf of the contract itself**_.

**Note: due to a recent change in how Pixelcraft distributes XP for votes, depositors will need to continue to vote on the Aavegotchi snapshots to ensure they receive all voting XP.**

Just like with GHST staking, once your Aavegotchi is deposited into the Vault only you can withdraw that Aavegotchi. No one else involved in Gotchi Vault can trade it, list it for sale, or transfer it. Once an Aavegotchi is in the Vault, a user can always withdraw the Aavegotchi if they want to play in a minigame, or run around the Gotchiverse.

You can also now deposit your Realm parcels into the Vault.  Once in the Vault, anyone borrowing a Vault gotchi can channel on your parcel.  You will receive 10% of all alchemica channeled on your parcels, which will be distributed as a weekly airdrop.  **Note: at this point there are many more parcels in the Vault than there are Aavegotchis.  If your parcel alter is below Level 6, it is unlikely that anyone will channel on your parcel.**

