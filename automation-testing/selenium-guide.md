# Selenium Automation Guide

## Topics Covered
- WebDriver Setup
- Locators
- Waits
- TestNG Integration

## Sample Java Snippet

```java
WebDriver driver = new ChromeDriver();
driver.get("https://example.com");
driver.findElement(By.id("username")).sendKeys("admin");