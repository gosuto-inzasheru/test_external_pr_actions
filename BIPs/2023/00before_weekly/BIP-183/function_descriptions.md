| function                                           | description                                                                                                 |
|:---------------------------------------------------|:------------------------------------------------------------------------------------------------------------|
| disable()                                          | Disables a new creation of pools on a pool factory.                                                         |
| enableRecoveryMode()                               | Puts a pool into [Recovery Mode](https://medium.com/@0xSkly/inside-balancer-code-recoverymode-9af34ce5ab72) |
| pause()                                            | Stops trading on a pool.  Proportinal withdraws are still possible.                                         |
| setSwapFeePercentage(uint256)                      | Authorize change of swap fees for pools that delegate ownership to Balancer Governance: 0xba1ba1...         |
| startAmplificationParameterUpdate(uint256,uint256) | Start ramping up or down the A factor of a stableswap pool.                                                 |
| stopAmplificationParameterUpdate()                 | Stop A-factor change leaving the A-Factor at its currently set value.                                       |