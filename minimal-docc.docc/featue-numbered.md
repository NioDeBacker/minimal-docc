# 1. This is a  page with numbered headers

This is an overview of the page


## Preface

@Image(source: "image.jpg", alt: "A landscape", label: "image", numbered: true) {
    1.1 A landscape
}

@Image(source: "image.jpg", alt: "A landscape", label: "another image") {
    A landscape
}

A link to <doc:/article>

| col 1 | col 2 |
|-------|-------|
| row 1 | row 1 |
| row 2 | row 2 |
| row 3 | row 3 |
@Small { 1.2 table-one}

| col 1 | col 2 |
|-------|-------|
| row 1 | row 1 |
| row 2 | row 2 |
| row 3 | row 3 |
@Small { table-two}


A link to <doc:/article>


According to @Cite(key: '@key') this is expected.

@Math{
    $a^2 + b^2 = c^2$
}