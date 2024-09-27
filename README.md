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
