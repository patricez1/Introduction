# Introduction
def introduction():
    name = "Patricia Zhuge"  
    school_level = "Senior High School Student"
    interests = ["Motion Graphics", "Writing", "Urbanism"]  
    
    print(f"Hello! My name is {name}.")
    print(f"I am currently a {school_level}.")
    print("Some of my interests include:")
    
    for interest in interests:
        print(f"- {interest}")

if __name__ == "__main__":
    introduction()

#fish.py
def count_less_fish(fish):
    n = len(fish)
    result = []

    for i in range(n):
        count = 0
        for j in range(i):
            if fish[j] < fish[i]:
                count += 1
        result.append(count)

    return result


fish = [4, 3, 0, 5, 1, 2]

output = count_less_fish(fish)

print(output)

n = 6
fish = [4,3,0,5,1,2]

maxx = 0

for i in range(n):
    if fish[i] > maxx:
        maxx = fish[i]
print(maxx)


target = -10
fish = [4, 3, 0, 5, 1, 2]

target = -10
exist = False
for i in range(n):
    if fish[i] == target:
        exist = True
if exist:
    print("yes")
else:
    print("no")

for i in range(n):
    for j in range(i+1, n):
        if fish[i] + fish[j] == target:
            exist = True
if exist:
    print("yes")
else: print("no")