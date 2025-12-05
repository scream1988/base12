# base12
Air-Drop Eligibility Tool for Base Users
You can build a tool that checks if a wallet meets criteria like:

20 transactions

0.01 ETH bridged

interactions with specific contracts

Python: basic filter

tx_count = w3.eth.get_transaction_count(addr)
if tx_count > 20:
    print("Eligible")
