# Notes

## Parson Data Structures

- `json_array_t` - Dynamic array struct.
- `json_value_t` / `JSON_Value` - Represents a generic type.
  - `JSON_Value-Type` - Enum indicating the type of a value.
  - `JSON_Value_Value` - Union containing the actual value.

## Rewriting Methods

- `json_array_t->items` will be the dynamic array.
- To keep the interfaces as much as possible, it seems like I need to continue using `JSON_Array` wrapper as the return type.
- Do I continue mainttaining `count` and `capacity`?
