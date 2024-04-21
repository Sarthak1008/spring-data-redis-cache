This project demonstrates how to integrate Google ReCaptcha v2 validation in a Spring Boot application.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have a valid Google ReCaptcha site key and secret key.
- JDK 8 or higher installed on your machine.
- Apache Maven installed.

## Setup

1. **Clone the repository:**
    ```shell
    git clone https://github.com/your-username/your-project.git
    ```

2. **Navigate to the project directory:**
    ```shell
    cd your-project
    ```

3. **Open `application.properties` file** and replace `YOUR_RECAPTCHA_SITE_KEY` and `YOUR_RECAPTCHA_SECRET_KEY` with your actual Google ReCaptcha site key and secret key.

4. **Build the project:**
    ```shell
    mvn clean install
    ```

5. **Run the application:**
    ```shell
    mvn spring-boot:run
    ```

6. **Access the application** in your browser at `http://localhost:8080`.

## Usage

1. Navigate to the registration page.
2. Fill in the registration form.
3. Complete the Google ReCaptcha challenge.
4. Submit the form.
5. If the ReCaptcha validation succeeds, you will be registered successfully.

![Redis image](https://miro.medium.com/v2/resize:fit:1167/1*7opjR94hTXrBPrYF7EDgqg.png)
