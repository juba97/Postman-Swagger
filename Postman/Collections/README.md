# Reqres API Testing
This project runs automated tests on [https://reqres.in](https://reqres.in) using Postman and Newman.

## 📂 Structure
- `postman/collections`: Postman collection (your API test cases)
- `.github/workflows`: GitHub Actions workflow for CI/CD
- `newman-reports`: HTML test results (local)

## 🚀 Run Locally
Run the collection locally using Newman:

```bash
newman run postman/collections/reqres-api-collection.json 
