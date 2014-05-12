# Contents of this repo

## QTokenizer

A template-based string tokenizer implementation based on Chromiums'
`string_tokenizer` class.  This implementation aims to be more Qt friendly and
can parse temporaries. In particular, it is optimized for parsing QStrings
and can return QStringRefs instead of a deep-copy of the token.
