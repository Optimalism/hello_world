# hello_world

# dot product using a loop

def dot(K,L):
    if len(K)==len(L) and len(K)!=0:
        return sum([K[n]*L[n] for n in range(len(K))])
    else:
        return 0
