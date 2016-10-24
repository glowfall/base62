# base62

Compact and fast implementation of Base62 data encoding/decoding algorithm.

In comparison with simple Base64 it have one noticable advantage: the links encoded with Base62 contains only alpha-numerical symbols and can be safely used in cases where Base64 faced with undesirable behavior.

1. Base62 is safe for url-encoded links (just as url-safe version of Base64)
2. Base62 can be validated by more simple regexp
3. Base62 string can be fully selected by mouse double-click in any text editors or browser address bar
4. Base62 is the most natural and unambiguous way to encode your data in human-readable form :)

This Base62 implementation is not much slower (sometimes even faster) than typical implementations of original Base64 found in maven repositories.

Variations of Base62 algorithm widely used to represent authentication data in printable and easy-copyable form, for example to encode OAuth 2.0 `access_token` data.
