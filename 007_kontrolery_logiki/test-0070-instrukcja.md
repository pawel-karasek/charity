## Korzystamy z elementów konfiguracyjnych

W tej części:

Dodamy kontoler **IF** tak, aby:
- stworzyć opcjonalnie nowy post jeśli zmienna ${createPost} jest `true`:
  ```
  POST /post/add/new
  Content-Type: application/json
  
  {
    "title": "jmeter post",
    "body": "jmeter body"
  }
  ```
