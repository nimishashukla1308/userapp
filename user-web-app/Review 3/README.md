# Currency Converter GUI Application

A Java-based currency converter application with a graphical user interface that allows users to convert between different currencies in real-time.

## Features

### 1. Core Feature Implementation

- **Currency Conversion Engine**
  - Support for multiple international currencies with up-to-date exchange rates
  - Bi-directional conversion between any two selected currencies
  - Decimal precision handling for accurate conversion results

- **User Interface Components**
  - Clean and intuitive graphical interface built with Java Swing/JavaFX
  - Currency selection dropdowns for both source and target currencies
  - Input field for amount with real-time validation
  - Clear display of conversion results
  - Reset button to clear all fields

### 2. Error Handling and Robustness

- **Input Validation**
  - Real-time validation of numeric input
  - Prevention of invalid characters and negative numbers
  - Clear error messages for invalid inputs

- **Exception Management**
  - Graceful handling of network errors during exchange rate updates
  - Fallback to cached exchange rates when network is unavailable
  - Comprehensive error logging system
  - User-friendly error messages and recovery options

### 3. Integration of Components

- **Architecture**
  - Model-View-Controller (MVC) design pattern implementation
  - Modular code structure with clear separation of concerns
  - Integration of exchange rate API service
  - Local data persistence for frequently used conversions

- **Data Management**
  - Efficient caching system for exchange rates
  - Regular updates of currency exchange rates
  - Proper resource management and cleanup

### 4. Event Handling and Processing

- **User Interaction**
  - Responsive event listeners for all UI components
  - Real-time conversion updates as user types
  - Smooth handling of currency selection changes
  - Keyboard shortcuts for common actions

- **Background Processing**
  - Asynchronous exchange rate updates
  - Non-blocking UI during network operations
  - Progress indicators for long-running operations

## Technical Requirements

- Java JDK 11 or higher
- Internet connection for live exchange rates
- Minimum screen resolution: 800x600
