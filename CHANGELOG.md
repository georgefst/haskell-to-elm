# Changelog for haskell-to-elm

## Unreleased changes

## 0.3.2.0

- Fix support for the Aeson option `omitNothingFields`
- Add instances for some more numeric Haskell types: `Float`, `Int8`, `Int16`, `Int32`, `Word8`, `Word16`, and `Word32`
- Add instances for Elm `Array`s, which correspond to Haskell `Vector`s

## 0.3.1.0

- Generate correct JSON coders for record constructors for types with multiple constructors (https://github.com/haskell-to-elm/haskell-to-elm/issues/7)

## 0.3.0.0

- Make compatible with GHC 8.8
- Add support for parameterised types

## 0.2.1.0

- Update to `elm-syntax-0.2.0.0`, adding simplification of the generated definitions

## 0.2.0.0

- Merged the `HasElmType` and `HasElmDefinition` classes
- Merged the `HasElmDecoder` and `HasElmDecoderDefinition` classes
- Merged the `HasElmEncoder` and `HasElmEncoderDefinition` classes

## 0.1.0.1

- Tightened generics-sop bounds to < 0.5.0

## 0.1.0.0

- Initial release
