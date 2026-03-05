# MERN E-COMMERCE 

Hi! My name is **Orxan Ulfatli**,This is full stack e-commerce app with full functionality I have created this project to improve my skills in web development.



# Install Dependencies

**For Backend** - `npm i`

**For Frontend** - `cd frontend` ` npm i`

## Env Variables

Create `config/config.env` in this server project root and fill it with:

```env
# Server
PORT=
NODE_ENV=DEVELOPMENT

# Database
DB_URI=

# Auth
JWT_SECRET=
JWT_EXPIRE=5d
COOKIE_EXPIRE=5

# Client URL (used in password reset link)
CLIENT_URI=http://localhost:3000

# Stripe
STRIPE_API_KEY=
STRIPE_SECRET_KEY=

# SMTP (note: code uses SMPT_* variable names)
SMPT_HOST=
SMPT_PORT=
SMPT_MAIL=
SMPT_PASSWORD=

# Cloudinary
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

Note:
- `config/config.env` is ignored by git, so it will not be pushed.
- For deployed environments, set the same variables in your hosting provider's Environment Variables section.

## Author

Orxan Ulfatli  
**LinkedIn:** [https://www.linkedin.com/in/orxanulfatli/](https://www.linkedin.com/in/orxanulfatli/)

