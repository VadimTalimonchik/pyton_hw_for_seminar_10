# Домашняя работа
## Задача 44.
Ниже представлен код генерирующий **DataFrame**, которая состоит всего из 1 столбца. Ваш задача перевести его в one hot вид. Сможете ли вы это сделать без **get_dummies**?

    import random
    lst = ['robot'] * 10
    lst += ['human'] * 10
    random.shuffle(lst)
    data = pd.DataFrame({'whoAmI':lst})
    data.head()