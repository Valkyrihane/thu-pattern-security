# thu-pattern-security
Tsinghua combinatorics project

![](/home/valky/me/github/thu-pattern-security/pattern.png)

### The goal

`pattern-security` computes the number of possible android pattern password, from one digit to another, with a given length. For example, going from the digit **1** to the digit **3** with a length of **3**, is doable in five ways: `1 2 3`, `1 4 3`, `1 5 3`, `1 6 3` and `1 8 3`

<p align="center">1 - 2 - 3</p>

<p align="center">4 - 5 - 6</p>

<p align="center">7 - 8 - 9</p>

## Dependencies

- Python 3.7

## Get started

```bash
git clone https://github.com/Valkyrihane/thu-pattern-security.git
cd thu-pattern-security

python3 pattern-security 1 3 3
# or
chmod 755 pattern-security
./pattern-security 1 3 3
```

## Usage

```
usage: pattern-security [-h] start [1-9] end [1-9] length [1-9]

Android pattern security

positional arguments:
  start [1-9]   Pattern starting digit
  end [1-9]     Pattern ending digit
  length [1-9]  Pattern length

optional arguments:
  -h, --help    show this help message and exit
```

