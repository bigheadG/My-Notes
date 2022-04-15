# SLDC:(Software Development Life Cycle)
 https://stackify.com/what-is-sdlc/   
    
# BNF: (Backus Naur-Form)

 https://en.wikipedia.org/wiki/Backus–Naur_form
 https://zh.wikipedia.org/wiki/扩展巴科斯范式

# Grammer example:
    left recursive:
        A -> Aα | β 
        
        ex:
        A -> Aαα -> Aααααα...α -> βααααα...α
        
    right recursive:
        A ->  β R
        R -> αR | ε
        
        ex:
        A ->  βαR ->  βααR -> βαα....αR -> βαα....αε
        
# implementation method:
    And gate eq. if --> switch case --> state machine
    
    And : if then else
    Makov Chain: state machine (switch case)
