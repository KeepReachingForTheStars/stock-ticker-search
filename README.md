# stock-ticker-search

Search different stock tickers at once.

try:
    from googlesearch import search
except ImportError:
    print("no module named 'google' found")

# Search 1
query = "MSFT ticker"
print(str(query))
for j in search(query, tld="com", num=10, stop=10, pause=2):
    print(j)

# Search 2
query = "RCL ticker"
print(str(query))
for j in search(query, tld="com", num=10, stop=10, pause=2):
    print(j)

# Search 3
query = "SWRAY ticker"
print(str(query))
for j in search(query, tld="com", num=10, stop=10, pause=2):
    print(j)

# Search 4
query = "IDA ticker"
print(str(query))
for j in search(query, tld="com", num=10, stop=10, pause=2):
    print(j)

# Search 5
query = "FE ticker"
print(str(query))
for j in search(query, tld="com", num=10, stop=10, pause=2):
    print(j)
