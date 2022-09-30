# Workshop Katas Setup

## Java

A minimal setup with Java, JUnit5, AssertJ and Mockito to get you started.
Based on Gradle and Java 17.

### Project layout

- `build.gradle`: Gradle configuration file
- `src/test/java` contains all tests
  - `day1`: Starting test class for day 1
  - `day2`: Starting test class for day 2
  - `day3`: Starting test class for day 3

### Setup

```bash
git clone https://github.com/jlink-workshop/katas
cd katas-java
```

### Running Tests

```bash
./gradlew test
```

## Python

### Project layout

- `app` contains code to be tested
- `tests` contains tests definitions

### Setup

```bash
git clone https://github.com/jlink-workshop/katas
cd katas-python
python -m venv venv
source venv/bin/activate
pip install --editable .
```

### Running Tests

Run all tests in file `tests/test_leap_year.py`:

```bash
pytest tests/test_leap_year.py
```

## Javascript

A minimal setup for JS with [jasmine](http://jasmine.github.io/)

### Setup

```bash
git clone https://github.com/jlink-workshop/katas
cd katas-js
```

Open folder in editor or IDE:
- source code can be found in folder src
- test specs can be found in folder spec

### Running Tests

`<any modern browser>` SpecRunner.html
