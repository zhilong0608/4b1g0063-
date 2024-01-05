class Food:
    #食物類別 數性是米飯,重量,價格
    def __init__(self, rice, weight, price):
        self.rice = rice
        self.weight = weight
        self.price = price

    def describe(self):
        print(f"{self.rice} is a food with {self.weight} grams, priced at {self.price} dollars.")

    def cook(self):
        print(f" weight {self.rice}...")

    def eat(self):
        print(f" price {self.rice}!")

# 建立食物物件
food1 = Food("Rice blueRice", 200, 2.5)
food2 = Food("egg birdegg", 250, 3.0)
food3 = Food("apple big", 300, 4.5)

# 呼叫副函式
food1.describe()
food1.cook()
food1.eat()

food2.describe()
food2.cook()
food2.eat()

food3.describe()
food3.cook()
food3.eat()
