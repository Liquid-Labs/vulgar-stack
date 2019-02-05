# Testing

## Golang testing standards

* White box *must* be organized in a separate 'xxx\_test' package in the same directory as the files being tested.
* Black box tests (of unexported functions) *should be used sparingly* and idealy not at all.
* Tests *should* make use of the [testify 'assert'](https://godoc.org/github.com/stretchr/testify/assert) and 'require) packages for readability.
* Tests *should not* use the testify 'suite' package. At time of last test, the suite would suppress useful stack traces on failure.
