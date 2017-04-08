# patrick
Extension to the Mac say command. My son, Patrick, loves to use the `say` command on the Mac. However, he became frustrated that it only understood numbers up to 999 trillion. This Ruby script adds support for numbers all the way up to _centillion_ (303 zeros)!

### Install

Move the file `patrick` somewhere in your path.

### Usage

`patrick` acts just like `say`.

You can pass words into it as arguments:

```bash
patrick Hello World
```

You can pipe words into it:

```bash
echo "Hello World" | patrick
```

Or you can use STDIN:

```bash
patrick
Hello World!
```

Try it with a huge number :)

```bash
patrick 1000000000000000000
```
