# count even and numbers in python

list=[2,4,6,8,11,43,44]
even_count,odd_count=0,0

for i in list:
  if i%2==0:
    even_count +=1
  else:
    odd_count +=1
print("even numbers in the list",even_count)
print("odd numbers in the list",odd_count)
