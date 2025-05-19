# current_datetime.py

from datetime import datetime

# Get the current date and time
now = datetime.now()

# Format the date and time
formatted = now.strftime("%Y-%m-%d %H:%M:%S")

# Print it
print("Current Date and Time:", formatted)
