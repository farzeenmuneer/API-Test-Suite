# 🌐 API Test Suite

## Project Overview
Automated API testing suite using Postman with JavaScript assertions for REST API validation.

## Tools Used
- **Postman** - API testing tool
- **JavaScript** - For writing assertions
- **DummyJSON API** - Mock API for testing
- **SQLite** - For data integrity validation

## Test Coverage
| Endpoint | Method | Status | Assertions |
|----------|--------|--------|------------|
| /users | GET | ✅ PASS | 3/3 |
| /users/add | POST | ✅ PASS | 3/3 |
| /users/1 | PUT | ✅ PASS | 3/3 |
| /users/1 | DELETE | ✅ PASS | 3/3 |

## Test Results
- **Total Tests:** 4
- **Passed:** 4 ✅
- **Failed:** 0
- **Pass Rate:** 100%
- **Total Assertions:** 12
- **Assertions Passed:** 12

## Key Features
- Automated JavaScript assertions for status codes
- JSON schema validation
- Response structure validation
- API + SQL cross-validation (Integration Testing)
- Regression testing via Collection Runner
- Professional bug reports with tracking history

## Documentation
- [Test Case Summary](Documentation/Test_Case_Summary.txt)
- [Bug Report](Documentation/Bug_Report_001.txt)
- [UAT Guide](Documentation/UAT_Guide.txt)
- [Release Validation Report](Documentation/Release_Validation_Report.txt)

## Screenshots
All screenshots are saved in the `Screenshots/` folder:
- `01_GET_Request_Working.png`
- `02_GET_Test_Pass.png`
- `03_POST_Test_Pass.png`
- `04_PUT_Test_Pass.png`
- `05_DELETE_Test_Pass.png`
- `06_All_Tests_Pass.png`

## How to Run
1. Import the Postman collection from `Postman_Collection.json`
2. Open Postman
3. Click "Import" → Select the JSON file
4. Run the collection using Collection Runner

## JD Coverage
| Requirement | Status |
|-------------|--------|
| Functional Testing | ✅ |
| API Testing | ✅ |
| Integration Testing | ✅ |
| Regression Testing | ✅ |
| Defect Management | ✅ |
| Test Cases | ✅ |
| UAT Guides | ✅ |
| Release Validation | ✅ |
| SQL Data Validation | ✅ |
| Postman | ✅ |

---

**Created by: Farzeen Muneer**
