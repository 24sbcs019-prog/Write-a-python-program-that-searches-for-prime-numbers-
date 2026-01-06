# Write-a-python-program-that-searches-for-prime-numbers-
for a in range(15, 26):
    k = 0
    for i in range(2, a // 2 + 1):
        if a % i == 0:
            k = k + 1
    if k == 0 and a > 1:
        print(a)
Output;
17
19
23
