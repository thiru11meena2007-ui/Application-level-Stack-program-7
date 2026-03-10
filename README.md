# Application-level-Stack-program-7

# Stack Program - Browser Back Function

stack = []

# Push operations (visiting pages)
stack.append("Google")
stack.append("YouTube")
stack.append("Wikipedia")

print("Browser History:", stack)

# Pop operation (Back button)
last_page = stack.pop()
print("Going back from:", last_page)

print("Current Browser History:", stack)



Browser History: ['Google', 'YouTube', 'Wikipedia']
Going back from: Wikipedia
Current Browser History: ['Google', 'YouTube']
