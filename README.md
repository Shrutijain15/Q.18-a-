# Q.18-a-
def convert_to_binary(num):
  if num>0:
     convert_to_binary (num // 2)
    print(num%2, end='')

# test the function
convert_to_binary(10)
