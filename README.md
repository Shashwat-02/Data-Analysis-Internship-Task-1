# Creating a List

my_list = [1, 2, 3, 4, 5]
print("List:", my_list)

my_list.append(6)
print("After adding element to list:", my_list)

my_list.remove(3)
print("After removing element from list:", my_list)

my_list[2] = 10
print("After modifying element in list:", my_list)

# Creating a Dictionary

my_dict = {'a': 1, 'b': 2, 'c': 3}
print("Dictionary:", my_dict)

my_dict['d'] = 4
print("After adding element to dictionary:", my_dict)

del my_dict['b']
print("After removing element from dictionary:", my_dict)

my_dict['a'] = 100
print("After modifying element in dictionary:", my_dict)

# Creating a Set

my_set = {1, 2, 3, 4, 5}
print("Set:", my_set)

my_set.add(6)
print("After adding element to set:", my_set)

my_set.remove(3)
print("After removing element from set:", my_set)
