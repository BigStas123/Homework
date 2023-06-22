def polindrom(word):
    for i in range(0,len(word)//2):
        if word[i] != word[len(word) - i - 1]:
            return False
        else:
            return True