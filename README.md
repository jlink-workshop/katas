# Workshop Katas Setup

## Java

A minimal setup with Java, JUnit5, AssertJ and Mockito to get you started.
Based on Gradle and Java 17.

### Setup

```
git clone https://github.com/jlink-workshop/katas
cd katas-java
```

### Running Tests

```
./gradlew test
```

## Python

### Project layout

- `app` contains code to be tested
- `tests` contains tests definitions

### Setup

```
python -m venv venv
source venv/bin/activate
pip install --editable .
```

### Running Tests

Run all tests in file `tests/test_leap_year.py`:

```
pytest tests/test_leap_year.py
```

## Javascript

A minimal setup for JS with [jasmine](http://jasmine.github.io/)

### Setup

```
git clone https://github.com/jlink-workshop/katas
cd katas-js
```

Open folder in editor or IDE

    source code can be found in folder src
    test specs can be found in folder spec

### Running Tests

`<any modern browser>` SpecRunner.html