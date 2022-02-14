import urllib.request,random
a,s=list(urllib.request.urlopen('https://www-cs-faculty.stanford.edu/~knuth/sgb-words.txt').read().decode('utf-8').split())[random.randint(0,5756)],""
while s!=a.upper():
    g,s=input("guess: "),""
    for i,l in enumerate(a):s+=l.upper() if l==g[i] else "("+g[i].upper()+")" if g[i] in a else "("+g[i].lower()+")"
    print(s)