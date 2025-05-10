# API Testing & Documentation

This repository contains Postman tests and Swagger documentation for practicing REST API testing and documentation workflows using public or mock APIs.

## Structure

- `/postman/` – Contains Postman collections for API testing with test scripts.
- `/swagger/` –  Contains Swagger API documentation.
- `/environments/` - Contains environment configuration files for Postman.

  ## 🌍 How to Use Postman Environment

### 📥 Import the Environment

1. Go to Postman → (Settings) → **Environments**
2. Click **Import**
3. Select the file: `environment file` from `/environments/`

### ✅ Select the Environment

- Choose the imported environment from the **Environment dropdown** in the top-right corner of the Postman app

### 🧪 Use Variables in Requests

Instead of hardcoding values, use environment variables in your requests.  
For example:

``http
GET {{baseUrl}}/orders/{{order_id}}
``

## 🌍 How to Use Swagger

  Clone the repo: https://github.com/juba97/postman-swagger.git

1. **Go to Swagger Petstore UI**:
   - Visit the following URL: [Swagger Petstore UI](https://petstore.swagger.io)

2. **Insert the Raw URL of the OpenAPI YAML file**:
   - In the "Explore" field, paste the Raw URL of the `openapi.yaml` file.
     - Example: `https://raw.githubusercontent.com/your-username/your-repository/main/openapi.yaml`

3. **Click the "Explore" button**:
   - This will load the API documentation, and you will be able to interact with the API endpoints directly from the UI.

4. **Explore the API**:
   - You can now test the API methods, view the responses, and explore the parameters.
