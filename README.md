# Go Stripe Backend

A simple, secure Go server that integrates with Stripe to process payments. This project demonstrates how to handle PaymentIntents and manage secrets securely using environment variables.

##  Features
- **Secure:** Uses `.env` to store Stripe API keys.
- **Robust:** Includes server-side price calculation and validation.
- **Clean:** Implements Go's standard `net/http` library.

##  Prerequisites
- [Go](https://go.dev/dl/) (version 1.18 or higher)
- A [Stripe Account](https://stripe.com) for API keys

## ⚙️ Setup Instructions
 1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Davoole/golang-stripe-backend.git](https://github.com/Davoole/golang-stripe-backend.git)
   cd golang-stripe-backend
