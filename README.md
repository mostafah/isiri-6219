# ISIRI 6219 in JSON

This repo has the list of characters mentioned in the ISIRI 6219 standard in JSON format, so that programs can use them too.

Please note that ISIRI 6219 is old and does not reflect latest changes in Unicode. In particular, Unicode 6.3 introduced the simpler isolates to replace the embedding control characters, but ISIRI 6219 has not been updated to reflect that.

This repo does not cover or suggest these changes. The data in the JSON file is exactly what was published in the ISIRI 6219 standard. It’s only purpose is to provide the same data in a machine-readable format.

## Categories and Classes

Please refer to the standard itself for a better definition of this data.

The standard has marked some of the characters as optional. It also lists “forbidden” characters, which are not supposed to be used for Persian texts. The rest are mandatory ones. The `class` field in the JSON file shows one of these three states for each character.

The `category` field is extracted from the names of the tables in the standard that list the characters. There are seven categories:

- `control`
- `common_punctuation`
- `persian_punctuation`
- `math`
- `alphabet`
- `subsidiary`
- `diacritic`

Forbidden characters have no category.

## To Do

ISIRI 6219 has a Persian name for each character. It would be nice to include them too.

## License

Unfortunately, the standard doesn’t mention its license. Hence, I am not sure what if I can specify a license for this data extracted directly from it.

But since ISIRI 6219 is a national standard and is publicly available, you can probably use tis data however you like.