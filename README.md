# Funds LISA Could Save
Here is a list of hacks that should not happen as the smart contract vulnerabilities can be detected with LISA.

## About LISA
[L.I.S.A](https://agentlisa.ai/), an acronym for LLM-based Intelligent Security Analyzer, is an AI-powered security platform that utilizes the power of LLMs to perform smart contract security analysis, provide code insights and offer security recommendations.

## Try LISA
Everyone now has 500 free credits to scan smart contracts. LISA supports scaning github repo, on-chain contract address, and smart contract files. https://agentlisa.ai/docs

## Total Losses LISA Could Save
**$5,161,000**

## Security Incident Report

| Date| Project | Loss Amount | Vulnerability Title | LISA Security Scan Report Link | Alert News |
|-----|---------|-------------|---------------------|--------------------------------|-------------|
| 2025-07-29 | [SuperRare](https://superrare.com)         | $730K       | Incorrect access control in `updateMerkleRoot` allows unauthorized users to update the merkle root.                 | [Link](https://agentlisa.ai/scan/7c439f8c-3238-4a08-84c3-10ab69171d6c)       | [Alert](https://x.com/MetaTrustAlert/status/1949775292836508141)|
| 2025-07-15 | [Arcadia Finance](https://arcadia.finance)   | $3.5M       | Arbitrary external call in _swapViaRouter allows initiator to perform unauthorized swaps                            | [Link](https://agentlisa.ai/scan/7fda7f28-acca-48a5-96e1-d7307b2dc71b)       | [Alert](https://x.com/MetaTrustAlert/status/1945407744879604068)|
| 2025-07-11 | BankrollNetworkLife | $113K     | Profit calculation in distribute() does not cap to available balances, leading to over-issuance of dividends.       | [Link](https://agentlisa.ai/scan/6f6ed87f-6199-4b83-b661-763845234f1d)       | [Alert](https://x.com/TenArmorAlert/status/1943499612007932233) |
| 2025-07-05 | RANTToken         | $203K       | Incorrect burn amount calculation leading to price manipulation.                                                    | [Link](https://agentlisa.ai/scan/b0d8e7cd-a163-4c70-9e3d-372513a1041d)       | [Alert](https://x.com/MetaTrustAlert/status/1942159314795598206) |
| 2025-06-25 | [Silo Finance](https://silo.finance)      | $550K       | Profit calculation in distribute() does not cap to available balances, leading to over-issuance of dividends.       | [Link](https://agentlisa.ai/scan/6f6ed87f-6199-4b83-b661-763845234f1d)       |[Alert](https://x.com/MetaTrustAlert/status/1938228858597347750) |
| 2025-06-19 | [BankrollNetwork](https://bankroll.network)   | $65K        | Incorrect payout adjustment in sell function leads to dividend miscalculations                                      | [Link](https://agentlisa.ai/scan/72dc86e1-a95d-4e8c-a258-e758b3545f15)       | [Alert](https://x.com/Phalcon_xyz/status/1943518566831296566) |


## Miscellaneous
If you find more hacks detected that shouldn't be happening as the vulnerabilities can be found by LISA, please reach out to us [X](https://x.com/AgentLISA_ai), or create a pull request directly.
