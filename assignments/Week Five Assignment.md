~~~{.ProofChecker .ZachTFL2019 guides="Fitch"}
1. A -> B, A -> C :|-: A -> (B /\ C)
2. (A /\ B) -> C :|-: A -> (B -> C)
3. A -> (B -> C) :|-: (A /\ B) -> C 
4. A \/ (B /\ C) :|-: (A \/ B) /\ (A \/ C)
5. (A \/ B) /\ (A \/ C) :|-: A \/ (B /\ C)
6. A \/ C, A -> C, B -> D :|-: C \/ D
7. B :|-: ~(A /\ ~A)
8. (A -> C) /\ (B -> C) :|-: (A \/ B) -> C
9. ~A -> ~B :|-: B -> A
10. A -> (B \/ C) :|-: (A -> B) \/ (A -> C)
~~~