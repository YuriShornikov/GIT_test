# English words

# Thit document was create for new words

# i learn 5 words every day.

new_words = int(input('Введите количество изученных слов: '))
count = 0
While True:
    if new_words == 5:
        count += 1
        print('Количество дней: ', count)
    else:
        count += 1
        print(f'You missed', {count}, 'days, please continue to learn new words')    