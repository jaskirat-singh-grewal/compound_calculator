# Compound Calculator

A simple tool for calculating compound interest over time.

## Features

- Calculate compound interest based on principal, rate, time, and frequency
- Easy-to-use interface
- Fast and accurate results

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/compound_calculator.git
   cd compound_calculator
   ```
2. Run the calculator:
   ```bash
   python main.py
   ```

## Example

```python
# Calculate compound interest
principal = 1000
rate = 5  # percent
time = 10 # years
frequency = 4 # quarterly

amount = calculate_compound_interest(principal, rate, time, frequency)
print(f"Total amount after {time} years: {amount}")
```

## License

MIT License