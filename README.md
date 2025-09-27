# RESTFULAPI_PROJECT - Postman Collection

This repository contains a Postman collection for testing the [Restful Booker API](https://restful-booker.herokuapp.com/).

## 📌 Overview
The collection provides requests to test:
- 🔑 **Authentication** (token generation)
- 🩺 **Health Check** (`/ping`)
- 📖 **Booking operations** (Create, Read, Update, Delete)

## 📂 Files
- `RESTFULAPI_PROJECT.postman_collection.json` → Postman collection with all requests and variables
- `README.md` → Project documentation

## ⚙️ Variables
All required variables are **already included inside the collection**, so no separate environment file is needed.

- `baseurl` → `https://restful-booker.herokuapp.com`
- `BookingID` → Default `1` (updated dynamically after creating a booking)
- `firstname`, `lastname`, `totalprice`, `depositpaid`, `checkin`, `checkout`, `additionalneeds`, `token`

## 🚀 Usage

### Import into Postman
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
