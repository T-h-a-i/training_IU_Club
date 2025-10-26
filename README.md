N = int(input("Nhập số lượng phần tử: "))
numbers = list(map(int, input("Nhập dãy các số nguyên dương: ").split()))
odd_sum = 0
for i in range(1, N, 2):
    odd_sum += numbers[i]
print(odd_sum)
