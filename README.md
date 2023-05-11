# Write-a-Python-program-to-replace-dictionary-values-with-their-sum

my_dict = {'a': 10, 'b': 20, 'c': 30, 'd': 40}
total = sum(my_dict.values())
for key in my_dict:
 my_dict[key] = total
print(my_dict)
