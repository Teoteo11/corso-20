# corso-20
Start with git

# Operazioni di commit
# Strada1
git add . [PREMO INVIO]
git commit -m "messaggio" [PREMO INVIO]
git push [PREMO INVIO]
# Strada2
git add . && git commit -m "messaggio" && git push [PREMO INVIO]
# Strada 3
git commit -am "messaggio" && git push

# Operazione di stash con etichetta custom
git stash save "test"
git stash apply stash^{/test}
