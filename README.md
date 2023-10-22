# time-converter
  # Input an integer of the total number of seconds
total_seconds = int(input("Enter an integer (total seconds): "))

# find hours, minutes, and seconds
hours = total_seconds // 3600
minutes = (total_seconds % 3600) // 60
seconds = total_seconds % 60

# Display results
print(f"{total_seconds} seconds is equal to {hours} hours, {minutes} minutes, and {seconds} seconds.")
