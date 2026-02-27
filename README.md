# duplicate-check
Contains Duplicate Problem Solution
def containsDuplicate(numbers):
    return len(numbers) != len(set(numbers))
