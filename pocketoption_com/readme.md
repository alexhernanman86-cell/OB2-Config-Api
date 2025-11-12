# PocketOption.com OpenBullet2 Config

Binary Options Trading Platform Login Checker

## Features
- Login validation with comprehensive error handling
- Account information extraction
- Balance and account details capture
- Multiple data points extraction (email, balance, account ID, username, etc.)

## Usage
1. Load this config in OpenBullet2
2. Use Credentials wordlist format (username:password or email:password)
3. Configure proxies if needed
4. Run the config

## Extracted Data
- Email
- Username
- Account ID
- Balance
- Available Balance
- Bonus Balance
- First Name
- Last Name
- Phone Number
- Country
- Currency
- Verified Status
- Access Token
- Refresh Token

## Notes
- Supports proxy usage
- Extracts comprehensive account information on successful login
- Handles various error responses
- Uses Bearer token authentication for account info requests

## API Endpoints Used
- POST /api/v1/login - Login endpoint
- GET /api/v1/account - Account information endpoint
- GET /api/v1/balance - Balance information endpoint
