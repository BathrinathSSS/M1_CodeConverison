## Introduction: 

  In digital electronics, the number system is used for representing the information. The number system has different bases and the most common of them are the decimal, binary, octal, and hexadecimal. Any digital system can understand only the optional number system. In these systems, digits symbols are used to represent different values. The system introduced in the project makes it easier to convert a data from one representation method/ number system to other. A person can convert data to a desired format with the help of this project in timely manner. Since, the digital logic circuitry requires numorous calculations of such type, it will be benificial to have such a system. 


## Features:

This system supports following types of data conversions (For positive integers): 
* Decimal to Binary
* Decimal to HexaDecimal
* Decimal to Excess-3
* Decimal to BCD
* Decimal to Octal

# How to Convert Decimal to Binary?
To convert numbers from decimal to binary, the given decimal number is divided repeatedly by 2 and the remainders are noted down till we get 0 as the final quotient. The following steps is considered as the decimal to binary formula that shows the procedure of conversion.

* Step 1: Divide the given decimal number by 2 and note down the remainder.
* Step 2: Now, divide the obtained quotient by 2, and note the remainder again.
* Step 3: Repeat the above steps until you get 0 as the quotient.
* Step 4: Now, write the remainders in such a way that the last remainder is written first, followed by the rest in the reverse order.
* Step 5: This can also be understood in another way which states that the Least Significant Bit (LSB) of the binary number is at the top and the Most Significant Bit (MSB) is at the bottom. This number is the binary value of the given decimal number.
How to Convert Decimal to Hex
Decimal to hexadecimal conversion can be achieved by applying the repeated division and remainder algorithm. Simply put, the decimal number is repeatedly divided by the radix 16. In between these divisions, the remainders give the hex equivalent in reverse order.

# How to convert decimal to hex?

* Step 1: If the given decimal number is less than 16, the hex equivalent is the same. Remembering that the letters A, B, C, D, E and F are used for the values 10, 11, 12, 13, 14 and 15, convert accordingly. For example, the decimal number 15 will be F in hex.
* Step 2: If the given decimal number is 16 or greater, divide the number by 16.
* Step 3: Write down the remainder.
* Step 4: Divide the part before the decimal point of your quotient by 16 again. Write down the remainder.
* Step 5: Continue this process of dividing by 16 and noting the remainders until the last decimal digit you are left with is less than 16.
* Step 6: When the last decimal digit is less than 16, the quotient will be less than 0 and the remainder will be the digit itself.
* Step 7: The last remainder you get will be the most significant digit of your hex value while the first remainder from Step 3 is the least significant digit. Therefore, when you write the remainders in reverse order - starting at the bottom with the most significant digit and going to the top- you will reach the hex value of the given decimal number.

# Octal number: 
         These are the numbers with base 8. If x is a number then the octal number is denoted as x8. It contains digits from 0 to 7. Example: (212)8, (121)8, etc.

Convert Decimal to Octal with Steps

* Write the given decimal number
* If the given decimal number is less than 8 the octal number is the same.
* If the decimal number is greater than 7 then divide the number by 8.
* Note the remainder, we get after division
* Repeat step 3 and 4 with the quotient till it is less than 8
* Now, write the remainders in reverse order (bottom to top)
* The resultant is the equivalent octal number to the given decimal number.


# Excess-3
Excess-3, 3-excess or 10-excess-3 binary code (often abbreviated as XS-3, 3XS or X3), shifted binary or Stibitz code (after George Stibitz who built a relay-based adding machine in 1937) is a self-complementary binary-coded decimal (BCD) code and numeral system. It is a biased representation. Excess-3 code was used on some older computers as well as in cash registers and hand-held portable electronic calculators of the 1970s, among other uses.



# What BCD means?

Binary coded decimal (BCD) is a system of writing numerals that assigns a four-digit binary code to each digit 0 through 9 in a decimal (base-10) numeral. The four-bit BCD code for any particular single base-10 digit is its representation in binary notation, as follows: 0 = 0000. 1 = 0001.



# 4W&#39;s and 1&#39;H

## Who:

1. Electrical and Electronics Engineering students
2. Digital circuit developer

## What:
A person can convert data to a desired format with the help of this project in timely manner.


## When:

At the initial stage of digital circuit designing operation.

## Where:

This project can be used by students as well as circuit developers where such calculations are needed.

## How:

This project can perform various calculations at the same and make user's task smooth and effortless.

# Detail requirements
## High Level Requirements:

| ID | Description | Status (Implemented/Future)|
|:---:|:---:|:---:|
|HLR-1| User shall be able to convert data from decimal system to another |Implemented|
|HLR-2| System output must display data without any error |Implemented|
|HLR-3| User shall be able to convert data between any number systems|Future|
|HLR-4| User shall be able to convert a negative data value|Future|

##  Low level Requirements:
| ID | Description | Status (Implemented/Future)|
|:---:|:---:|:---:|
|LLR-1|User shall be able to read the output data|Implemented| 

