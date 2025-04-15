## ABAP Data Types Overview

ABAP provides a variety of data types to define variables and structures.

### 1. Elementary Data Types
- `C` (Character)
- `N` (Numeric text)
- `D` (Date)
- `T` (Time)
- `I` (Integer)
- `F` (Floating point)
- `P` (Packed number, for currency)
- `STRING` (Variable length character string)

### 2. Complex Data Types
- **Structures**: Collection of fields (like a record)
- **Internal Tables**: Dynamic arrays to store rows of data

### 3. Reference Types
- Used to store references (like object pointers)
- Examples: `REF TO`, class instances

### 4. Constants and Variables
- Constants: `CONSTANTS: c_pi TYPE p VALUE '3.14'.`
- Variables: `DATA: lv_name TYPE string.`
