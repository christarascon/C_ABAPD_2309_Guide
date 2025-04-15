## ABAP Classes and Objects

Object-Oriented Programming (OOP) in ABAP helps organize code into classes and objects.

### Class
- A blueprint for objects.
- Contains **attributes** (data) and **methods** (functions).
- Defined using `CLASS ... DEFINITION` and `CLASS ... IMPLEMENTATION`.

### Object
- Instance of a class.
- Created using `CREATE OBJECT`.

### Example

```abap
CLASS lcl_car DEFINITION.
  PUBLIC SECTION.
    METHODS: start_engine.
ENDCLASS.

CLASS lcl_car IMPLEMENTATION.
  METHOD start_engine.
    WRITE: 'Engine started'.
  ENDMETHOD.
ENDCLASS.

DATA: lo_car TYPE REF TO lcl_car.
CREATE OBJECT lo_car.
lo_car->start_engine( ).
