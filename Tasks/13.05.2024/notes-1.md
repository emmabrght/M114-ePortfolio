## Dec to Hex:

1. Divide the decimal number by 16.
2. Write down the remainder (which will be a digit from 0 to 15) as the least significant digit (rightmost).
3. Repeat steps 1 and 2 with the quotient obtained in the previous step until the quotient becomes zero.
4. The hexadecimal representation will be the remainders written in reverse order.

## Large binary numbers separated by points:

The given binary number is broken into groups of 8 bits for better readability:

1100’0000 . 1010’1000 . 0100’1100 . 1101’0011

To convert this binary number to decimal, we'll first convert each group of 8 bits to its decimal equivalent, and then combine them.

Group 1: 1100'0000 = 192
Group 2: 1010'1000 = 168
Group 3: 0100'1100 = 76
Group 4: 1101'0011 = 211

Now, combining these decimal values:

192.168.76.211

So, the binary number 1100’0000.1010’1000.0100’1100.1101’0011 is equivalent to the decimal IP address 192.168.76.211.

## Converting ips to hex:

192.168.76.211

Hexadecimal:
192 = C0
168 = A8
76 = 4C
211 = D3

So, the hexadecimal representation is: C0.A8.4C.D3.

## Binary addition:

Binary numbers are added following a process similar to the way decimal numbers are added. There are only four math facts to remember when adding binary numbers. They are 0 + 0 = 0, 0 + 1 = 1, 1 + 0 = 1, and 1 + 1 = 10. Just like when adding decimal numbers that equal 10 or more, a 1 is carried over to the left, in binary addition, when the binary addition equals 10 or more in binary, then a 1 is carried over to the left as well.

## Task 7 explained:

To dimension the code width of the binary code for cabin counting of the Matterhorn-Express, where a total of 107 gondolas transport tourists from Zermatt to Trockener Steg, we need to find a binary number that can represent at least 107 gondolas.

To do this, we find the smallest power of 2 that is greater than or equal to 107. In this case:

2^7 = 128

Since
2^7 is greater than 107, we need at least 7 bits to represent 107 gondolas. Therefore, the code width of the binary code for cabin counting would be 7.

## Signed and unsigned

Unsigned = zero or positive

Signed = can be positive and negative

> Typically use a sign bit to indicate the sign of the number: 0 for positive and 1 for negative.

## Signed with 2nd complement

To represent -83 using two's complement notation, first, you need to determine its binary representation.

The binary representation of 83 is 01010011. To get the two's complement for -83, you need to flip the bits and add 1.

So, the one's complement of 83 would be: 10101100.

Then, add 1 to get the two's complement: 10101101.

So, in two's complement notation, -83 is represented as 10101101 in binary.
