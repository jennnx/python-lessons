# Basics

**Programming is the act of giving simple instructions to the computer**. It's about taking big, complex tasks into small steps that even an elementary student can perform.

**Examples**
****
1. Basic math
   1. Jay has 7 computers. I give him 2 more.
   2. The market cap in Q2 2022 was 45 Million. Next quarter, increase it by 3%.
2. If this then that
   1. If the weather is less than 0 degrees, print "freezing"
   2. If there are no more itmes in stock, cancel the order
3. Do an action X times

**A real program**

```
passwordFile = open('SecretPasswordFile.txt')

secretPassword = passwordFile.read()

print('Enter your password.')

   typedPassword = input()

if typedPassword == secretPassword:

   print('Access granted')
   
   if typedPassword == '12345':

       print('That password is one that an idiot puts on their luggage.')

  else:
  
   print('Access denied')
```

## Think in terms of lego blocks

There are only a few fundamental lego blocks (conditional, loops, variables, etc). Programming is about learning how to arrange and connect different blocks together to create something interesting.

Let's outline the typical learning path using this analogy.

1. **Learn the syntax**. When you begin building, you're colorblind. You can't tell one block apart from another. Your first step is getting used to the basic syntax. Most people don't even get past this part (2-3 weeks).
2. **Learn the different building blocks**. There are only so many blocks you can build with (conditional, loops, etc). Understanding each individual block and how it works is crucial. It will take you a while to master every one of them, but it will come with time (another 3-4 weeks).
3. **Learn to piece them together**. This is about finally combining your lego blocks and building a bigger project.

> "Computers are dumb. They are just very good at following instructions."