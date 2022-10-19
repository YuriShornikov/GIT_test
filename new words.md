# English words

# Thit document was create for new words

# i learn 5 words every day.

new_words = int(input('Введите количество изученных слов: '))
count = 0
exp = 0
lvl = 0
bonus = 0
While True:
    if new_words == 5:
        count += 1
        exp += new_words * 10
        lvl = exp // 250
        print('Количество дней: ', count)
        print('You lvl: ', lvl)
        if count == 10:
            bonus += 500
            exp = exp + bonus
            lvl = exp // 250
            print('congraduation, you know 50 new word')
            print('Please, repeat all new words')
    else:
        count += 1
        print(f'You missed', {count}, 'days, please continue to learn new words')    
