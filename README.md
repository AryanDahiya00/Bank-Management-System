# Bank Management System Documentation

## Project Overview
The Bank Management System is a C-based application that automates banking operations for users. It provides a comprehensive solution for managing customer accounts, transactions, and basic banking operations.

## System Features
### 1. Account Management
- Create new customer accounts
- Update existing account information
- Remove existing accounts
- View customer lists
- Check account details

### 2. Transaction Management
- Deposit funds
- Withdraw funds
- Account balance tracking
- Transaction history

### 3. Account Types Support
- Savings Account
- Current Account
- Fixed Deposit Accounts
  - 1-year term (Fixed1)
  - 2-year term (Fixed2)
  - 3-year term (Fixed3)

### 4. Interest Calculation
- Different interest rates based on account type:
  - Savings: 8% per annum
  - Fixed1: 9% per annum
  - Fixed2: 11% per annum
  - Fixed3: 13% per annum
  - Current: No interest

## Technical Specifications

### Development Environment
- Operating System: Windows 10
- Programming Language: C
- Backend Storage: Text file-based database
- Development Tool: Notepad

### Hardware Requirements
- Personal Computer
- HP Desk Jet 3500 series printer (for printouts)

## System Architecture

### Main Menu Options
1. Create new account
2. Update information of existing account
3. Transactions
4. Check existing account details
5. Remove existing account
6. View customer's list
7. Exit

### Data Structure
Customer information stored includes:
- Account number
- Name
- Date of birth
- Age
- Address
- Citizenship number
- Phone number
- Account type
- Balance
- Deposit date

## System Workflows

### 1. Account Creation Process
1. Enter current date
2. Input account number
3. Enter customer details
4. Choose account type
5. Make initial deposit

### 2. Transaction Process
1. Enter account number
2. Select transaction type (deposit/withdraw)
3. Enter transaction amount
4. Process transaction
5. Update balance

### 3. Account Update Process
1. Enter account number
2. Select information to update
   - Address
   - Phone number
3. Enter new information
4. Save changes

### 4. Account Verification
- Search by account number
- Search by customer name
- Display complete account details
- Show applicable interest calculations

## Security Features
- Password-protected system access
- Validation checks for account numbers
- Transaction verification
- Data integrity checks

## Testing Methodology
### Testing Phases
1. Unit Testing
   - Individual function testing
   - Program block verification

2. Module Testing
   - Module functionality verification
   - Inter-unit interaction testing

3. Integration Testing
   - Cross-module functionality
   - Interface testing

4. Acceptance Testing
   - User environment testing
   - System functionality verification

## System Implementation
### Database Structure
- Text file-based storage system
- Record-based data organization
- Sequential data access
- Data persistence across sessions

### Error Handling
- Input validation
- Transaction verification
- Account existence checks
- Balance sufficiency verification
- Duplicate account prevention
