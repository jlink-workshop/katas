# Workshop Katas Setup

## Java

A minimal setup with Java, JUnit5, AssertJ and Mockito to get you started.
Based on Gradle and Java 17.

### Project layout

- `build.gradle`: Gradle configuration file
- `src/test/java/` contains all tests
  - `day1`: Test class stub for day 1
  - `day2`: Test class stub for day 2
  - `day3`: Test class stub for day 3

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

A minimal setup for testing Python code with [pytest](https://docs.pytest.org/en/7.1.x/)

### Project layout

- `app/`: Code to be tested
- `tests/`: Test definition stubs
  - `test_leap_year.py`
  - `test_text_munger.py`
  - `test_prime_factorization.py`

### Setup

```bash
git clone https://github.com/jlink-workshop/katas
cd katas
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

A minimal setup for testing JavaScript code with [jasmine](http://jasmine.github.io/)

### Project layout

- `src/`: Code to test
- `spec/`: Test spec file stubs
  - `LeapYearsSpec.js`
  - `TextMungerSpec.js`
  - `PrimeFactorizationSpec.js`

### Setup

```bash
git clone https://github.com/jlink-workshop/katas
cd katas-js
```

### Running Tests

- Open `SpecRunner.html` with any modern browser

  e.g. on Mac:
  ```bash
  open SpecRunner.html -a /Applications/Safari.app
  ```

- Reload page to rerun tests
