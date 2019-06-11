## 0.15.6
   
- upgrade `analyzer` to version `^0.36.0`

## 0.15.4

- fix set null values to attributes (fixes: #45)

## 0.15.3

- Enhance serialization of generics
- Add ability to deserialize generics
- upgrade `analyzer` to version `^0.34.0`
- upgrade `serializable_core` to version `^0.11.2`

## 0.15.2

- upgrade `analyzer` to version `^0.33.0`
- upgrade `build_runner` to version `^1.0.0`
- upgrade `build` to version `^1.0.1`
- upgrade `serializable_core` to version `^0.11.1`

## 0.15.1

- fix deserialize class with default constructor with optional args (fix #37).
- deserialize immutable with wrong constructor-parameter name now is possible. However now it returns null for that parameter after deserializing instead throwing `NoConstructorFound` error.

## 0.15.0

- upgrade `serializable_core` to version `0.11.0` since
  this version now generates from methods which now allows
  convert objects from generic values.
- move `SerializedName` to `built_mirrors` library since
  the serialized name is now generated at build time

## 0.14.0

- upgrade `sourge_gen` to version `^0.9.0`
- upgrade `analyzer` to version `^0.32.0`
- upgrade `built_mirrors_core` to version `^0.9.0`
- upgrade `serializable_core` to version `^0.10.0`

## 0.13.3

- fix https://github.com/drails-dart/dson/issues/34

## 0.13.2

- fix error serializing immutable with optional parameters

## 0.13.1

- upgrade `source_gen` to version `^0.8.0`

## 0.13.0

- Upgrade `serializable_core` to version `^0.9.0`

## 0.12.0

- move files from `dson`
