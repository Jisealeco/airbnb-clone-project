## API Security
 
### 1. Authentication

**What it is**:

Verifies the identity of users making API requests.

**Implementation**:

. Token-based authentication (e.g., JWT)

. Passwords stored using secure hashing algorithms (e.g., bcrypt)

**Why it is Crucial**:

Prevents unauthorized users from accessing user accounts or personal information.

### 2. Authorization

**What it is**:

Controls what authenticated users are allowed to do within the system.

**Implementation**:

. Role-based access control (e.g., guest vs. host vs. admin)

. Route-level access restrictions

**Why it is Crucial**:

Prevents users from performing actions outside their permissions (e.g., editing someone else’s property or accessing admin tools).

### 3. Rate Limiting

**What it is**:

Limits the number of requests a user or IP can make in a given time frame.

**Implementation**:

. Implemented via middleware (e.g., Flask-Limiter, Django Ratelimit, or NGINX rules)

**Why it is Crucial**:

Protects the API from brute-force attacks, spamming, and potential denial-of-service (DoS) attempts.

