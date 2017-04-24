# lab4
# A:
 0000000000000000 b .bss
 0000000000000000 d .data
 0000000000000000 p .pdata
# 0000000000000000 r .rdata
# 0000000000000000 r .rdata$zzz
# 0000000000000000 t .text
# 0000000000000000 r .xdata
#                  U __main
# 000000000000002e T _Z7averageif  (function name average with parameter integer and float)
# 0000000000000000 T _Z7averagePdRd  (function name average with parameter pointer double and regular double)
# 000000000000005a T main  (function name main)

#
# B:
#
# Result is : 1 8
#             4 8
#             4 8
#             8 8
# The first one is a char variable, a normal character variable is 1 byte and a pointer character or a sizeof character depends on your architecture, but is usually 4 or 8 bytes, and here is 8 bytes.
# Second is a integer variable, a normal integer variable is 4 bytes while a pointer integer is 8 bytes
# Third is a float variable, a normal float is 4 bytes same as the above result of integer.
# The last is a double, a normal double is 8 bytes while the pointer double is also usually 8 bytes which is depending on your architecture.
