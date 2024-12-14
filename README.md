## Video Link

https://drive.google.com/file/d/1qQ_MRWjs8NKD-A0TJa4fSwVu9W2BavFB/view?usp=sharing

## RabbitMQ Payment Notification System

This project implements a payment notification system using RabbitMQ, Node.js, and Nodemailer to simulate a real-world asynchronous messaging system. 
The goal is to manage and process payment workflows and notify users about the status of their payments via email, ensuring a seamless and reliable messaging system.

The project uses RabbitMQ to manage three queues:

payment_queue for processing payment transactions.
notification_queue for sending email notifications.
compensation_queue for handling failed payments.

### Technical Stacks

- Node.js
- RabbitMQ
- Nodemailer
- JavaScript


### Services

- Payment Service
- Notification Service
- Compensation Service
- Booking Service


### Installation & Run

-Install Node.js 
-Install and configure RabbitMQ.
-Set up an SMTP server (in this case, Gmail SMTP).

### Your .env file
SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
SMTP_USER=youremail@gmail.com
SMTP_PASS=yourpassword

Start each service in separate terminals:

# Start Payment Service
node payment-service.js

# Start Notification Service
node notification-service.js

# Start Compensation Service
node compensation-service.js

# Start Booking Service
node booking-service.js



