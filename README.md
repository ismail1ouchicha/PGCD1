# PGCD1
def pgcd(x,y) :
    if x>y:
        while y!=0:
            z=x
            x=y
            x=z%y
    return x 
