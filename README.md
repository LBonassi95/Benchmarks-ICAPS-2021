# Benchmarks-ICAPS-2021

# Commands used to launch planners/compilers

./sgplan522 -o DOMAIN -f PROBLEM -out OUTPUT

./mips PATH PROBLEM DOMAIN OUTPUT

./optic-cplex -T DOMAIN PROBLEM

./convert.sh DOMAIN PROBLEM dp 4 (ltl-poly)

./convert.sh DOMAIN PROBLEM OUT_PROB OUT_DOM dp (ltl-exp)

# Notes:

For ltl-exp and ltl-poly i choosed the encoding that maximises the overall performances, folders ltl-exp.tar.xz and ltl-poly.tar.xz.

The benchmarks used for tcore and the others pddl3 systems are in the pddl3_systems.tar.xz folder.

There is a folder called 'optic.tar.xz'. Insise there are two domains, storage_optic and tpp_optic, that were used in subsitution to the ones inside pddl3_systems.tar.xz folder. This choice was also done to maximize optic's performances.
