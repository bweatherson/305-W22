~~~{.ProofChecker .ZachTFL2019 guides="Fitch"}
1. (A \/ B) /\ (A \/ C) :|-: A \/ (B /\ C)
2. B :|-: ~(A /\ ~A)
3. (A -> C) /\ (B -> C) :|-: (A \/ B) -> C
4. ~A -> ~B :|-: B -> A
5. A -> (B \/ C) :|-: (A -> B) \/ (A -> C)
~~~