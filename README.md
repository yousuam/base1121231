# base1121231
Monitoring Failed Transactions
tx_hash = "0x..."
receipt = w3.eth.get_transaction_receipt(tx_hash)

if receipt.status == 0:
    print("Transaction failed")
