## What is ABAP?
ABAP (Advanced Business Application Programming) is the programming language of SAP.

## Types of ABAP Programs

In ABAP, there are different types of programs, each used for specific purposes.

### 1. Executable Programs (Type 1)
- These are standalone programs.
- Start with `REPORT` statement.
- Used to perform tasks like reports, data processing, etc.

### 2. Module Pool Programs (Type M)
- Also called Dialog Programs.
- Used for complex user interactions (screens).
- Start with `PROGRAM` statement and use screens (`dynpros`).

### 3. Function Groups (Type F)
- Collections of reusable functions.
- Created using SE37.
- Not executable on their own.

### 4. Include Programs (Type I)
- Code blocks that can be reused in other programs using `INCLUDE` statement.
- Not executable directly.

### 5. Subroutine Pools (Type S)
- Programs that contain `FORM` routines.
- Used for reusability of logic.

### 6. Class Pools (Type K) and Interface Pools (Type J)
- Used for object-oriented programming.
- Class pools contain ABAP classes.
- Interface pools define interfaces.
