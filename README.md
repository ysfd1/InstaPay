# InstaPay System
## Description:

This project implements an Instapay-like system that allows users to transfer money or pay their bills using a variety of services. The system supports the following functionalities:

# Services:
1-Transfer to Another Instapay Account: Users can transfer money to other Instapay users.

2-Transfer to Bank Account: Users registered with their bank account can transfer money to any bank account.

3-Transfer to a Mobile Wallet: Users can transfer money to mobile wallets provided by telecommunications companies (e.g., Vodafone Cash), banks (e.g., CIB), or electronic payment companies (e.g., Fawry).

4-Pay Utilities’ Bills: Users can pay for Gas, Electricity, or Water bills.

# Requirements

User Registration and Authentication

1-Signup Options:

-Using Bank Account: Users can register using their bank account and the registered mobile number, verified through the bank's API.

-Using Mobile Wallet: Users can register using their mobile number and a wallet from a provider, verified through the wallet provider.

2-Verification Process:

-After verifying the bank account or wallet, the system sends an OTP to the user’s mobile number for verification.

-Users must enter a unique username and a complex password.

3-Sign In: Users can sign in using their Instapay username and password. Upon logging in, the user profile is loaded based on the user type.

# User Capabilities

1-Transfer to Wallet: Users can transfer money to a wallet using a mobile number.

2-Transfer to Another Instapay Account: Users can transfer money to another Instapay account.

3-Inquire About Balance: Users can check their account balance.
4-Pay Bills: Users can pay their utility bills (Gas, Electricity, Water).
