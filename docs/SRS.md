# Software Requirements Specification (SRS)

## Requirement Review Activity

---

### 1. The system should be user-friendly.

Problems:
- Not clear
- Not measurable
- Not testable
- Ambiguous

Improved Requirement:
The system shall allow a new user to complete the registration process within 2 minutes without external assistance.

---

### 2. The system shall store student records safely.

Problems:
- "Safely" is vague
- Not measurable
- Not specific

Improved Requirement:
The system shall store student records in an encrypted database using AES-256 encryption.

---

### 3. The system should load quickly.

Problems:
- "Quickly" is not measurable
- Not testable
- Ambiguous

Improved Requirement:
The system shall load the dashboard page within 3 seconds under normal internet conditions (10 Mbps).

---

### 4. The system shall allow users to register, login, and manage their profile.

Problems:
- Not atomic (multiple requirements combined)
- Not detailed

Improved Requirements:
1. The system shall allow users to register using email and password.
2. The system shall allow registered users to log in using valid credentials.
3. The system shall allow users to update their profile information.

---

### 5. The system shall send notifications.

Problems:
- Not specific
- Not clear what type of notification
- Not measurable

Improved Requirement:
The system shall send an email notification to users within 1 minute after successful registration.
