# Spring AI ChatGPT Clone

This project is a ChatGPT clone built using Java, Spring Boot, Thymeleaf, and HTMX. It allows users to interact with a
ChatGPT-like interface.

## Setup

### Prerequisites

- Java 17
- Maven
- An `OPEN_API_KEY` environment variable must be set with your OpenAI API key.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/rupert-ong/spring-ai-chat-gpt-clone.git
    cd spring-ai-chat-gpt-clone
    ```

2. Set the `OPEN_API_KEY` environment variable:
    ```sh
    export OPEN_API_KEY=your_openai_api_key
    ```

3. Build the project using Maven:
    ```sh
    mvn clean install
    ```

### Running the Application

1. Start the Spring Boot application:
    ```sh
    mvn spring-boot:run
    ```

2. Open your browser and navigate to `http://localhost:8080`.

## Dependencies

- **Spring Boot Starter Web**: For building web applications, including RESTful applications using Spring MVC.
- **Spring AI OpenAI Spring Boot Starter**: For integrating with OpenAI's API.
- **Spring Boot Starter Thymeleaf**: For using Thymeleaf as the template engine.
- **HTMX Spring Boot Thymeleaf**: For using HTMX with Thymeleaf.
- **Spring Boot DevTools**: For development tools.
- **Spring Boot Starter Test**: For testing Spring Boot applications.

## Project Structure

- `src/main/java`: Contains the Java source code.
- `src/main/resources/templates`: Contains the Thymeleaf templates.
- `src/main/resources/application.properties`: Contains the application configuration.

## Environment Variables

- `OPEN_API_KEY`: Your OpenAI API key.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.