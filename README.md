# Cw20 Coding Challenge

- [x] Anytime cw20 tokens are deposited add a new Expiration of 20 blocks higher than the current block height
- [x] If a user tries to withdraw cw20 tokens before expiration return a error
- [x] Write a new custom error for this
- [x] Complete the deposit 20 and withdraw test, use cw-multi-test to advance the block height to make sure the expiration is working properly
