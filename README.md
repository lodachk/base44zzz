# base44zzz
Measuring Average Transaction Value
values = [tx["value"] for tx in block.transactions]
avg = sum(values) / len(values)
print("Avg value:", avg)
