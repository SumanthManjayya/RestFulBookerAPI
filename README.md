# RESTFULAPI_PROJECT - Postman Collection

This repository contains a Postman collection for testing the [Restful Booker API](https://restful-booker.herokuapp.com/).

## 📌 Overview
The collection provides requests to test:
- 🔑 Authentication (token generation)
- 🩺 Health Check (`/ping`)
- 📖 Booking operations (Create, Read, Update, Delete)

## 📂 Collection File
- `RESTFULAPI_PROJECT.postman_collection.json`

## ⚙️ Variables
The collection uses the following variables:
- `baseurl` → `https://restful-booker.herokuapp.com`
- `BookingID` → Default `1` (updated dynamically after creating a booking)
- `firstname`, `lastname`, `totalprice`, `depositpaid`, `checkin`, `checkout`, `additionalneeds`, `token`


   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
