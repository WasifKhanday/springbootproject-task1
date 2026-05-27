# Spring MVC Greeting Application

## Project Overview

This project is a simple Spring Boot web application developed using Spring MVC and Thymeleaf.

The application displays a greeting page and allows passing a custom name through a URL parameter.

---

## Technologies Used

- Java 17
- Spring Boot
- Spring MVC
- Thymeleaf
- Maven
- IntelliJ IDEA

---

## Application Features

- Greeting page
- Dynamic greeting using URL parameters
- Displaying a static image
- Thymeleaf template rendering

---

## Application Flow

1. User opens:

```
http://localhost:8080/greeting
```

2. Spring Boot receives the request.

3. `HelloController` handles the request.

4. The controller sends data to the Thymeleaf template.

5. The `greeting.html` page is rendered and displayed.

---

## Use Case 1 – Default Greeting

### URL

```
http://localhost:8080/greeting
```

### Result

Displays a greeting using the default value:

```
Hello, World!
```

### Screenshot

<img width="1907" height="956" alt="image" src="https://github.com/user-attachments/assets/f40da609-dea7-4b95-8819-d682675d56e4" />


---

## Use Case 2 – Custom Greeting

### URL

```
http://localhost:8080/greeting?name=Vistula
```

### Result

Displays:

```
Hello, Vistula!
```

### Screenshot

<img width="1913" height="956" alt="image" src="https://github.com/user-attachments/assets/d28e1133-50ca-4172-90b4-8f2d59659e9e" />


---

## Static Resources

The project contains a static image stored in:

```
src/main/resources/static/images
```

The image is displayed on the greeting page.

### Screenshot

<img width="578" height="606" alt="image" src="https://github.com/user-attachments/assets/dc9f175b-9efd-4b7a-ba48-f38b3898d93f" />


---

## Controller

The application uses a Spring MVC controller to process requests.

### Screenshot

<img width="1200" height="847" alt="image" src="https://github.com/user-attachments/assets/48d0d4af-21d4-4672-ad3d-a1687bc4a048" />


---

## Running the Project

1. Clone the repository.
2. Open the project in IntelliJ IDEA.
3. Run the Spring Boot application.
4. Open:

```
http://localhost:8080/greeting
```

---

## Author

Wasif Ashraf Khanday
