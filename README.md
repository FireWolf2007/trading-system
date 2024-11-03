# trading-system

# DB

## User
### Login
### Password
### OTP?
### BonusId
### First Name
### Middle Name?
### Last Name
### Order Address

## Wallet
### user link
### currency link
### amount (~)
### name?

## Currency
### Sign
### Rate (current rate to base currency)
### Currency History link 

## Currency History (immutable)
### currency link
### Date
### Rate

## Operation Type (immutable)
### Name (sell/buy - bid; exchange)
### Function

## History
### wallet withdraw link
### currency link
### operation type link
### operation table id
### value

## Tax Type (immutable)
### Name
### CalculationFunction

## Tax (immutable)
### tax type link
### value
### currency link
### tax packet link

## Tax packet (immutable)
### name

## Settings
### Base currency

## Trade Operation
### Name
### Type (sell,buy)

## Current Bids
### date nano (order)
### history link
### trade operation link
### currency link
### Tax link
### TaxCurrency = currency history link
### TaxCalculatedValue = calculated
### calculated bid value

## Exchange orders (immutable)
### history link
### src value
### src currency link
### Tax link
### TaxCurrency = currency history link
### TaxCalculatedValue = calculated
### dest currency link
### dest calculated value = calculated
### done date?

## Exchange order history (immutable)
### history link
### src value
### src currency link
### Tax link
### TaxCurrency = currency history link
### TaxCalculatedValue = calculated
### dest currency link
### dest calculated value = calculated
### done date


# API

# MICROSERVICES

## Exchange
### Sell
### Buy

## Tax
### List
### Calculation
### Management

## Wallet
### List
### Top-up
### Withdraw
### Exchange

## Currency
### Management
### Rate (List)

## Auth
### User

## History
### Currency
### Wallet

## Settings
### Set Base currency

## 