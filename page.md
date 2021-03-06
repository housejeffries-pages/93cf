# JSON Variants

## Subsets of JSON

+ ### Son

    GitHub: [https://github.com/seagreen/Son](https://github.com/seagreen/Son)

    Disclaimer: my project.

+ ### Matrix.org Canonical JSON

    Spec: [Matrix.org appendices section 3.1](https://matrix.org/docs/spec/appendices.html#canonical-json)

    Note: This is a good spec.

+ ### JSON Canonical Form

    IETF draft: [draft-staykov-hu-json-canonical-form-00](https://tools.ietf.org/html/draft-staykov-hu-json-canonical-form-00)

    Note: the mapping from JSON Canonical Form to bytes is ambiguous. It doesn't specify which characters should be escaped or which escape sequences to use.

+ ### OLPC Canonical JSON (One Laptop Per Child)

    Description: [http://wiki.laptop.org/go/Canonical_JSON](http://wiki.laptop.org/go/Canonical_JSON)

    Note: not actually a subset of JSON. JSON forbids code points below %x20, but Canonical JSON (which is actually specified in bytes, not code points) allows all bytes to appear in strings.

+ ### I-JSON

    IETF: [rfc7493](https://tools.ietf.org/html/rfc7493)

## JSON


+ ### Itself

    Spec: [RFC 7159](https://tools.ietf.org/html/rfc7159)

    Note: There's also [ECMA 404](https://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf). A nice, short history of JSON specs is [here](https://www.tbray.org/ongoing/When/201x/2014/03/05/RFC7159-JSON).

## Supersets of JSON

+ ### YAML

    Spec: [1.2](http://yaml.org/spec/1.2/spec.html)

    Note: Claims to be a superset of JSON [here](http://yaml.org/spec/1.2/spec.html#id2759572). Stack Overflow discuesses whether this is actually the case [here](https://stackoverflow.com/a/26220257/1132816) (see the comments on the answer as well).

+ ### JSON5

    Website: [http://json5.org/](http://json5.org/)

+ ### Hjson

    Website: [https://hjson.org/](https://hjson.org/)

+ ### HOCON (Human-Optimized Config Object Notation)

    Description: [https://github.com/typesafehub/config/blob/master/HOCON.md](https://github.com/typesafehub/config/blob/master/HOCON.md)

+ ### Jsonnet

    Website: [http://jsonnet.org/](http://jsonnet.org/)

    Spec: [http://jsonnet.org/language/spec.html](http://jsonnet.org/language/spec.html)
