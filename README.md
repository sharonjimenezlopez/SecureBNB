# SecureBnB

Academic web application for managing accommodations, activities, and tourism services, developed with a primary focus on information security. The system serves as an evaluation platform for security controls applied both to the application and to the infrastructure that supports it.

The project simulates an Airbnb-style system, incorporating robust authentication, access control, sensitive data protection, and defense mechanisms at both the network and application levels.

## My contribution

This was a team project. I built the **admin panel**, including the interface and functionality for:

- Approving or rejecting accommodations, activities, and services
- Viewing the list of registered users

> **Note:** This repository was cloned from the original team project for portfolio purposes. I don't have access to the production database or to the hardware 2FA device (YubiKey) used for admin authentication in the original deployment, so the admin panel can't be fully demoed live in its original environment.

## Tech stack

**Frontend**
- React
- Vite
- JavaScript
- HTTPS

**Backend**
- Node.js
- Express.js
- REST API with authentication and authorization

**Database**
- PostgreSQL
- Least-privilege credential access
- Parameterized queries to prevent SQL injection

## Running locally

```bash
# Clone the repository
git clone https://github.com/your-username/securebnb.git
cd securebnb

# Install dependencies
npm install

# Run in development mode
npm run dev
```

> Note: full functionality requires a configured PostgreSQL database and 2FA hardware device, which are not included in this repository.

## License

This project was developed as part of an academic assignment by a team. Shared here for portfolio purposes.
