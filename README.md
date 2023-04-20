# Unit7Python
class Best_Passer:
    def __init__(self, passerA, height, ast):
        self.passerA = passerA
        self.height = height
        self.apg = ast

leader1 = Best_Passer('Magic Johnson', '6ft 9in', '11.2')

print(leader1.passerA)
print(leader1.height)
print(leader1.apg + ' per game')

leader2 = Best_Passer('John Stockton', '6ft 1in', '10.5')

print(leader2.passerA)
print(leader2.height)
print(leader2.apg + ' per game')

leader3 = Best_Passer('Chris Paul', '6ft in', '9.5')

print(leader3.passerA)
print(leader3.height)
print(leader3.apg + ' per game')
