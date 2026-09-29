# Run the library demo

## Prerequisites

- Python 3.9 or newer
- JDK 17 or newer, with both `java` and `javac` available on `PATH`
- A terminal opened in the repository's top-level directory

No third-party Python packages or Java libraries are needed.

## Run

```text
python3 run.py demo
```

On Windows, if Python is available through the launcher instead of `python3`, run `py -3 run.py demo`.

The command compiles the Java sources in a temporary directory and runs a short library demonstration. It shows the borrowing limits, searches the catalog for a title, borrows a book, prints a loan receipt and due date, then returns the book and shows the return fee and remaining active loans. The demo uses a fixed date so its output is repeatable.
