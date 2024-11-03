# Cybersecurity
Koulutehtävä

# Logbook

A simple Python logbook for recording entries with timestamps. 

## Usage

1. **Logging an Entry**: Use `log()` to add a new entry to the logbook.
2. **Reading Logs**: Use `read_logs()` to read all entries.
3. **Clearing Logs**: Use `clear_logs()` to remove all entries.

## Example

```python
from logbook import Logbook

# Initialize the logbook
logbook = Logbook()

# Add a log entry
logbook.log("Started the logbook project.")

# Read all logs
print(logbook.read_logs())

# Clear all logs
logbook.clear_logs()

