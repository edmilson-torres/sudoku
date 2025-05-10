# Sudoku Console Game

A Java-based Sudoku game for the console.  
This project demonstrates clean code organization, use of modern Java features, and a modular approach to building a classic puzzle game. The code is structured for maintainability and extensibility, making it suitable for further development or integration into larger systems.

## Interesting Techniques Used

- **Java Text Blocks:** Uses Java text blocks for multi-line string templates, improving readability for board rendering.
- **Streams and Lambdas:** Employs Java Streams and lambda expressions for concise data processing, such as board status checks and value updates.
- **Enum Usage:** Implements Java Enums for game status management, ensuring type safety and clarity.
- **Immutability and Encapsulation:** Uses `final` and `private` fields to enforce immutability and encapsulation, reducing bugs and side effects.
- **Input Validation Loop:** Demonstrates robust user input validation with loops to ensure correct values are entered.

## Notable Technologies and Libraries

- **Java 17+:** Leverages features from Java 17 and above, such as text blocks and enhanced switch statements.
- **IntelliJ IDEA Project Structure:** The project uses IntelliJ IDEA's module and project configuration files for streamlined development.

## Project Structure

```
.idea/
src/
  br/
    com/
      dio/
        model/
        util/
out/
```

## File References

- **Main entry point:** `src/br/com/dio/Main.java`
- **Board rendering template:** `src/br/com/dio/util/BoardTemplate.java`
- **Game logic:**  
  - `src/br/com/dio/model/Board.java`  
  - `src/br/com/dio/model/Space.java`  
  - `src/br/com/dio/model/GameStatusEnum.java`