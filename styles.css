
def find_word_horizontal(crosswords,word):
    if not crosswords or not word : # if empty then return None
        return None
    for i in range(0, len(crosswords)):
        temp_str = ""
        for j in range(0, len(crosswords[i])):
            temp_str = temp_str + crosswords[i][j]
       
        if temp_str.find(word)>=0:
            return [i, temp_str.find(word)]
    return None

def find_word_vertical(crosswords,word):
    if not crosswords or not word : # if empty then return None
        return None
    for j in range(0, len(crosswords[0])):
        temp_str = ""
        for i in range(0, len(crosswords)):
            temp_str = temp_str + crosswords[i][j]
        
        if temp_str.find(word)>=0:
            return [temp_str.find(word), j]
    return None
def capitalize_word_in_crossword(crosswords,word):
    
    if not crosswords or not word : # if empty then return None
         return None

    elif find_word_horizontal(crosswords,word) != None:
        list_horiz = find_word_horizontal(crosswords,word)
        n = list_horiz[1]
        for i in range(n, len(word)+n):
            k = list_horiz[0]
            crosswords[k][i] = crosswords[k][i].upper()
   

     
    elif find_word_vertical(crosswords,word) != None:
        list_vertical = find_word_vertical(crosswords,word)
        m = list_vertical[0]
        for j in range(m, len(word)+m):
            t = list_vertical[1]
            crosswords[j][t] = crosswords[j][t].upper()
            
    return crosswords


