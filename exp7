cipherText = "53‡‡†305))6*;4826)4‡)4‡);806*;48†8¶60))85;;]8*;:‡8†83(88)5†;46(;88*96*?;8)‡(;485);5†2:‡(;4956*2(5—4)8¶8*;4069285);)6†8)4‡‡;1(‡9;48081;8:8‡1;48†85;4)485†528806*81(‡9;48;(88;4(‡?34;48)4‡;161;:188;‡?;"
length = len(cipherText)
plainText = ['']*length
for i in range(length):
    currentChar = cipherText[i]
    if currentChar == '1':
        plainText[i] = 'a'
    elif currentChar == '2':
        plainText[i] = 'b'
    elif currentChar == '3':
        plainText[i] = 'c'
    elif currentChar == '4':
        plainText[i] = 'd'
    elif currentChar == '5':
        plainText[i] = 'e'
    elif currentChar == '6':
        plainText[i] = 'f'
    elif currentChar == '7':
        plainText[i] = 'g'
    elif currentChar == '8':
        plainText[i] = 'h'
    elif currentChar == '9':
        plainText[i] = 'i'
    elif currentChar == '0':
        plainText[i] = 'j'
    elif currentChar == ';':
        plainText[i] = 'k'
    elif currentChar == ':':
        plainText[i] = 'l'
    elif currentChar == '(':
        plainText[i] = 'm'
    elif currentChar == ')':
        plainText[i] = 'n'
    elif currentChar == '?':
        plainText[i] = 'o'
    elif currentChar == '—':
        plainText[i] = 'p'
    elif currentChar == '†':
        plainText[i] = 'q'
    elif currentChar == '‡':
        plainText[i] = 'r'
    elif currentChar == '¶':
        plainText[i] = 's'
    elif currentChar == '*':
        plainText[i] = 't'
    elif currentChar == '[':
        plainText[i] = 'u'
    elif currentChar == ']':
        plainText[i] = 'v'
    else:
        plainText[i] = currentChar
plainText = ''.join(plainText)
print(plainText)
