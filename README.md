# REST API Enhancement and Django Application Refinement

## Part 1: REST API Enhancement

### Email Verification and Rate Limiting

1. **Email Verification:**
   - Implement email verification for registered users. When a user registers, a verification email will be sent with a unique link for verification.
   - Users need to click the verification link to confirm their email address.

2. **Rate Limiting:**
   - Restrict the number of requests to contact routes for each user to prevent abuse.
   - Implement rate limiting with a reasonable threshold to control the speed of creating contacts.

### CORS Enablement

3. **CORS (Cross-Origin Resource Sharing):**
   - Enable CORS for the REST API to allow requests from different origins.
   - Implement proper CORS headers to define which origins are permitted to access the API.

### Avatar Update with Cloudinary

4. **Avatar Update:**
   - Allow users to update their avatars.
   - Implement integration with the Cloudinary service for handling avatar uploads.

### Docker Compose

5. **Docker Compose:**
   - Set up a Docker Compose configuration to facilitate the easy launch of all services and databases required by the application.
   - Ensure that environment variables are loaded from a `.env` file.

### Additional Task (Optional)

6. **Redis Caching:**
   - Implement caching using Redis.
   - Cache the current user's information during authentication to enhance performance.

7. **Password Reset Mechanism:**
   - Implement a mechanism for users to reset their passwords if forgotten.
   - Users should receive an email with instructions on resetting their password.

## Part 2: Django Application Refinement

### Password Reset Mechanism

1. **Password Reset:**
   - Implement a password reset mechanism for registered users.
   - Users should receive an email with a secure link for resetting their password.

### Environment Variables and Settings

2. **Environment Variables:**
   - Store all environment variables in a `.env` file for both the Django application and the FastAPI REST API.
   - Utilize these environment variables in the `settings.py` file of the Django application.

---

These enhancements and refinements aim to make the applications more secure, user-friendly, and efficient. The implementation of features like email verification, rate limiting, CORS support, and avatar updates contribute to a robust and reliable user experience. Additionally, the use of Docker Compose ensures easy deployment, while optional features like Redis caching and password reset mechanisms add further functionality.
