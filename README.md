## Portfolio

Below a curated collection of my most relevant contributions to Web3 security: public contests and private audits whose clients kindly agreed to share reports publicly.
- **10/24 Kakarot (L2 - Cairo0)** - [🏅1st place in team RadiantLabs](https://code4rena.com/audits/2024-09-kakarot), [report](https://code4rena.com/reports/2024-09-kakarot)
- **8/24 Reserve Core (DeFi - Go)** - [🏅1st place in team RadiantLabs](https://code4rena.com/audits/2024-07-reserve-core), [report](https://code4rena.com/reports/2024-07-reserve)
- **7/24 Optimism Superchain (L2 - Solidity)** - [🏅1st place in team RadiantLabs](https://code4rena.com/audits/2024-07-optimism-superchain), [report](https://code4rena.com/reports/2024-07-optimism)
- **5/24 Canto (Cosmos SDK - Go) on Code4rena** - [winnings forfeited for judging](https://code4rena.com/reports/2024-05-canto):
  - [![medium]![poc] Incomplete "cosmos.msg.v1.signer" protobuf annotation causes the "MsgSwapOrder" message to fail](https://github.com/code-423n4/2024-05-canto-findings/issues/4)
  - [![solo]![medium] Govshuttle module does not register its transaction MsgServer](https://github.com/code-423n4/2024-05-canto-findings/issues/5)
  - [![solo]![medium]![poc] Incorrect names provided in RegisterConcrete calls break LegacyAmino signing method](https://github.com/code-423n4/2024-05-canto-findings/issues/2)
  - [![low] QA report](https://github.com/code-423n4/2024-05-canto-findings/blob/main/data/3docSec-Q.md)
- **4/24 Renzo (Restaking - Solidity) on Code4rena** - [🏅1st place in team LessDupes](https://code4rena.com/audits/2024-04-renzo), [report](https://code4rena.com/reports/2024-04-renzo)
- **12/23 Ethereum Credit Guild (Staking app - Solidity) on Code4rena** - [7th place](https://code4rena.com/audits/2023-12-ethereum-credit-guild):
  - [![high]![poc] Double-counting of reward realization in ERC20RebaseDistributor self-transfers exposes distribution funds to theft and insolvency](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/291)
  - [![high]![poc] Updates to "creditMultiplier" can prevent bidding to pre-existing loan auctions](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/298)
  - [![medium]![poc] Newly created lending markets can be bricked by burning credit tokens](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/297)
  - [![medium]![poc] New distributions create unwanted fat-tail dilution of previous distributions](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/295)
  - [![medium]![poc] Rounding errors can cause ERC20RebaseDistributor transfers and mints to fail for underflow](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/294)
  - [![medium]![poc] ProfitManager's "creditMultiplier" calculation does not count undistributed rewards; this can cause value losses to users](https://github.com/code-423n4/2023-12-ethereumcreditguild-findings/issues/292)
- **11/23 usemoon.ai (Wallet backend - TypeScript/Go) private audit in solo**: [report](https://gist.github.com/3docSec/d91cadeaf9ea363f3eb68524d4c42a2d)
- **10/23 Party Protocol (Governance app - Solidity) on Code4rena** - [🥉3rd place](https://code4rena.com/audits/2023-10-party-protocol):
  - [![high]![poc] A host can abuse "abdicateHost" to inflate arbitrarily the number of hosts that voted a proposal](https://github.com/code-423n4/2023-10-party-findings/issues/331)
  - [![medium]![poc] ETHCrowdfundBase.delegationsByContributor can be manipulated via zero-value front-running donations](https://github.com/code-423n4/2023-10-party-findings/issues/334)
  - [![medium] PartyGovernanceNFT advertises but does not honor the ERC-4906 standard](https://github.com/code-423n4/2023-10-party-findings/issues/340)
  - [![medium]![poc] PartyGovernanceNFT.rageQuit burns tokens without honoring minWithdrawAmounts when amounts to be transferred are zero](https://github.com/code-423n4/202-310-party-findings/issues/333)
  - [![medium]![poc] ETH Crowdfunds that aim at raising exact amounts and require a minimum contribution can be bricked](https://github.com/code-423n4/2023-10-party-findings/issues/336)
  - [![low] QA report](https://github.com/code-423n4/2023-10-party-findings/blob/main/data/3docSec-Q.md)
- **9/23 Maia DAO Ulysses (LayerZero app - Solidity) on Code4rena** - [4th place](https://code4rena.com/audits/2023-09-maia-dao-ulysses):
  - [![high]![poc] Permissionless VirtualAccount.payableCall enables direct theft of assets](https://github.com/code-423n4/2023-09-maia-findings/issues/349)
  - [![high]![poc] Several instances of assumptions on LayerZero refundee can lead to refunded tokens being permanently locked](https://github.com/code-423n4/2023-09-maia-findings/isseus/351)
  - [![medium]![poc] Unused native tokens airdropped to RootBridgeAgent and BranchBridgeAgent are exposed to theft](https://github.com/code-423n4/2023-09-maia-findings/issues/350)
  - [![medium]![poc] Messages under-funded in remote gas temporarily halt Agents' communication via LayerZero](https://github.com/code-423n4/2023-09-maia-findings/issues/354)
  - [![medium]![poc] Incorrect source address decoding in RootBridgeAgent and BranchBridgeAgent’s _requiresEndpoint breaks LayerZero communication](https://github.com/code-423n4/2023-09-maia-findings/issues/348)
  - [![low] QA report](https://github.com/code-423n4/2023-09-maia-findings/blob/main/data/3docSec-Q.md)
- **8/23 GoodEntry (Uniswap V3 app - Solidity) on Code4rena** - [🏅1st place](https://code4rena.com/audits/2023-08-good-entry):
  - [![solo]![high]![poc] TokenisableRange's incorrect accounting of non-reinvested fees in "deposit" exposes the fees to a flash-loan attack](https://github.com/code-423n4/2023-08-goodentry-findings/issues/85)
  - [![high]![poc] V3Proxy swapTokensForExactETH does not send back to the caller the unused input tokens](https://github.com/code-423n4/2023-08-goodentry-findings/issues/64)
  - [![high]![poc] Incorrect Solidity version in FullMath.sol can cause permanent freezing of assets for arithmetic underflow-induced revert](https://github.com/code-423n4/2023-08-goodentry-findings/issues/58)
  - [![high]![poc] New from fees rework: fees can still be stolen with a flash-loan on GeVault](https://github.com/code-423n4/2023-09-goodentry-mitigation-findings/issues/16)
  - [![solo]![medium]: Incorrect boundaries check in GeVault's "getActiveTickIndex" can temporarily freeze assets due to Index out of bounds error](https://github.com/code-423n4/2023-08-goodentry-findings/issues/379)
  - [![medium] V3 Proxy does not send funds to the recipient, instead it sends to the msg.sender](https://github.com/code-423n4/2023-08-goodentry-findings/issues/463)
  - [![medium] User can steal refunded underlying tokens from initRange operation inside RangeManager](https://github.com/code-423n4/2023-08-goodentry-findings/issues/254)
  - [![medium]![poc] Transaction origin check in ROE Markets make Options positions opened by contract users impossible to reduce or close](https://github.com/code-423n4/2023-09-goodentry-mitigation-findings/issues/17)
  - [![medium] UniswapV3 trading fees are always locked in treasury instead of going back to the protocol users through GeVault](https://github.com/code-423n4/2023-09-goodentry-mitigation-findings/issues/18)
  - [![low] QA report](https://github.com/code-423n4/2023-08-goodentry-findings/blob/main/data/3docSec-Q.md)
- **6/23 Canto (Cosmos SDK - Go) on Code4rena** - [🥉3rd place](https://code4rena.com/audits/2023-06-canto):
  - [![high]![poc] DefaultMaxSwapAmount is 10x higher than spec for ETH](https://github.com/code-423n4/2023-06-canto-findings/issues/8)

## Blog posts
- 2023-10-26 [Testing for audits: there is no spoon](blog/23-10-26-testing-for-audits.md)

## CTF challenges authored
- [Proof of work @ ONLYPWNER.xyz](https://onlypwner.xyz/challenges/13)
- [Liquid Staking @ ONLYPWNER.xyz](https://onlypwner.xyz/challenges/15)
- [Seal 911 @ ONLYPWNER.xyz](https://onlypwner.xyz/challenges/16)

[high]: https://img.shields.io/badge/-HIGH-b02319 "HIGH"
[medium]: https://img.shields.io/badge/-MEDIUM-orange "MEDIUM"
[low]: https://img.shields.io/badge/-LOW-FFD700 "LOW"
[solo]: https://img.shields.io/badge/-Solo-lightblue "Solo"
[poc]: https://img.shields.io/badge/-Coded_PoC-lightgrey "Coded PoC"