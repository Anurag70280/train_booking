# Train Booking System

This project is a simple C++ train booking system. It allows users to book seats on trains, manage vehicles, and handle user information.

## Project Structure

- `entities/`
  - `user.hpp`: Defines the User structure.
  - `train.hpp`: Defines the Train structure.
  - `vehicle.hpp`: Defines the Vehicle structure and conversion logic.
- `service/`
  - `bookingService.cpp`: Implements booking logic.
- `.vscode/`
  - `settings.json`: VS Code configuration for file associations.

## Build Instructions

1. **Ensure you have a C++ compiler installed** (e.g., g++, clang).
2. **Compile the project** (example using g++):
   ```
   g++ -I./entities -I./service main.cpp service/bookingService.cpp -o trainbooking
   ```
3. **Run the executable:**
   ```
   ./trainbooking
   ```

## Notes

- Update your IDE's include path to recognize header files in the `entities` directory.
- All source files should use double quotes for local includes, e.g., `#include "user.hpp"`.

## License

This project is for educational purposes.
