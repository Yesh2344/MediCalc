# MediCalc: A Medical Calculation Library

MediCalc is a Java library designed to perform common medical calculations. It provides functionalities for calculating Body Mass Index (BMI), Ideal Body Weight (IBW) using different formulas (Devine, Hamwi), and Adjusted Body Weight (AdjBW) for obese patients. The library is designed for ease of use, accuracy, and extensibility, allowing healthcare professionals and application developers to integrate medical calculations seamlessly into their workflows.

## Features

*   **BMI Calculation:** Calculates BMI based on weight and height, providing both metric and imperial unit options.
*   **Ideal Body Weight (IBW) Calculation:** Implements Devine and Hamwi formulas for estimating IBW.
*   **Adjusted Body Weight (AdjBW) Calculation:** Calculates AdjBW for patients who are overweight or obese.
*   **Unit Flexibility:** Supports both metric (kg, cm) and imperial (lbs, inches) units.
*   **Clear and Concise API:** Easy-to-understand methods for performing calculations.
*   **Robust Error Handling:** Handles invalid input gracefully.
*   **Well-Documented Code:** Detailed JavaDoc comments for all methods.

## Getting Started

### Prerequisites

*   Java Development Kit (JDK) 8 or higher
*   Maven or Gradle (optional, for building from source)

### Installation

1.  **Download the JAR file:** Obtain the pre-built JAR file from the releases section (if available) or build it from the source code.

2.  **Add the dependency:** Include the JAR file in your project's classpath.

    *   **Maven:**

    ```xml
    <dependency>
        <groupId>com.example</groupId>
        <artifactId>mediccalc</artifactId>
        <version>1.0.0</version>
        <scope>system</scope>
        <systemPath>${basedir}/lib/mediccalc-1.0.0.jar</systemPath>
    </dependency>
    ```

    *   **Gradle:**

    ```gradle
    dependencies {
        implementation files('lib/mediccalc-1.0.0.jar')
    }
    ```

    (Adjust the paths and version accordingly.)

### Usage

Here's a simple example demonstrating how to use the MediCalc library:
