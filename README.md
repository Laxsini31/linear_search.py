numbers=list(map(int,input("Enter numbers: ").split()))
x=int(input("Enter element to search: "))
for i in range(len(numbers)):
    if numbers[i]==x:
        print("Found at position",i)
        break
else:
    print("Not Found")
Output
Enter numbers: 4 2 7 1 8
Enter element to search: 1
Found at position 3
