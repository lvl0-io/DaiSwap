# DaiSwap Smart Contract 🚀

The DaiSwap smart contract provides an easy and efficient way to swap DAI for WETH using the Uniswap V3 protocol. This contract integrates with Uniswap's SwapRouter to enable seamless token swaps directly from your wallet. 🔄

## Features 💡

    Swap DAI to WETH: Utilize Uniswap's powerful liquidity pools for trading DAI for WETH.
    Minimal Overhead: Simple and efficient contract design.
    User-Friendly: Designed with the end user in mind for straightforward interactions.

## Functions 🛠️

swapExactInputSingle

  Swap a specified amount of DAI for as much WETH as possible based on current pool liquidity.

Parameters:

    amountIn: Amount of DAI you want to swap.

Returns: The amount of WETH received from the swap.

swapExactOutputSingle

  Swap DAI for a fixed amount of WETH, specifying the maximum amount of DAI you are willing to trade.

Parameters:

    amountOut: Desired amount of WETH.
    amountInMaximum: Maximum amount of DAI you are willing to spend.

Returns: The actual amount of DAI spent to receive the desired WETH amount.

Setup and Usage 🚀

    Approve DaiSwap: Before interacting with the contract, ensure you approve it to spend your DAI tokens.
    Call Swap Functions: Use either swapExactInputSingle or swapExactOutputSingle based on your trading preference.
    Receive WETH: After a successful swap, WETH will be transferred to your wallet.

Deployment 📡

    Network: Ethereum Mainnet
    Swap Router Address: 0xE592427A0AEce92De3Edee1F18E0157C05861564 (Uniswap V3 Router)
    DAI Address: 0x6B175474E89094C44Da98b954EedeAC495271d0F
    WETH9 Address: 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2
    Pool Fee: 0.3%

Safety and Security 🔒

The DaiSwap contract ensures safety through:

    Using Uniswap's trusted TransferHelper library.
    Careful handling of token transfers and approvals.

Contributions and Feedback 🌟

Your contributions and feedback are welcome! Feel free to open issues or pull requests in our GitHub repository.
Disclaimer ⚠️

This contract is provided as-is with no warranty. Users should ensure they understand the risks involved in DeFi token swapping.

Happy swapping with DaiSwap! 💫🔁💰
