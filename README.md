# Calculator with GoLang

## Required

- Install and configuring GoLang
- Download this project


## Running

1. Open the *src* folder project on terminal
2. Type: *go run .*

## Endpoints
Endpoints and examples of appropriate response

- Addition: http://localhost:8000/calc/sum/{value1}/{value2}
  - ``` json
     {
        "result": "10"
     }
     ``` 
- Subtraction: http://localhost:8000/calc/sub/{value1}/{value2}
  - ``` json
     {
        "result": "5"
     }
     ``` 
- Division: http://localhost:8000/calc/div/{value1}/{value2}
  - ``` json
     {
        "result": "7"
     }
     ``` 
- Multiplication: http://localhost:8000/calc/mult/{value1}/{value2}
  - ``` json
     {
        "result": "30"
     }
     ``` 
- History: http://localhost:8000/calc/history
  - ``` json
    [
        {
            "time": "2022-08-19T02:13:52.853500749-03:00",
            "result": "6.00 - 6.00 = 0.00",
            "operation": "SUBTRACTION"
        },
        {
            "time": "2022-08-19T02:13:52.859714718-03:00",
            "result": "6.00 + 6.00 = 12.00",
            "operation": "ADDITION"
        }
    ]
     ``` 

## Testing

1. Open the folder project on terminal
2. Type: *sudo chmod +x ./smoke-test-calculator.sh*
3. Type: *./smoke-test-calculator.sh* to execute the test