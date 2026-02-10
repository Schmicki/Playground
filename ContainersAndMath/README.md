# Containers & Math

A simple C++ STL replacement and linear algebra library.

## Containers

- **Array**: Dynamic resizable array. ([Array.hpp](Array.hpp#L38), [ArrayImpl.hpp](ArrayImpl.hpp#L32))
- **Map**: Array based map using binary search algorithm, optimized for small maps of less then a thousand entries. ([Map.hpp](Map.hpp#L38), [MapImpl.hpp](MapImpl.hpp#L32))
- **Set**: Array based set using a binary search algorithm, optimized for small maps of less then a thousand entries. ([Set.hpp](Set.hpp#L38), [SetImpl.hpp](SetImpl.hpp#L32))
- **ChunkedMap**: A map based on a 3D array for faster insertion and deletion with large numbers of elements. ([ChunkedMap.hpp](ChunkedMap.hpp#L45), [ChunkedMapImpl.hpp](ChunkedMapImpl.hpp#L44))
- **ChunkedSet**: A set based on a 3D array for faster insertion and deletion with large numbers of elements. ([ChunkedSet.hpp](ChunkedSet.hpp#L45), [ChunkedSetImpl.hpp](ChunkedSetImpl.hpp#L39))
- **String**: Dynamic string class with support for utf-16 and utf-32 conversion. ([String.hpp](String.hpp#L40), [StringImpl.hpp](StringImpl.hpp#L31))

## Linear Algebra

- **Vectors**: `Vec2`, `Vec3`, `Vec4` ([Vector.hpp](Vector.hpp#L42), [VectorImpl.hpp](VectorImpl.hpp#L42))
- **Quaternion**: `Quat` ([Quaternion.hpp](Quaternion.hpp#L40), [QuaternionImpl.hpp](QuaternionImpl.hpp#L42))
- **Matrix (Column-Major)**: `Mat4` ([Matrix.hpp](Matrix.hpp#L65), [MatrixImpl.hpp](MatrixImpl.hpp#L46))

## More

- **[TypeTraits](Templates.hpp#L30)**