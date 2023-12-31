
# 12/10/2023

# Units of informations

# Learning Objectives

- Be able to define:
    - bits and bytes
    - know that the 2<sup>n</sup> values can be represented with n bits

- Know:
    - quantities of bytes


# Bits and Bytes

Bit = the fundamental unit of information, represented as 0 and 1.

Byte = group of 8bits (it may vary)

    1,1,0,1,1,1,1,1,0 = 011111011

# States

    2^n = states, where n = bits

Example:

3 bits can be configured in 2<sup>3</sup> = 8 different ways:

    2^3 = 8

    (Base 2) 000,001,010,011,100,101,110,111

    (base 10): 0,1,2,3,4,5,6,7

# Bits

    [log2(n)] = bits, where n = states

states to bits = log<sub>2</sub>(states)

minimum number of bits required to represent the states = ceilling(log(base2)(states))

# Quantity Prefixes

Quantities of bytes = binary prefixes<sub>2</sub> or decimal prefixes<sub>10</sub>

one kibibytes is not equivalent to one kilobyte:

    1KiB (kibibytes) = 210B
    1kB (kilobyte) = 103B


## Binary Prefixes:

- kibi, ki - 2<sub>2</sub><sup>10</sup>
- mebi, Mi - 2<sub>2</sub><sup>20</sup>
- gibi, Gi - 2<sub>2</sub><sup>30</sup>
- tebi, Ti - 2<sub>2</sub><sup>40</sup>

## Decimal Prefixes

- kilo, k - 10<sup>3</sup>
- mega, M - 10<sup>6</sup>
- giga, G - 10<sup>9</sup>
- tera, T - 10<sup>12</sup>

---

# Historical Context

how many bist is inside something: explain how many bits is there in 10 kibibytes = ask for bits, times by 8 to figure it out.

Terms of **kilo**byte,**mega**byte, ect.., have often been used when **kibi**byte, **mebi**byte, ect.., are meant, causing confusion for consumers and developers.

---

# Further reading

- what is:
    - a ***nibble*** in relation to binary-hexadecimal conversion
    - the difference between ***kilobits*** and ***kilobytes***, and so forth
    - how many binary prefixes and decimal prefixes are there
