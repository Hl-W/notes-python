# logical reasoning by python  

# define known Booleans 
knowledge_base = {
    'A': True,
    'B': False,
    'C': True
}

# define logical rules 
rules = {
    'D': 'A and B',
    'E': 'A and C',
    'F': 'D or E'
}

# logical reasoning using eval for each rules 
for variable, rule in rules.items():
    knowledge_base[variable] = eval(rule, knowledge_base)

# print all Booleans 
for variable, value in knowledge_base.items():
    print(f'{variable}: {value}')
