# ln(2) (Natural Logarithm of 2) Digit Files

This repository contains plain text files with the value of ln(2) (the natural logarithm of 2) truncated to different numbers of decimal places. Each file starts with `0.` followed by the digits after the decimal point (no extra whitespace or trailing newline).

## Files

| File                | Decimal digits | File size          |
| -------------------- | --------------- | ------------------- |
| `ln2_10.txt`         | 10               | 12 bytes             |
| `ln2_100.txt`        | 100              | 102 bytes            |
| `ln2_1000.txt`       | 1,000            | 1,002 bytes          |
| `ln2_10000.txt`      | 10,000           | 10,002 bytes         |
| `ln2_100000.txt`     | 100,000          | 100,002 bytes        |
| `ln2_1000000.txt`    | 1,000,000        | 1,000,002 bytes      |
| `ln2_10000000.txt`   | 10,000,000       | 10,000,002 bytes     |
| `ln2_50000000.txt`   | 50,000,000       | 50,000,002 bytes     |
| `ln2_100000000.7z`   | 100,000,000      | 100,000,002 bytes (uncompressed) |

> The `ln2_100000000.7z` archive needs to be decompressed.

## Example

`ln2_10.txt`:

```
0.6931471805
```

## Format

Each file follows the pattern:

```
0.<N digits of ln(2)>
```

where `<N digits of ln(2)>` is the first N digits of ln(2) after the decimal point.

## Source

Digits were truncated from a 120,000,000-decimal-digit reference file of ln(2) (only the first 100,000,000 digits are provided here).

## About

This project allows you to download a plain text file containing ln(2) (the natural logarithm of 2) to 100 million decimal places.
