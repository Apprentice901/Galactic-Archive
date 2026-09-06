# Galactic Archive

Phase 1 (Journal):
- We use Final int constants to set the array size because it's used as a cap limit in lists.
- When I attempt to access an array index that contains null, the reference points to no object meaning any method or field access on it will fail at runtime verses one that contains an object will call its methods and access its fields normally.
