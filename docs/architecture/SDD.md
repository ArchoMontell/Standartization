# SDD — Software Design Document

## 1. Архітектура
Мікросервісна

## 2. Компоненти

- API Gateway
- Auth Service
- User Service
- Flight Service
- Booking Service
- Payment Service
- Notification Service

## 3. Взаємодія
Клієнт → API Gateway → Сервіси

## 4. API

### Auth
POST /auth/login

### Flights
GET /flights

### Booking
POST /bookings

### Payment
POST /payments

## 5. База даних

User  
Flight  
Booking  
Payment