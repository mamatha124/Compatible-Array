# Compatible-Array in python
n1 = int(input())
arr1 = [int(input()) for i in range(0,n1,1)]
n2 = int(input())
arr2 = [int(input()) for i in range(0,n2,1)]
if n1 != n2:
    print("Incompatible")
else:
    for i in range(n1):
        if arr1[i] < arr2[i]:
            print("Incompatible")
            break
    else:
        print("Compatible")
