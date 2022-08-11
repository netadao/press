![Neta DAO](https://github.com/netadao/press/blob/main/netadao-header.png)
# Neta DAO Juno Validator
#### Address: [junovaloper1f2jpv5sc6ur6yurq5w0t2chphrznpy8lfvj9vs](https://www.mintscan.io/juno/validators/junovaloper1f2jpv5sc6ur6yurq5w0t2chphrznpy8lfvj9vs)
**How is this validator running? Where is it based, who is running it, what is their experience, what commission are they taking?**  
Inspired by [Notional's edge validation architecture](https://github.com/notional-labs/notional), Neta DAO's validator is located in the Greater Toronto area on Osmosis-grade hardware specifications and is being run by contributor [Poroburu](https://twitter.com/poroburu), a decade-long crypto enthusiast, miner, and software engineer with experience in mechatronics. Through the DAO bootstrapping phase, Poro is charging $125 CAD (10% of the node's hardware and operational cost) per month.

**What steps are being taken to avoid slashing/jailing/double signing?**  
To avoid slashing, Poroburu is making use of a server-grade UPS, two internet lines (cable and DSL), and a [Tenderduty](https://github.com/blockpane/tenderduty) instance for notifications. To mitigate double signing, [Tendermint KMS](https://github.com/iqlusioninc/tmkms) runs on a Raspberry Pi 4 with a [YubiHSM2](https://www.yubico.com/product/yubihsm-2/) as a means of key signing with a layer of hardware security.

**What can staking JUNO offer delegators in the immediate term? At a later date?**  
We are not a gimmicky validator - no NFT incentives, giveaways, or kickbacks. We aim to add value to every chain we validate. Many worthy validators build infrastructure - as DAO purists, we intend to go even further to help build communities. Poro's first project post-launch is expanding documentation for Juno validation to assist new and aspiring validators.

**What plans are in store for decentralizing validator operations?**  
Steps will be taken to migrate remote signing from Tendermint KMS with Poro to using [Horcrux](https://github.com/strangelove-ventures/horcrux) when the DKG (distributed key generation) multisig signing feature is added and the Cosmos SDK allows validator key migration. These developments are being actively tracked and contact has been made both informally and through Github to follow and assist in development.
