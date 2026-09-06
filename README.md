# Galactic Archive

Phase 1 (Journal):
- We use Final int constants to set the array size because it's used as a cap limit in lists.
- When I attempt to access an array index that contains null, the reference points to no object meaning any method or field access on it will fail at runtime verses one that contains an object will call its methods and access its fields normally.

Phase 2 (Journal):
- When you cast a double to an int, the fractional part is discarded and no rounding is performed.
- In Narrow Casting, Converting from a larger type to a smaller one (double → int) is unsafe because the type has a smaller range and precision which Java could lose data if it allowed it implicitly.
- Java forces you to explicit cast from a double to int instead of doing it automatically to prevent data loss in possible unsafe conversions.

Phase 3 (Journal):
- The two different array elements were able to reflect the same change to the RuneCore class because it's linked.
- Primitive variables Holds values directly because the value is stored in the variable itself and fixed in size while Reference variables Holds a memory address to an object stored elsewhere in the stack as a pointer.
