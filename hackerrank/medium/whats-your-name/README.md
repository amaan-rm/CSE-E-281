# What's Your Name?

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

You are given the firstname and lastname of a person on two different lines. Your task is to read them and print the following:

Hello `firstname` `lastname`! You just delved into python.

 **Function Description** 

Complete the  *print_full_name*  function in the editor below.

 *print_full_name*  has the following parameters:

- string first: the first name
- string last: the last name

 **Prints** 

- string: 'Hello ! You just delved into python' where and are replaced with and.

 **Input Format** 

The first line contains the first name, and the second line contains the last name.

 **Constraints** 

The length of the first and last names are each ≤.

 **Sample Input 0** 

```
Ross
Taylor

```

 **Sample Output 0** 

```
Hello Ross Taylor! You just delved into python.

```

 **Explanation 0** 

The input read by the program is stored as a string data type. A string is a collection of characters.

## Solution

**Language:** Python  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-10-20T10:59:53.079Z  

```py
def print_full_name(first_name, last_name):
    
    print("Hello",first_name,last_name + "! You just delved into python.")
    

```

---

[View on HackerRank](https://www.hackerrank.com/challenges/whats-your-name/problem)