# QA Automation Assessment

## Technology
- Playwright
- JavaScript
- Playwright Test
- APIRequestContext
- Page Object Model

## UI Automation

### Q1 - Locked Out User
- Login with locked_out_user
- Verify locked-out error message

### Q2 - Standard User
- Login
- Reset App State
- Add 3 products
- Verify checkout products and total
- Complete purchase
- Verify successful order
- Reset App State
- Logout

### Q3 - Performance Glitch User
- Login
- Reset App State
- Sort products Z-A
- Add first product
- Verify checkout information
- Complete purchase
- Verify successful order
- Reset App State
- Logout

## API Automation

### Q3 - Login
- Login with registered credentials
- Capture authToken

### Q4 - GET User
- Verify user name and email

### Q5 - PUT User
- Verify updatedAt timestamp

### Q6 - PATCH User
- Verify only requested field changed

### Q8 - Negative Testing
- Execute invalid requests
- Verify 4xx responses
