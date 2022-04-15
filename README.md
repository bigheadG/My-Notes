# SLDC:(Software Development Life Cycle)
    
    
# BNF: (Backus Naur-Form)
   https://zh.wikipedia.org/wiki/扩展巴科斯范式

# Grammer example:
    left recursive:
        A -> Aα | β 
        A -> Aαα -> Aααααα...α -> βααααα...α
    right recursive:
        A ->  β R
        R -> αR | ε

# implementation:
    And gate eq. if --> switch case --> state machine
