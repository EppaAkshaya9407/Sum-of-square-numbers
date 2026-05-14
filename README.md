# Sum-of-square-numbers
c = int(input("Enter a non-negative integer:"))
i = 0
j = int(c ** 0.5)
while i <= j:
    s = i * i + j * j
    if s == c:
        print(True)
        break
    elif s < c:
        i += 1
    else:
        j -= 1
else:
    print(False)
