# RamasConSquash
# PASOS A SEGUIR
- 1- Desde a main inicializas o git
    - git init
- 2- Fas o primer commit
    - git commit -m "A"
- 3- Fas o segundo commit
    - git commit -m "B"
- 4- Desde la main creas unha nova rama chamada colaborador
    - git branch colaborador
- 4.1- E creas unha nova java class chamada Colaborador
- 5- Cambias de rama
    - git checkout colaborador
- 6- Fas os 3 commits na rama colaborador e na java class de Colaborador
   - git commit -m "aC"
   - git commit -m "bC"
   - git commit -m "cC"
- 7- Volves a main
    git checkout main
- 8- Creas unha nova rama chamada lider
    - git branch lider
- 8.1- Creas outra nova java class chamada Lider
- 9- Cambias da rama main a rama lider e a java class de Lider
    - git checkout lider
- 10- Fas os 3 commits correspondientes
    - git commit -m "aL"
    - git commit -m "bL"
    - git commit -m "cL"
- 11 Volves para a rama main
    - git checkout main
- 12 Desde o IDE do intelilli de no apartado de git fas un merge squash co a clase Colaborador
- 13- Na main fas un commit
    - git commit -m "merge con squash de colaborador"
- 14-Desde o IDE do intelilli de no apartado de git fas un merge squash co a clase Lider
- 15 - Na main fas outro commit
    - git commit -m "merge con squash de lider"
