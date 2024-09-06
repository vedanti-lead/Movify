

# 🎬 Movify - Movie Seat Booking Website

**Movify** is a dynamic and scalable movie seat booking platform designed with a focus on performance and security. The project integrates cloud services for a seamless experience, ensuring both scalability and security for users.

## ✨ Features

- **Frontend**: Built with **HTML**, **CSS**, and **JavaScript** for a smooth and responsive seat selection interface.
- **Seat Selection**: Powered by **JavaScript**, users can easily choose their preferred seats in real-time.
- **Cloud Deployment**: 
  - The frontend is deployed on **Amazon EC2** for high availability and performance. Alternatively, **Amazon S3** can also be used for static hosting.
  - Backend is securely deployed using **AWS VPC** with subnets for controlled networking.
- **Database**: User booking details are stored in **AWS RDS** for reliable and scalable database management.
- **Event-Driven Architecture**: Integrated with **AWS Lambda** for event-triggered functions, ensuring efficient processing when users submit booking information.
- **Security**: **AWS WAF (Web Application Firewall)** is applied to protect against common web vulnerabilities and enhance security.
- **Scalability**: The entire infrastructure is designed to scale, handling growing traffic without compromising performance.

## 🚀 How It Works

1. Users select their movie and preferred seats on the interactive frontend.
2. Upon proceeding to payment, user details are submitted via the **Payment Page**.
3. Submissions trigger an **AWS Lambda** function, securely storing the data in **AWS RDS**.
4. The system ensures security using **AWS WAF** and scalable backend architecture with **AWS VPC** and subnets.

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: AWS Lambda, AWS RDS, AWS VPC, Subnets
- **Cloud Deployment**: Amazon EC2 (for frontend), S3 (optional), AWS RDS (for database)
- **Security**: AWS WAF
- **Scalability**: Designed for large-scale deployment

## 🌐 Deployment

- **Frontend** is deployed on **Amazon EC2** (or **S3** for static hosting).
- **Backend** is deployed on **AWS VPC**, using **subnets** and secured with **AWS WAF**.



